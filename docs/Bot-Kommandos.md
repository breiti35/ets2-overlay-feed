# Bot-Kommandos

## Standardbefehle

Die App bringt diese Chat-Kommandos mit:

- `!hilfe`
- `!ladung`
- `!sprit`
- `!job`
- `!schaden`
- `!speed`

## Twitch Bot konfigurieren

In `Twitch Setup`:

1. `Twitch Bot aktiv` einschalten
2. Bot-Username setzen
3. OAuth-Token eintragen (Format meist `oauth:...`)
4. Channel setzen

## YouTube Bot konfigurieren

In `YouTube Setup`:

1. `YouTube Bot aktiv` einschalten
2. API-Key eintragen
3. Live-Video-ID setzen

## Cooldown

Im Bereich `System` kannst du den globalen Command-Cooldown setzen.

- `0` = kein Cooldown
- `30` = jeder Nutzer darf denselben Befehl z. B. alle 30 Sekunden senden

## Eigene Kommandos

Unter `Custom Commands` kannst du beliebige Befehle anlegen:

- Name z. B. `!discord`
- Antwort z. B. `Unser Discord: ...`
- Platzhalter `{user}` wird durch den Namen ersetzt

Beispiel:

- Command: `!moin`
- Antwort: `Moin {user}, schoen dass du da bist!`
