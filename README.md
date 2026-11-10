# DH Athlete 2027

A black-and-white, mobile-first progressive web app for a personal MTB training plan.

## What it does
- Editable 10-day cycle (session name, type, notes, start date)
- Editable exercise library (add, edit, remove, category, dosage, notes)
- Ride and training log
- Sleep, energy, soreness and optional hydration check-ins
- JSON backup export/import
- Offline shell after first successful load

## Install on iPhone
1. Host this folder on an HTTPS static host (GitHub Pages is one option).
2. Open the published HTTPS address in **Safari** on your iPhone.
3. Tap **Share** → **Add to Home Screen** → **Add**.
4. Launch DH Athlete from the new Home Screen icon.

A local file opened from Files will not install as a PWA. It needs an HTTPS website address. The app stores its records in browser storage on that device; export backups regularly. Clearing Safari website data can erase records.

## GitHub Pages quick route
1. Create a GitHub repository and upload the contents of this folder (not the outer ZIP).
2. In repository Settings → Pages, publish from the `main` branch and `/ (root)`.
3. Wait for GitHub Pages to publish, then open the HTTPS URL in Safari.

## Important
This is a personal planning/logging tool, not a medical device or a substitute for a qualified coach. Training suggestions are intentionally conservative; adapt with a parent/guardian and qualified coach, especially for strength and plyometric work. Do not train through pain or persistent fatigue.
