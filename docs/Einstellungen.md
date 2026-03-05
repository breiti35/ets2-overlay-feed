# Einstellungen

Das Control Panel ist in mehrere Bereiche aufgeteilt.

## Layout Designer

- Positionen von Modulen setzen
- Größen und Skalierung anpassen
- Presets laden/speichern

## Module

- Module ein-/ausblenden
- sichtbare Elemente pro Szene steuern

## Design

- Theme wechseln
- Farben, Transparenz und Stilwerte anpassen
- `Minimal (Clean)` bietet einen aufgeräumten, helleren Widget-Look

## System

### Einheiten

- Speed (`km/h` oder `mph`)
- Distanz (`km` oder `miles`)
- Volumen (`Liter` oder `Gallon`)

### Overlay

- Popup-Dauer
- Command-Cooldown
- Global Scale
- Canvas-Auflösung

### OBS

- Overlay-URL kopieren und in OBS als Browser Source verwenden

### Update & Diagnose

- Update-Status live anzeigen
- manuell auf Updates prüfen
- Diagnose aktualisieren
- erweiterte Diagnose starten
- Der Banner-Button führt auf die öffentliche Download-Seite mit Plattform-Auswahl
- Oeffentlicher Feed nutzt nur den `stable`-Kanal (Alpha bleibt intern)

## In-Game Overlay (Beta)

Eigene Sparte fuer ein Desktop-Overlay direkt ueber dem Spiel (getrennt vom OBS Browser Overlay).

- Plattformziel: Windows stabil, Linux experimentell
- Global ein-/ausschalten
- Always-on-top, Click-through, Deckkraft
- Auto-Hide bei Fokusverlust (Overlay blendet automatisch aus, wenn ETS2/ATS nicht im Vordergrund ist)
- Radar FPS Limit waehlbar (`24`, `30`, `45`, `60`) fuer bessere Performance-Kontrolle
- globaler Hotkey zum Ein-/Ausblenden
- Widgets einzeln steuerbar: `job`, `fuel`, `damage`, `time`, `indicators`, `weather`, `session`, `radar`, `gear`
- Legacy-Option: `info` als Komplettpanel bleibt optional verfuegbar
- Legacy-`info` nutzt volle Fensterhoehe, damit keine Unter-Module abgeschnitten werden
- In-Game Layout Designer mit Drag-and-Drop fuer Widget-Positionen (X/Y werden live synchronisiert)
- Demo-Modus: Overlay mit simulierten Fahrtdaten ohne laufendes Spiel starten
  (Settings → In-Game → „Demo-Modus starten")
- Demo-Badge (orange, oben mittig) kennzeichnet den Modus visuell
- Fake-Chat-Nachrichten erscheinen automatisch alle 3–8 Sekunden im Demo-Modus
- Editor-Modus: Blauer Bar mit „✕ Editor beenden"-Button oben im Overlay zum einfachen Beenden

## Twitch Setup

- Bot aktivieren
- Bot-Username, OAuth-Token und Channel eintragen

## YouTube Setup

- Bot aktivieren
- API-Key und Live-Video-ID eintragen

## Custom Commands

- eigene Befehle wie `!discord` anlegen
- Antworttexte mit `{user}`-Platzhalter nutzen
