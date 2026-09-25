# Case Study Automation

Internes Tool von High Performance Mail: Brand + Zeitraum eingeben, das Tool zieht
die Klaviyo-Ergebnisse des Zeitraums und erstellt daraus eine Case Study als Dokument.

## Status

Konzeptphase (Stand 25.09.2026). Noch kein Code.

Beschlossen:
- Pro Brand ein Read-only Private API Key aus Klaviyo, lokal in `.env` (siehe `.env.example`).
- Nutzer: nur das HPM-Team, kein Rechte-System.

Offen:
- Aufbau und Stil der Case Study (Branchen-Beispiele folgen).
- Ausgabeziel des Dokuments (Claude Doc / Google Docs).

## Einrichtung

```
cp .env.example .env
# echte Keys eintragen
```

Neuen Brand-Key anlegen: In Klaviyo in den Brand-Account wechseln → Settings → API Keys →
Create Private API Key → Access Level „Read-only key“ → Key kopieren (wird nur einmal gezeigt).
