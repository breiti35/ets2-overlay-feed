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
