# Minimal RSS Reader PWA

A clean, light, and responsive RSS reader application built with single-page HTML, Tailwind CSS, and Service Worker capabilities for Progressive Web App (PWA) installation.

## Files Included

- `index.html` - The primary entry point containing the UI layout, RSS parsing logic, local state management, and install handlers.
- `manifest.json` - Web App Manifest defining standalone mode, theme colors, and icons.
- `sw.js` - Service Worker for caching application assets and offline capability.
- `README.md` - Documentation and setup instructions.

## Local Setup & Testing

1. Unzip the file archive.
2. Serve the directory via an HTTP server (e.g., using Python: `python -m http.server 8000`).
3. Open `http://localhost:8000` in your browser.

## Deploying to GitHub Pages

1. Push these repository files to a public GitHub repository.
2. Go to **Settings > Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**, choose `main` / `root`, and save.
4. Access your live site HTTPS URL to install it as an app on Android or Desktop.
