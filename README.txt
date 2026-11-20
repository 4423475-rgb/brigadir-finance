FINORA V4.8 — BRAND UPDATE

Upload/replace these files in the root of your GitHub Pages repository:
- index.html
- sw.js
- manifest.webmanifest
- icon.svg
- icon-192.png
- icon-512.png

Keep your existing user data. The internal storage keys and legacy backup identifier are intentionally preserved for compatibility.
After committing, reopen the installed PWA. If the old name/icon remains, close the app fully and open the site once in the browser to let the service worker update, then install/open again.
