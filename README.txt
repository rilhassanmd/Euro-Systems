EURO SYSTEMS — DAILY SITE SCHEDULE PWA PACKAGE

Files:
- index.html: current schedule HTML, including centered logo and no logo animation
- manifest.webmanifest: installable app metadata
- sw.js: app-shell caching for faster/reliable reopening; it does NOT make cloud sync work offline
- icons/: app icons

IMPORTANT
This package is prepared for deployment, but it is not yet published online. For installation on Android/iPhone, host the folder on an HTTPS website. A simple route is GitHub Pages. Upload all files/folders in this package to the root of a GitHub repository, enable Settings > Pages > Deploy from a branch > main > /(root), and wait for the published HTTPS address. Then open that address on the phone and use Chrome > menu > Install app / Add to Home screen (Android), or Safari > Share > Add to Home Screen (iPhone).

CLOUD / DATA
The app still relies on the existing app's cloud configuration and browser storage. Test login, cloud sync, schedule saving and logo settings after publishing. Do not delete the old HTML or browser data until you've confirmed everything works. Service-worker caching does not guarantee offline database access.
