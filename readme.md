# Steel Challenge Classifier (PWA)

Enter **final stage times** (after the match drops the slowest string).  
Each division keeps its own times. Classification % and class update live. Works offline once installed.

## Setup

1. Generate icons: open `generate-icons.html` in a browser → download `icon-192.png` and `icon-512.png` into this folder.
2. Push all files to a public GitHub repo (root or `/docs`).
3. **Settings → Pages → Source:** Deploy from branch → `main` → root.
4. Open: `https://YOUR_USERNAME.github.io/REPO_NAME/`

## Install

- Chrome / Edge: install icon in the address bar  
- Android: menu → Install app  
- iOS Safari: Share → Add to Home Screen  

## After you push updates

In the installed app, tap **Hard refresh**. That clears the offline cache and reloads so you get the new code. Your stage times stay on the device.

## Files

| File | Role |
|------|------|
| `index.html` | App |
| `manifest.webmanifest` | Install metadata |
| `sw.js` | Offline cache |
| `icon.svg` | Vector icon |
| `icon-192.png` / `icon-512.png` | PWA icons |
| `generate-icons.html` | One-time icon helper |

Times stay in your browser only (`localStorage`), per division.
