# ☄️ Asteroid Dodge

A browser-based spaceship dodge game built with **React 18** and **CSS animations** — no external animation libraries required.

## 🎮 How to Play

- **Move your mouse** (or drag your finger on mobile) to steer the ship
- **Dodge** falling asteroids to survive
- Each asteroid that safely passes below adds to your **score**
- Every 30 points you **level up** — asteroids fall faster and spawn more frequently
- You have **3 lives** — getting hit costs one life and destroys the asteroid
- **Game Over** when you run out of lives

## 🛠 Tech Stack

| Layer | Technology |
|-------|-----------|
| UI Framework | React 18 (via CDN) |
| Transpiler | Babel Standalone |
| Animations | Pure CSS `@keyframes` |
| Styling | CSS custom properties & flexbox |
| Ship movement | React `useState` + `requestAnimationFrame` |

## 🚀 Running

No build step needed. Just open `index.html` in any modern browser:

```bash
open index.html
```

Or serve it locally:

```bash
npx serve .
# or
python3 -m http.server 8080
```

## 📁 Project Structure

```
asteroid-dodge/
├── index.html    # Single-file game (React + CSS + game logic)
└── README.md     # This file
```

## 🎯 Game Features

- Smooth ship tracking via `requestAnimationFrame`
- CSS-animated asteroids with variable size, speed, and rotation
- Explosion effects on collision
- Twinkling star parallax background
- Mouse and touch input support
- Score, lives, and level HUD
- Progressive difficulty scaling

## 📄 License

MIT
