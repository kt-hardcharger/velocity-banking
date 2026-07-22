# Velocity Banking Ledger

A single-file web app for weekly HELOC velocity banking. Data is stored in a
Google Sheet via an Apps Script Web App — this repo just hosts the static
`index.html` file that talks to it.

## First run

1. Open the live GitHub Pages URL (see repo Settings → Pages once enabled).
2. Go to the **Setup** tab → **Sync (Google Sheets)**.
3. Paste your Apps Script Web App URL (ends in `/exec`) → **Save & test connection**.
4. Bookmark the link shown afterward (it includes `?api=...`) on your phone's
   home screen — that link opens with sync already configured.

## Updating the app

Edit `index.html` and push to `main`. GitHub Pages redeploys automatically,
usually within a minute or two.
