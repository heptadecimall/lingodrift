# LingoDrift

Track the words and phrases you use, and how each one drifts over time.

LingoDrift is a single-page web app with no build step and no server. Your lingo is stored in your browser on your own device.

## Use it

Open the GitHub Pages site for this repository.

**iPhone / iPad (Safari):** tap the Share button, then **Add to Home Screen**. LingoDrift then opens full screen like an app and works offline.

**Android (Chrome):** open the menu, then **Install app** or **Add to Home screen**.

## Your data

- Everything is saved in the browser on that device. Nothing is uploaded.
- Each browser, and each home-screen copy, keeps its own separate list. On iPhone, the home-screen app and a Safari tab don't share data.
- Use **Settings → Backup → Export backup** to save a JSON file, and **Import backup** to load it on another device or browser.

## Files

| File | What it is |
| --- | --- |
| `index.html` | The whole app (HTML, CSS and JavaScript) |
| `sw.js` | Service worker that keeps the app working offline |
| `manifest.webmanifest` | App name, colours and icons for installing |
| `icon*.png`, `icon.svg` | App icons |
