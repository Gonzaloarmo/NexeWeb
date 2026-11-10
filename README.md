# NEXO — Landing page

Static site. No build step.

## Structure
- `index.html` — the page
- `support.js` — runtime the page needs (keep next to index.html)
- `uploads/` — hero video and poster
- `vercel.json` — static config

## Deploy to Vercel
1. Push this folder to a GitHub repo (files at the repo root).
2. In Vercel: New Project → import the repo.
3. Framework preset: **Other**. Leave Build Command and Output Directory empty.
4. Deploy.

## Run locally
```
npx serve .
```
Opening the file directly via `file://` will block the globe's module imports — use a local server.
