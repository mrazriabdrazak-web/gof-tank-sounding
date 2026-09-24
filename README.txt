GOF Fleet Tank Sounding Calculator v8.2.2

GitHub Pages / Android / iPhone installable web app (PWA).

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
4. On Android, use the browser menu's Install app / Add to Home screen command. On iPhone, use Safari's Share > Add to Home Screen.
5. Open the installed app once while online. The service worker then caches the calculator for offline use.

This creates installable home-screen apps. It does not create Google Play or Apple App Store listings.

Do not open index.html directly from the phone Files app if you want PWA/offline installation.

v8.2.1 fixes: Tank rows display fuel tanks first in number order, followed by fresh-water tanks in number order, then other liquids and void/reference tanks. Sorting keeps original calibration indexes stable for saved readings. Dolphin Satu's trim control now activates from its vessel data and applies the tank-specific correction tables already embedded in the app. Setia Deras and Dolphin Satu show percent-full values calculated from calibrated capacity where their source tables omit percentages.
v8.2.2: Added Android/iPhone home-screen install metadata and registered the offline service worker. Cache cleanup is limited to this app so it does not delete another GitHub Pages app's cache.
