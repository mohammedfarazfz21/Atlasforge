# ⚡ AtlasForge — Cloud Engineering Platform

> **A browser-based parametric CAD, physics simulation, robotics, and AI-assisted engineering platform — all in a single HTML file.**

![Version](https://img.shields.io/badge/version-v0.1.0--alpha-6366f1?style=flat-square)
![Built With](https://img.shields.io/badge/built%20with-Three.js%20%7C%20WebGL%202.0-06b6d4?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-22c55e?style=flat-square)

---

## 🌐 Live Demo

> **Test it instantly — no install needed:**
>
> 👉 **[Open AtlasForge Live](https://YOUR-USERNAME.github.io/AtlasForge/atlasforge.html)**

_(Replace `YOUR-USERNAME` with your GitHub username after enabling GitHub Pages — see [Deploy](#-deploy-on-github-pages) below)_

---

## ✨ Features

| Module | Description |
|---|---|
| 🧊 **CAD Design** | Parametric modeling with Sketch, Extrude, Revolve, Sweep, Loft, Fillet, Boolean ops, Mirror, Pattern |
| 🔗 **Assembly** | Hierarchical joint system — Revolute, Slider, Ball, Cylindrical joints with mass properties |
| ⚙️ **Physics Simulation** | Real-time physics with Bullet/PhysX/MuJoCo solvers, gravity environments (Earth, Moon, Mars), force & torque application |
| 🤖 **Robotics** | URDF/SDF import, FK/IK solvers, PID controllers, trajectory planning, sensor suite (Camera, LiDAR, IMU, GPS) |
| 📖 **Education Mode** | Interactive kinematics, dynamics, and control theory modules with step-by-step solvers |
| 🤖 **AI Copilot** | Built-in AI assistant for modeling suggestions, PID tuning, singularity detection, and optimization |
| 👥 **Collaboration** | Workspace sharing modal with team invite system |
| 🎨 **3D Viewport** | Three.js-powered 3D view with orbit controls, wireframe, top/front/right views, grid toggle, ACES filmic tone mapping |

---

## 🖥️ Screenshots

_Animated 3D robot arm visible immediately on launch._

- **CAD Mode** — Feature tree, extrude parameters, material properties
- **Simulate Mode** — Physics debug panel with energy stats
- **Robotics Mode** — PID tuning, end-effector position, sensor feeds
- **Education Mode** — Live FK/IK sliders with mathematical equations

---

## 🚀 Run Locally

### Option 1 — Python Server (Recommended)
```bash
# Clone the repo
git clone https://github.com/YOUR-USERNAME/AtlasForge.git
cd AtlasForge

# Start the server (auto-opens browser)
python server.py
```
Then open: **http://localhost:3000/atlasforge.html**

### Option 2 — Direct File
Just double-click `atlasforge.html` — it works as a standalone file too!

---

## 🌍 Deploy on GitHub Pages

To get a **public URL** for your visitors:

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set source to **`main` branch / root (`/`)**
4. Your live URL will be:
   ```
   https://YOUR-USERNAME.github.io/AtlasForge/atlasforge.html
   ```

---

## 🛠️ Tech Stack

- **Three.js r128** — 3D rendering engine (WebGL 2.0)
- **Vanilla HTML/CSS/JS** — Zero dependencies, zero build tools
- **ACES Filmic Tone Mapping** — Cinematic rendering quality
- **PCF Soft Shadow Maps** — Realistic shadows
- **Python `http.server`** — Lightweight local dev server

---

## 📁 Project Structure

```
AtlasForge/
├── atlasforge.html   # Entire application (CAD + Sim + Robotics + AI)
└── server.py         # Local development server (Python)
```

---

## 🤝 Contributing

Pull requests are welcome! Feel free to open issues for feature requests or bugs.

---

## 📜 License

MIT License — free to use, modify, and distribute.

---

> Built with ❤️ using Three.js and vanilla web technologies.
