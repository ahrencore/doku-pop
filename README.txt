DOKUPOP — iPhone Home Screen package

1. On GitHub, open your dokupop repository and upload ALL SIX files from this folder into the repository root:
   index.html, manifest.webmanifest, service-worker.js, apple-touch-icon.png, icon-192.png, icon-512.png
2. GitHub repository Settings > Pages > Deploy from a branch > main / (root) > Save.
3. Wait until the website is published. Open https://YOUR-USERNAME.github.io/dokupop/ in iPhone Safari.
4. Tap Share > Add to Home Screen. Turn on Open as Web App if offered, and choose Add.
5. Your approved pink cupcake icon should appear on the iPhone Home Screen. Tap it to play Dokupop.

Notes:
- GitHub Pages on a free personal account generally needs a public repository. Anything included in public website files can be retrieved by others.
- This game saves progress in browser/device local storage. Don't erase website data or assume it syncs across devices. Installing under a different domain may not carry over previous data.
- When updating the game, replace index.html in this package with an updated version that keeps the metadata, and update the service worker cache version so offline players receive updates.
