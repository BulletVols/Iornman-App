# Ironman Build: phone app version

This folder is a Progressive Web App. Host it anywhere that serves HTTPS (GitHub Pages is free), open it on your phone, and add it to your home screen.

## Put it online with GitHub Pages
1. Create a new public repository on GitHub, e.g. `ironman-app`.
2. Upload everything in this folder (index.html, sw.js, manifest.webmanifest, the icons folder).
3. Repository Settings > Pages > Source: "Deploy from a branch", branch `main`, folder `/ (root)`. Save.
4. After a minute your app is at `https://<your-username>.github.io/ironman-app/`.

## Install on your phone
- iPhone (Safari): open the link, tap Share, then "Add to Home Screen".
- Android (Chrome): open the link, tap the menu, then "Install app" or "Add to Home screen".

## Your data
In this version, logs are stored on the phone itself (they don't sync). Use "Export CSV" in the Log tab regularly as a backup.

## Updating
Replace index.html in the repo, then change `VERSION` at the top of sw.js (e.g. `ironman-v2`) so phones load the new version.
