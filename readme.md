# Steel Challenge Classifier (PWA)

Enter your **final stage times** (after the match drops the slowest string).  
Each division keeps its own times. Classification % and class update live. Works offline once installed.

## Deploy to GitHub Pages

1. Create a new repo and push these files to the root (or `/docs`).
2. **Settings → Pages → Source:** Deploy from branch → `main` / root.
3. Open `https://YOUR_USERNAME.github.io/REPO_NAME/`

Must be served over **HTTPS** (GitHub Pages does this) for the service worker and install prompt.

## Install as app

- **Chrome / Edge (desktop):** address bar → install icon, or menu → “Install Steel Challenge Classifier”
- **Android Chrome:** menu → “Install app” / “Add to Home screen”
- **iOS Safari:** Share → “Add to Home Screen”

## Files

| File | Role |
|------|------|
| `index.html` | App UI + logic |
| `manifest.webmanifest` | Install metadata |
| `sw.js` | Offline cache |
| `icon.svg` | App icon |

Times are stored only in your browser (`localStorage`), per division. Nothing is sent to a server.

Peak times are from SCSA (scsa.org). This is an unofficial helper.
