# ContracttrackerOE

PWA tracker for OE Corinthian contracts (single-page app).

## Features

- Contract period tracking (start/end date and time)
- Salary calculation (monthly, weekly, or total)
- Progress chart and countdown
- Day/Night theme toggle
- Dynamic card 3D hover effect (desktop)
- Mobile-friendly layout
- Installable as a PWA on Android Chrome
- Offline support via Service Worker cache

## Project Structure

- `index.html`: main UI and app logic
- `manifest.json`: PWA manifest
- `sw.js`: service worker and offline cache
- Image assets (`.png`, `.webp`)

## Run Locally

Because this is a PWA, use a local HTTP server (do not open with `file://`).

Example with Python:

```bash
python -m http.server 8080
```

Then open:

- `http://localhost:8080`

## Install on Mobile

### Android (Chrome)

1. Open the app URL in Chrome.
2. Tap `Install app` (or menu > `Install app`).
3. Launch it from home screen.

### iOS

1. Open the app URL in Safari.
2. Tap Share > `Add to Home Screen`.

## Deploy

Any static hosting with HTTPS works:

- GitHub Pages
- Netlify
- Cloudflare Pages

## Notes

- PWA install requires HTTPS in production.
- If updates do not appear immediately, force refresh (`Ctrl+F5`) to refresh cache.
