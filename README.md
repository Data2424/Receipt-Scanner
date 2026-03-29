# Bon Scanner

Kassenbon-Scanner App für Google Sheets. Fotos aufnehmen → KI liest Daten aus → direkt in Google Sheets speichern.

## Features
- 📷 Foto direkt vom Handy oder Upload
- 🤖 Claude Vision liest Datum, Händler, Betrag, Ort automatisch aus
- ✍️ Handschriftliche Notizen auf dem Bon werden erkannt
- 📊 Speichert direkt in Google Sheets (Library/Finance/Receipt Scanner Data)
- 📱 Funktioniert auf jedem Handy im Browser

## Setup

### 1. Google Cloud Console
- Projekt: `receipt-scanner`
- APIs aktiviert: Google Sheets API, Google Drive API
- OAuth 2.0 Client ID (Web application)
  - Authorized JavaScript origins: `https://Data2424.github.io`
  - Authorized redirect URIs: `https://Data2424.github.io/receipt-scanner`

### 2. GitHub Pages
- Repo: `receipt-scanner`
- GitHub Pages aktivieren: Settings → Pages → Branch: main / root

## Nutzung
1. `https://Data2424.github.io/receipt-scanner` im Browser öffnen
2. Mit Google anmelden
3. Bon-Foto(s) hochladen
4. Daten prüfen / korrigieren
5. "In Google Sheets speichern" klicken

## Spalten in Google Sheets
| Datum | Berechnen | Betrag | Zahler | Ort | Bemerkung |
|-------|-----------|--------|--------|-----|-----------|
| YYYY-MM-DD | 1 | 9.32 | Netto | Quickborn | Einkauf |
