GOF Fleet Tank Sounding Calculator v8.2.1

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

v8.2.1 fixes: Tank rows display fuel tanks first in number order, followed by fresh-water tanks in number order, then other liquids and void/reference tanks. Sorting keeps original calibration indexes stable for saved readings. Dolphin Satu's trim control now activates from its vessel data and applies the tank-specific correction tables already embedded in the app. Setia Deras and Dolphin Satu show percent-full values calculated from calibrated capacity where their source tables omit percentages.
