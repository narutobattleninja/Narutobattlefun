# Shinobi Clash

### 🥷 A browser-based 3D ninja battle arena — punch, kick, and jutsu your way through waves of rivals

*Built with plain HTML, CSS, and Three.js — no build step, no dependencies to install*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)
[![Made with Three.js](https://img.shields.io/badge/Made%20with-Three.js-black.svg?style=for-the-badge&logo=three.js)](https://threejs.org/)
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-orange.svg?style=for-the-badge)](CONTRIBUTING.md)

[▶️ Play Now](#-quick-start) · [🐛 Report Bug](../../issues/new?template=bug_report.md) · [💡 Request Feature](../../issues/new?template=feature_request.md)

---

## 📌 About

**Shinobi Clash** is a mobile-friendly, third-person ninja brawler that runs entirely in the browser. Explore an open arena, punch and kick rival shinobi, unleash a chakra-charged Ougi finisher, collect crystals, level up, and unlock new weapons — all rendered live in 3D with Three.js, with zero build tools required.

### ✨ Features

| Feature | Description |
|---|---|
| 🕹️ **Touch + drag controls** | On-screen joystick for movement, drag-to-orbit camera, tap buttons for attack/skill/dodge |
| 🎯 **Auto-lock combat** | Attacks and jutsu auto-aim at the nearest enemy in range so you never whiff on mobile |
| 🔥 **Flying-ember projectiles** | Layered, flickering fireball projectiles with a trailing ember particle effect |
| 🤺 **Turn-based enemy attacks** | Enemies queue up and attack one at a time instead of swarming the player |
| 🎥 **Dynamic chase camera** | Camera smoothly follows the hero's facing direction at all times |
| 🌀 **Chakra Ougi ultimate** | Charge a Rasengan-style orb and unleash an area-of-effect burst |
| 🛒 **Weapon shop & progression** | Earn crystals, level up, unlock and equip new weapons |
| 🏆 **Achievements & leaderboard** | Local achievement tracking and a persistent leaderboard |
| 💾 **Save / load** | Progress is saved locally in the browser — no account needed |

---

## 🚀 Quick Start

### Option 1 — Play Online (Recommended)

If this repo has GitHub Pages enabled, just open:

👉 **`https://<your-username>.github.io/shinobi-clash/`**

### Option 2 — Run Locally

No build step, no dependencies — just open the file.

```bash
# Clone the repository
git clone https://github.com/<your-username>/shinobi-clash.git
cd shinobi-clash

# Open directly in your browser
open index.html      # macOS
start index.html      # Windows
xdg-open index.html   # Linux
```

Or serve it locally (recommended for the best experience):

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

---

## 🎮 Controls

| Action | Control |
|---|---|
| Move | On-screen joystick |
| Attack (punch/kick) | JUTSU button |
| Skill / Ougi | Skill button (charges as you fight) |
| Dodge | Dodge button |
| Jump | Jump button |
| Camera orbit | Drag anywhere on screen |

---

## 🛠️ Tech Stack

- **Three.js** — 3D rendering, lighting, and scene management
- **Vanilla JavaScript** — game loop, AI, physics, and UI logic
- **HTML/CSS** — UI, HUD, and menus
- **`localStorage`** — save data, achievements, leaderboard, and settings

No package manager, no bundler, no build step — everything lives in a single `index.html`.

---

## 🤝 Contributing

Contributions, bug reports, and feature ideas are all welcome!

1. **Fork** this repository
2. **Create** your branch: `git checkout -b feat/your-feature`
3. **Commit**: `git commit -m 'feat: add your feature'`
4. **Push**: `git push origin feat/your-feature`
5. **Open a Pull Request**

See [CONTRIBUTING.md](CONTRIBUTING.md) for more details.

---

## 📄 License

Licensed under the [MIT License](LICENSE) — free to use, modify, and share.

---

**⭐ If you enjoy Shinobi Clash, consider starring the repo!**
