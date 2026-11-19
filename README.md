# LootLog

LootLog counts the chests you open in Fortnite. It tracks them live while you play, then double-checks every match against the replay Fortnite saves, so the numbers end up right even if something was missed.

On top of that you get stats per match and session, routes with markers on the map, a small in-game overlay, and a friends leaderboard.

This is a fan project. It is not made or endorsed by Epic Games.

## Getting started

1. [Download LootLog-Setup.exe](https://github.com/astroidsoap/LootLog/releases/latest/download/LootLog-Setup.exe) and run it. Windows may warn you because the app isn't signed. Click "More info" and then "Run anyway".
2. Click Install. No admin rights needed. The setup grabs Python if you don't have it and puts LootLog on your desktop and in the start menu.
3. In Fortnite, make sure Settings > Game > Record Replays is on. It usually is.

That's it. LootLog opens after the install and checks that it can find your replays.

Updates install themselves. LootLog looks for a new version every few hours and only installs it while you're in the lobby, never mid-match. Your matches, routes and settings stay as they are.

To uninstall, go to Windows Settings > Apps > LootLog.

## How it counts

During a match LootLog watches for the "Search" prompt and the "+XP CHEST" message Fortnite shows when you open a chest. It also reads the whole XP list, so a quick run of chests ("RARE CHEST X2", "SPRITE CHEST" and so on) is counted correctly too.

After the match it reads the replay. Anything live tracking missed gets added, and anything that wasn't really a chest gets removed. Chests you smash instead of open only show up this way.

## Is it safe to use?

LootLog only looks. It reads pixels from your screen the way OBS does, reads Fortnite's log file, and reads replays after the match is over. It doesn't touch game memory, doesn't send any input to the game and doesn't change game files. There are no features for spotting enemies, footsteps or anything like that.

Use it at your own risk and stick to Epic's terms of service.

## Privacy

Everything stays on your PC in `%LOCALAPPDATA%\LootLog\data`. The only things that go online are the island map (once per season), the update check on GitHub, and, if you turn it on, the friends sync, which shares your Epic name, chest count and wins with the friends you add.

## Problems?

If no replays show up, turn on Record Replays in Fortnite. It only keeps the last few, so they get counted after each match. If something else goes wrong, open Settings > About LootLog > Open log file.

LootLog uses FortniteReplayReader (MIT) and a few other open-source libraries. See `bin\THIRD-PARTY-NOTICES.txt`.
