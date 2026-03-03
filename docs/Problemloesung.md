# Problemlösung

## Update zeigt 404 beim Download

Ursache: alter Link oder gecachter Feed.

Lösung:

1. In `System -> Update & Diagnose` auf `Jetzt auf Updates prüfen` klicken
2. App neu starten
3. Wenn nötig kurz warten (CDN/Pages-Cache)

## Klick auf "Herunterladen" öffnet kein Browserfenster

Seit den aktuellen Versionen werden externe Links direkt im Standardbrowser geöffnet.

Wenn trotzdem ein internes Fenster erscheint:

1. App auf neueste Version updaten
2. App komplett beenden und neu starten

## Telemetrie bleibt offline

Prüfe im Bereich `Update & Diagnose`:

- `Telemetrie Modus`
- `SDK verbunden`
- `Letzte Daten`
- `Diagnose Hinweis`

Tipps:

- ETS2 muss laufen
- auf Linux/Proton: sicherstellen, dass Bridge/Prozesszugriff funktioniert

## Twitch Bot antwortet nicht

Prüfen:

- `Twitch Bot aktiv` eingeschaltet
- Username, OAuth-Token und Channel korrekt
- Cooldown nicht zu hoch

## YouTube Bot antwortet nicht

Prüfen:

- `YouTube Bot aktiv` eingeschaltet
- API-Key gültig
- Live-Video-ID korrekt

## Einstellungen sind nach Neustart weg

Die App speichert Settings lokal in einer `config.json` im AppData-Ordner.

Wenn Werte fehlen:

- App mit Schreibrechten starten
- nicht gleichzeitig mehrere Instanzen nutzen

## Overlay in OBS falsch skaliert

Stelle sicher, dass `Canvas Auflösung` und OBS Browser Source dieselbe Auflösung nutzen.

## Linux: AppImage startet nicht (`libfuse.so.2`)

**Fehlermeldung:**

```
dlopen(): error loading libfuse.so.2
```

**Ursache:** AppImage benötigt FUSE 2 (`libfuse2`). Ubuntu 22.04+, Fedora 34+ und Arch liefern standardmäßig nur noch FUSE 3.

**Lösung A – tar.gz verwenden (empfohlen):**

Ab v1.0.10-alpha.6 gibt es zusätzlich zum AppImage ein `.tar.gz`-Archiv auf der [Release-Seite](https://github.com/breiti35/ets2-overlay-feed/releases/latest).

```bash
tar -xzf ets2-overlay-*.tar.gz
cd ets2-overlay-*/
./ets2-overlay --no-sandbox
```

**Lösung B – AppImage ohne FUSE starten:**

```bash
APPIMAGE_EXTRACT_AND_RUN=1 ./ets2-overlay-*.AppImage
# oder:
./ets2-overlay-*.AppImage --appimage-extract-and-run
```

**Lösung C – libfuse2 nachinstallieren:**

```bash
# Ubuntu/Debian:
sudo apt install libfuse2

# Fedora:
sudo dnf install fuse
```
