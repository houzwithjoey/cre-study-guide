# CRE Study Guide (web app)

Commercial real estate study guide: asset types and core concepts, with calculators and self-checks.

- Works offline after the first visit (service worker caches everything).
- On iPhone: open the site in Safari → Share → **Add to Home Screen**.
- The "Ask a question" feature only works inside Claude, so it's hidden in this version.

Files: `index.html` (the whole site), `sw.js` (offline cache), `manifest.webmanifest` + `icons/` (home-screen app), `fonts/` (bundled fonts, no external requests).
