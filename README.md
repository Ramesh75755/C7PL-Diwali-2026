# C7PL Diwali Utsav 2026 — Premium Edition

A responsive, mobile-first Diwali celebration website.

## Files
- `index.html`
- `style.css`
- `app.js`

## Run in Termux
```bash
pkg update -y
pkg install python unzip -y
cd ~/storage/downloads
unzip -o C7PL-Diwali-Utsav-2026-Premium.zip
cd C7PL-Diwali-Utsav-2026-Premium
python -m http.server 8080
```
Open `http://127.0.0.1:8080` in Chrome.

## Publish on GitHub Pages
Upload the three website files (`index.html`, `style.css`, `app.js`) to the repository root. In Settings → Pages, select Deploy from a branch, branch `main`, folder `/ (root)`, then Save.

## Notes
- Team names are editable in the browser and saved with localStorage on that device only. A Firebase database is needed for a roster shared across visitors.
- The countdown targets 8 November 2026 at 6:00 PM India time. Edit `target` in `app.js` to change it.
- Sound is a small synthesized chime and starts only after tapping Sound on.
- Google Fonts load when internet is available; fallback fonts are used otherwise.
