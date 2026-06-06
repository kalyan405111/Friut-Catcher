# 🍎 Fruit Catcher

A fun and fast-paced browser game built with **Unity** and exported to **WebGL**. Catch falling fruits to score points — don't let them slip away!

---

## 🎮 Gameplay

- Fruits fall from the top of the screen
- Move your catcher/basket left and right to catch them
- Each caught fruit earns you points
- Miss too many and it's game over!

---

## 🚀 Play in Browser

Since this is a Unity WebGL build, you need a local HTTP server to run it (browsers block direct file access due to CORS).

### Option 1 — Python (recommended)

```bash
git clone https://github.com/kalyan405111/Friut-Catcher.git
cd Friut-Catcher/UpdateFruit/UpdateFruit
python3 -m http.server 8080
```

Then open your browser and go to: [http://localhost:8080](http://localhost:8080)

### Option 2 — Node.js

```bash
npx serve .
```

---

## 🌐 Host on GitHub Pages (Free)

You can share the game publicly using GitHub Pages:

1. Go to your repo → **Settings** → **Pages**
2. Set the source branch to `main`
3. Set the folder to `/UpdateFruit/UpdateFruit`
4. Click **Save**

Your game will be live at:
`https://kalyan405111.github.io/Friut-Catcher/`

---

## 🛠️ Tech Stack

| Property | Details |
|---|---|
| Engine | Unity (WebGL Export) |
| Runtime | WebAssembly (WASM) |
| Graphics API | WebGL 2.0 / WebGL 1.0 |
| Canvas Size | 960 × 600 px |
| Memory | 256 MB |

---

## 📁 Project Structure

```
Friut-Catcher/
└── UpdateFruit/UpdateFruit/
    ├── index.html                          # Game entry point
    ├── Build/
    │   ├── UnityLoader.js                  # Unity WebGL loader
    │   ├── UpdateFruit.json                # Game configuration
    │   ├── UpdateFruit.data.unityweb       # Compressed game assets
    │   ├── UpdateFruit.wasm.code.unityweb  # Game logic (WebAssembly)
    │   └── UpdateFruit.wasm.framework.unityweb  # Unity runtime
    └── TemplateData/
        ├── style.css                       # Loading screen styles
        ├── UnityProgress.js                # Loading bar script
        └── *.png / favicon.ico             # UI assets
```

---

## 📋 Requirements

- A modern browser with **WebGL support** (Chrome, Firefox, Edge, Safari)
- No installation needed — runs entirely in the browser

---

## 👤 Author

**Kalyan** — [GitHub Profile](https://github.com/kalyan405111)

---

## 📄 License

This project is open source. Feel free to fork and build upon it!
