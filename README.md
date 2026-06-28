# Pharmacy Management System

A single-file, browser-based pharmacy management app (inventory, sales, purchases, customers, suppliers, expiry tracking, audit log).

## Important: data storage
This app stores all its data in your browser's `localStorage`, scoped to whatever domain it's served from. That means:
- Data persists across reloads and deploys **as long as the URL stays the same**
- Data is **per-browser, per-device** — it does not sync between computers or browsers
- Clearing site data/cookies for this domain will wipe it

## Deployment
This site auto-deploys to Netlify on every push to `main`. No build step — it's a static `index.html`.
