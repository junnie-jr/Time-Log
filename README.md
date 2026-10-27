# Punch

Minimal time in / time out log. Works offline and installs as an app.
Logs are stored in your browser (localStorage), on that device only.

## Publish on GitHub Pages
1. Create a repo (e.g. `punch`) and upload everything in this folder, keeping the `icons/` folder.
2. Settings → Pages → Build and deployment → Deploy from a branch → `main` / `/ (root)` → Save.
3. Open `https://<your-username>.github.io/punch/`.

## Install
- Android / Chrome: menu → Install app.
- iPhone / Safari: Share → Add to Home Screen.
- Desktop Chrome / Edge: install icon in the address bar.

## Updating
After changing any file, bump `VERSION` in `sw.js` (e.g. `punch-v2`) so installed copies refresh.
