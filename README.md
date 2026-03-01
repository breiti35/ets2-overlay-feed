# ETS2 Overlay Feed

Dieses Repository ist die oeffentliche Update- und Download-Quelle fuer den Desktop-Client von ETS2 Overlay.

Hier findest du:

- oeffentliche Releases (Windows Installer + Linux AppImage)
- `version.json` fuer den In-App-Update-Checker
- kompakte Nutzer-Dokumentation zu Funktionen, Einstellungen und Bot-Kommandos
- eine kleine Troubleshooting-Wiki im Repo

## Schnellstart

1. Oeffne die aktuellen Downloads: [Releases](https://github.com/breiti35/ets2-overlay-feed/releases/latest)
2. Installiere die passende Datei:
   - Windows: `ETS2.Overlay.Setup-<version>.exe`
   - Linux: `ETS2.Overlay-<version>.AppImage`
3. Starte die App und oeffne im linken Menue den Bereich `System`.
4. Im Block `Update & Diagnose` kannst du jederzeit auf `Jetzt auf Updates pruefen` klicken.

## Dokumentation

- [Uebersicht](docs/README.md)
- [Funktionen](docs/Funktionen.md)
- [Einstellungen](docs/Einstellungen.md)
- [Bot-Kommandos](docs/Bot-Kommandos.md)
- [Problemloesung](docs/Problemloesung.md)

## Mini-Wiki (im Repo)

- [Wiki Home](wiki/Home.md)
- [Wiki Problemloesung](wiki/Problemloesung.md)

Hinweis: Die GitHub-Wiki kann spaeter zusaetzlich aktiviert/befuellt werden. Solange sie leer ist, liegen die Wiki-Inhalte direkt im Ordner `wiki/`.

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

Wenn etwas nicht funktioniert, starte mit [Problemloesung](docs/Problemloesung.md). Dort sind die haeufigsten Ursachen und Fixes gesammelt.
