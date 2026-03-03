# Wiki: Problemlösung

## Häufige Probleme

### 1) Download klappt nicht

- Update erneut prüfen
- App neu starten
- Release-Seite direkt öffnen: <https://github.com/breiti35/ets2-overlay-feed/releases/latest>

### 2) Bot reagiert nicht

- Twitch/YouTube aktiv?
- Zugangsdaten korrekt?
- Cooldown zu hoch?

### 3) Keine Telemetrie

- ETS2 läuft?
- Diagnose-Block in `System` kontrollieren

### 4) OBS zeigt falsche Größe

- OBS Browser Source auf gleiche Auflösung wie `Canvas Auflösung` stellen

### 5) Linux: AppImage startet nicht (libfuse.so.2)

- `.tar.gz`-Variante aus den Releases verwenden (kein FUSE nötig)
- oder: `APPIMAGE_EXTRACT_AND_RUN=1 ./ets2-overlay-*.AppImage`

Für Details: [docs/Problemloesung.md](../docs/Problemloesung.md)
