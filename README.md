# 🧰 LootLog

**Der Truhen-Tracker für Fortnite.** LootLog zählt automatisch jede Truhe, die du öffnest: live im Match und danach exakt aus dem Replay. Dazu kommen Statistiken, Routen mit Markern, eine kleine Ingame-Anzeige und eine Rangliste mit deinen Freunden.

### [⬇️ LootLog herunterladen (Windows)](https://github.com/astroidsoap/LootLog/releases/latest/download/LootLog-Setup.exe)

Herunterladen, doppelklicken, **Installieren**, fertig. Du brauchst keine Adminrechte, und Updates kommen automatisch.

> Windows zeigt bei neuen Programmen evtl. *„Der Computer wurde durch Windows geschützt“*. Dann **Weitere Informationen → Trotzdem ausführen** klicken.

---

## Was LootLog kann

| | |
|---|---|
| 🧮 **Exakt zählen** | Nach jedem Match liest LootLog das Fortnite-Replay und zählt jede Truhe, die *du* geöffnet hast, auch zerstörte. Live verpasste Truhen werden nachgetragen, Fehlerkennungen entfernt. |
| 👀 **Live-Zählung** | Erkennt den „Durchsuchen“-Hinweis an Truhen, optional auch das Öffnungsgeräusch. |
| 🖥️ **Mini-Anzeige im Spiel** | Truhen gesamt, im Match, Wins und mehr. Stil, Inhalt und Position kannst du frei einstellen. |
| 🗺️ **Routen & Marker** | Rotationen auf der Karte zeichnen und Marker setzen: Truhe, seltene Truhe, Landepunkt, Gefahr, Notiz, Nummern. Im Match navigiert die Minimap Punkt für Punkt und dreht sich mit deiner Laufrichtung. |
| 👥 **Mit Freunden vergleichen** | Rangliste und Duelle. Mitspieler mit LootLog werden automatisch erkannt, für die anderen wird aus deinem Replay geschätzt. |
| 📊 **Statistik** | Truhen pro Match, Tag, Session und Spielminute, Rekorde, beste Spots, Piraten-Token-Chance. |

## Fair Play
- LootLog **schaut nur zu**:
  - Es liest den Bildschirm wie eine Aufnahme-Software.
  - Es liest die Logdatei von Fortnite.
  - Nach dem Match liest es die Replays, die Fortnite selbst speichert.
- Kein Speicherzugriff, keine Eingaben ans Spiel, keine Änderungen an Spieldateien.
- Bewusst nicht eingebaut: Gegner erkennen, Schritte oder Schüsse orten, Netzwerk mitlesen, Makros.

## Datenschutz
- Alle Daten bleiben **lokal auf deinem PC**.
- Nur wenn du den Freunde-Abgleich einschaltest, werden dein Epic-Name, Truhen, Wins und Match-Zeiten über ntfy.sh geteilt.
- Die Update-Prüfung fragt nur bei GitHub nach der neuesten Version.

## Voraussetzungen
- Windows 10 oder 11
- In Fortnite: **Einstellungen → Spiel → „Replays aufnehmen“ = An** (meist schon Standard)
- Python wird vom Setup automatisch installiert, falls es fehlt.

## Fragen & Probleme
Einfach ein [Issue](https://github.com/astroidsoap/LootLog/issues) aufmachen. Alle Versionen findest du unter [Releases](https://github.com/astroidsoap/LootLog/releases).

---
<sub>LootLog ist ein Fan-Projekt und steht in keiner Verbindung zu Epic Games. Fortnite ist eine Marke von Epic Games, Inc. Replays werden mit der Open-Source-Bibliothek FortniteReplayReader (MIT) gelesen.</sub>
