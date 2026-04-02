My Day Lifestyle Planner PWA

What is included
- index.html
- manifest.webmanifest
- sw.js
- icons/

Important for iPhone
- iPhone cannot install a PWA from a local file (file://).
- For installability, the app must be served over HTTPS, or from localhost/127.0.0.1 in a development environment. See MDN for installability requirements. citeturn196168search0

Fastest way to test on a Mac
1. Unzip this folder on your Mac.
2. In Terminal:
   cd /path/to/myday-pwa
   python3 -m http.server 8000
3. Open Safari on your Mac at:
   http://localhost:8000
4. To open on your iPhone for viewing on the same Wi‑Fi:
   http://<your-mac-local-ip>:8000
   Note: for actual iPhone installation as a PWA, use an HTTPS host such as GitHub Pages, Netlify, or another HTTPS static host. citeturn196168search0turn196168search4

Install on iPhone from an HTTPS host
1. Upload the contents to an HTTPS static host.
2. Open the site in Safari on iPhone.
3. Tap Share.
4. Tap Add to Home Screen.

