# CTI

CTI-P is a minimal time in / time out log. It works offline and installs as an app.
Logs are stored in your browser (localStorage), on that device only.

## Day types
Each day can be logged as Office (default), **WFH** (work from home), **OB** (official business),
**SL** (sick leave) or **VL** (vacation leave). SL and VL need no times.
Pick the type on the time-in prompt, or tap any calendar day to edit it.

## Publish on GitHub Pages
1. Upload everything in this folder to your repo, keeping the `icons/` folder.
2. Settings → Pages → Build and deployment → Deploy from a branch → `main` / `/ (root)` → Save.
3. Open `https://junnie-jr.github.io/Time-Log/`.

## Install
- Android / Chrome: menu → Install app.
- iPhone / Safari: Share → Add to Home Screen.
- Desktop Chrome / Edge: install icon in the address bar.

## Export
Share logs → choose a date range → get an Excel file (Date, Day, Type, Time In, Time Out, Hours).
On phones it opens the share sheet; on desktop the file downloads and your mail app opens.

## Updating
After changing any file, bump `VERSION` in `sw.js` (e.g. `cti-v3`) so installed copies refresh.
