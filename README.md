# ETS2 Overlay Feed

Dieses Repository ist die öffentliche Update- und Download-Quelle für den Desktop-Client von ETS2 Overlay.

Hier findest du:

- öffentliche Releases (Windows Installer + Linux AppImage)
- `version.json` für den In-App-Update-Checker
- kompakte Nutzer-Dokumentation zu Funktionen, Einstellungen und Bot-Kommandos
- eine kleine Troubleshooting-Wiki im Repo

## Schnellstart

1. Öffne die aktuellen Downloads: [Releases](https://github.com/breiti35/ets2-overlay-feed/releases/latest)
2. Installiere die passende Datei:
   - Windows: `ETS2.Overlay.Setup-<version>.exe`
   - Linux: `ETS2.Overlay-<version>.AppImage`
3. Starte die App und öffne im linken Menü den Bereich `System`.
4. Im Block `Update & Diagnose` kannst du jederzeit auf `Jetzt auf Updates prüfen` klicken.

## Dokumentation

- [Übersicht](docs/README.md)
- [Funktionen](docs/Funktionen.md)
- [Einstellungen](docs/Einstellungen.md)
- [Bot-Kommandos](docs/Bot-Kommandos.md)
- [Problemlösung](docs/Problemloesung.md)

## Mini-Wiki (im Repo)

- [Wiki Home](wiki/Home.md)
- [Wiki Problemlösung](wiki/Problemloesung.md)

Hinweis: Die GitHub-Wiki kann später zusätzlich aktiviert/befüllt werden. Solange sie leer ist, liegen die Wiki-Inhalte direkt im Ordner `wiki/`.

## Update-Feed

Der Client liest diese Datei als Update-Quelle:

- [`version.json`](version.json)

Beispiel-Felder:

- `version`
- `downloadUrl`
- `downloadUrlLinux`
- `downloadUrlWindows`
- `changelog`

## Support

Wenn etwas nicht funktioniert, starte mit [Problemlösung](docs/Problemloesung.md). Dort sind die häufigsten Ursachen und Fixes gesammelt.

## Issue-Handling

Neue Issues in diesem öffentlichen Repository werden automatisch in das private Entwicklungs-Repository gespiegelt, damit die Umsetzung intern erfolgen kann.

- Du erhältst im öffentlichen Issue einen Kommentar mit der internen Referenz.
- Labels aus dem öffentlichen Issue werden automatisch ins private Issue übernommen.
- Der öffentliche Thread bleibt für Rückfragen sichtbar.
