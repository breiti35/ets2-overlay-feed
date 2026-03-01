# Problemloesung

## Update zeigt 404 beim Download

Ursache: alter Link oder gecachter Feed.

Loesung:

1. In `System -> Update & Diagnose` auf `Jetzt auf Updates pruefen` klicken
2. App neu starten
3. Wenn noetig kurz warten (CDN/Pages-Cache)

## Klick auf "Herunterladen" oeffnet kein Browserfenster

Seit den aktuellen Versionen werden externe Links direkt im Standardbrowser geoeffnet.

Wenn trotzdem ein internes Fenster erscheint:

1. App auf neueste Version updaten
2. App komplett beenden und neu starten

## Telemetrie bleibt offline

Pruefe im Bereich `Update & Diagnose`:

- `Telemetrie Modus`
- `SDK verbunden`
- `Letzte Daten`
- `Diagnose Hinweis`

Tipps:

- ETS2 muss laufen
- auf Linux/Proton: sicherstellen, dass Bridge/Prozesszugriff funktioniert

## Twitch Bot antwortet nicht

Pruefen:

- `Twitch Bot aktiv` eingeschaltet
- Username, OAuth-Token und Channel korrekt
- Cooldown nicht zu hoch

## YouTube Bot antwortet nicht

Pruefen:

- `YouTube Bot aktiv` eingeschaltet
- API-Key gueltig
- Live-Video-ID korrekt

## Einstellungen sind nach Neustart weg

Die App speichert Settings lokal in einer `config.json` im AppData-Ordner.

Wenn Werte fehlen:

- App mit Schreibrechten starten
- nicht gleichzeitig mehrere Instanzen nutzen

## Overlay in OBS falsch skaliert

Stelle sicher, dass `Canvas Aufloesung` und OBS Browser Source dieselbe Aufloesung nutzen.
