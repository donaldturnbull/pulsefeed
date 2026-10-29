# PulseFeed RSS Reader PWA

PulseFeed is a lightweight, responsive RSS Reader built as a Progressive Web App (PWA). It runs directly in the browser and can be installed as an app on Android, iOS, or desktop.

## Features
- **Installable PWA**: Works like a native application with fullscreen experience.
- **Offline Mode**: Local article caching via `localStorage` and Service Worker.
- **Custom Subscriptions**: Add/delete RSS or Atom feeds organized by categories.
- **In-App Reader**: Article preview panel with clean HTML formatting.
- **Dark Mode & Search**: Full dark theme toggle and real-time article filtering.

## How to Upload to GitHub and Host for Free

### 1. Upload to GitHub
1. Create a new repository on [GitHub](https://github.com/new).
2. Save `index.html`, `manifest.json`, `sw.js`, and `README.md` into a single folder on your machine.
3. Push the files to GitHub using terminal or GitHub Desktop:

```bash
git init
git add .
git commit -m "Initial commit - PulseFeed PWA"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
git push -u origin main
```

### 2. Enable Free Hosting via GitHub Pages
1. Go to your repository on GitHub.
2. Click **Settings** > **Pages** (in the left sidebar).
3. Under **Build and deployment**, set **Source** to `Deploy from a branch`.
4. Choose `main` branch and `/ (root)` folder, then click **Save**.
5. Wait 1–2 minutes, and GitHub will give you a live URL (`https://YOUR_USERNAME.github.io/YOUR_REPO_NAME`).

### 3. Install on Android / Mobile
1. Open your GitHub Pages link in Chrome on your Android device.
2. Tap the browser menu (3 vertical dots) or look for the install icon in the top toolbar.
3. Select **"Add to Home Screen"** or **"Install App"**.