GOF Fleet Tank Sounding Calculator v8

GitHub Pages / Android / iPhone PWA package.

Files:
- index.html — calculator application and embedded fleet calibration data
- manifest.webmanifest — PWA installation settings
- sw.js — offline service worker/cache
- icon-192.png — app icon
- icon-512.png — app icon

Deployment:
1. Upload ALL files to the GitHub repository root.
2. GitHub Pages: Settings > Pages > Deploy from branch > main > / (root).
3. Open the GitHub Pages URL in Safari on iPhone or Chrome on Android.
4. Add to Home Screen / Install.
5. After the first successful load, the service worker caches the app for offline use.

Do not open index.html directly from the phone Files app if you want PWA/offline installation.
