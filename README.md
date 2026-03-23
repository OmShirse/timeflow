# TimeFlow

A lightweight time tracking web app — built as a Progressive Web App (PWA) so it works offline and can be installed on any device like a native app.

## Live Demo

🔗 **[omshirse.github.io/timeflow](https://omshirse.github.io/timeflow)**

## What it does

- Track time across tasks and sessions
- Works offline — no internet needed after first load
- Installable on desktop and mobile (PWA)
- No backend, no login — runs entirely in the browser

## Run locally

No build step needed — just open the file:

```bash
git clone https://github.com/OmShirse/timeflow.git
cd timeflow
# open index.html in your browser
```

Or serve it locally for PWA features to work:

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

> PWA features like offline mode and install prompt only work when served over HTTP — not when opening `index.html` directly as a file.

## Tech stack

- HTML, CSS, JavaScript — single file, no framework
- Web App Manifest (`manifest.json`) for PWA install support
- Service Worker for offline caching

## Files

| File | Description |
|---|---|
| `index.html` | Entire app — UI, logic, and styles |
| `manifest.json` | PWA manifest — name, icons, theme |
| `icon-192.png` | App icon (192×192) |
| `icon-512.png` | App icon (512×512) |
