# 🧠 MindForge

> A personal mind map & planning canvas. Works on phone and PC. No installs. No accounts. Just your thoughts, organised.

![MindForge](https://img.shields.io/badge/PWA-installable-6d4aff?style=flat-square&logo=pwa)
![HTML](https://img.shields.io/badge/built%20with-HTML%20%2B%20Canvas-3b9eff?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-2ec99a?style=flat-square)

---

## ✨ What it does

MindForge is a lightweight mind map builder I built for myself to plan projects, roadmaps, and ideas visually. It runs entirely in the browser — no backend, no database, no framework. Pure HTML, CSS, and Canvas API.

You can:
- Drop nodes anywhere on an infinite canvas
- Connect them with dashed curved arrows
- Colour-code by category
- Rename, duplicate, delete nodes
- Drag everything around freely
- Zoom and pan the canvas
- Install it on your phone like a native app (PWA)
- Use it completely offline

---

## 📸 Preview

```
[Mindset] -----> [Be a problem solver] -----> [Resolve a pain]
                                         -----> [Save them time]
                                         -----> [Make them money]

[Goals]   -----> [SLC > MVP]

[Build]   -----> [Learn a stack]
```

---

## 🚀 Live Demo

👉 **(https://imforge.github.io/node-map---mind-map/)**

---

## 📱 Install as an App

**Android (Chrome):**
1. Open the live link in Chrome
2. Tap the install banner at the bottom → **Add to Home Screen**

**iOS (Safari):**
1. Open the live link in Safari
2. Tap the **Share** button
3. Tap **Add to Home Screen**

Once installed it opens fullscreen, works offline, and lives on your home screen like any other app.

---

## 🛠 Tech Stack

| Thing | What |
|---|---|
| UI | Plain HTML + CSS |
| Drawing | HTML5 Canvas API |
| Storage | localStorage (auto-saves everything) |
| Offline | Service Worker (cache-first) |
| Fonts | Google Fonts — Caveat (handwritten feel) |
| Hosting | GitHub Pages |
| Framework | None |

Zero dependencies. Zero npm. Zero build step. Just open the file.

---

## 📁 File Structure

```
mindforge/
├── index.html      # The entire app — all logic lives here
├── manifest.json   # PWA config (name, icons, theme colour)
├── sw.js           # Service worker — makes it work offline
├── icon-192.png    # App icon (Android home screen)
├── icon-512.png    # App icon (splash screen)
└── README.md       # You're reading this
```

---

## 🎮 Controls

### Mouse / Trackpad
| Action | How |
|---|---|
| Add node | Switch to Node mode → click canvas |
| Connect nodes | Switch to Connect mode → click node A → click node B |
| Move node | Select mode → drag |
| Pan canvas | Drag empty space (or Space + drag) |
| Zoom | Scroll wheel |
| Rename node | Double-click |
| Context menu | Right-click a node |
| Delete | Select → Delete key |
| Undo | Ctrl + Z |
| Fit all | F key |

### Mobile / Touch
| Action | How |
|---|---|
| Pan | Drag empty space |
| Zoom | Pinch two fingers |
| Context menu | Long press a node |
| Everything else | Tap the toolbar buttons |

### Keyboard Shortcuts
| Key | Action |
|---|---|
| `V` | Select mode |
| `N` | Node mode |
| `C` | Connect mode |
| `F` | Fit view |
| `Del` | Delete selected |
| `Ctrl+Z` | Undo |
| `Esc` | Cancel / deselect |

---

## ⚙️ Run Locally

No build step needed — just open the file:

```bash
# Clone the repo
git clone https://github.com/ImForge/node-map---mind-map
cd mindforge

# Option 1: open directly
open index.html

# Option 2: use VS Code Live Server
# Install "Live Server" extension → right-click index.html → Open with Live Server
```

> ⚠️ The service worker only activates when served over HTTP/HTTPS.
> For offline testing, use Live Server — don't just double-click the file.

---

## 🔧 Deploying to GitHub Pages

```bash
git init
git add .
git commit -m "initial commit"
git remote add origin https://github.com/YOUR_USERNAME/mindforge.git
git branch -M main
git push -u origin main
```

Then:
1. Go to your repo on GitHub
2. `Settings → Pages`
3. Source: `main` branch, `/ (root)`
4. Save

Your app is live at `https://YOUR_USERNAME.github.io/mindforge` in about 60 seconds.

---

## 🗺 Roadmap

- [ ] Export canvas as JSON (share your map)
- [ ] Import JSON to restore a map
- [ ] Multiple canvases / pages
- [ ] Node images / emoji support
- [ ] Collaborative editing (WebSockets)
- [ ] Custom node shapes
(THE UPDATED VERSION COMMING SOON)
---

## 👤 Built by

**Forge** — CS student, builder, tinkerer.

---

## 📄 License

MIT — do whatever you want with it.
