# MPSC PYQ Free — mobile-first starter

This is a free, mobile-friendly PWA prototype.

## Included
- Student login screen (demo only; local browser storage)
- Sample Marathi MCQs with four options and explanations
- Subject filter and search
- Bookmarks
- Admin Demo panel to add questions on the current device
- PWA manifest and service worker for installable web-app behavior

## Important limitations
- The included questions are illustrative samples, not verified official MPSC PYQs.
- Login is NOT secure authentication. A demo PIN in front-end code is not secure.
- Data is stored only in the current browser/device; it is NOT shared with other students.
- The real 2,100-question bank is not included.
- No real admin permissions or server/database has been configured.
- This project has no payment/subscription feature.
- Before use by real students, connect secure authentication and a shared database (e.g. Firebase) and enforce admin permissions with security rules/server-side checks.

## Publish a free web/PWA demo on GitHub Pages
1. Upload `index.html`, `manifest.json`, `sw.js`, and `README.md` to the root of a GitHub repository.
2. Repository Settings → Pages.
3. Set Source to "Deploy from a branch", Branch `main`, Folder `/ (root)`, then Save.
4. Open the URL shown after publication. On Android Chrome, use the browser menu and choose "Add to Home screen" / "Install app" if offered.

GitHub Pages can host the PWA website. Publishing a native app on Google Play is a separate process and may have fees/requirements.
