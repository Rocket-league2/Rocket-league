# 🚀 Rocket League 2D

A browser-based Rocket League clone built with vanilla HTML5 Canvas and JavaScript — no dependencies, no build step. Just open `index.html` and play!

![Rocket League 2D](https://img.shields.io/badge/game-HTML5%20Canvas-blue) ![License](https://img.shields.io/badge/license-MIT-green)

## 🎮 How to Play

| Key | Action |
|-----|--------|
| `A` / `D` (or `←` / `→`) | Drive left / right |
| `Space` | Jump (press again in air = double jump / dodge) |
| `Shift` / `W` / `↑` | Boost |
| `R` | Respawn (reset cars + ball) |

**Objective:** Hit the ball into the opponent's goal. Blue team shoots right, Orange team shoots left. Most goals after 5 minutes wins!

### ⚡ Boost Pads
- Collect glowing yellow pads on the field to refill your boost.
- Large centre pad gives full boost; side pads give 25%.

## 🕹️ Features

- Real arcade physics (gravity, bounce, spin, air drag)
- Boost mechanic with flame effect
- Double jump / air dodge
- CPU opponent with basic AI
- Boost pad pickups with cooldowns
- 5-minute match timer
- Goal flash & celebration text
- Car-car collision
- Responsive scoreboard & HUD

## 🚀 Running the Game

```bash
# Option 1: Just open the file
open index.html

# Option 2: Serve locally (avoids any browser quirks)
npx serve .
# or
python3 -m http.server 8080
```

Then visit `http://localhost:8080` in your browser.

## 🌐 Publishing via GitHub Pages

1. Create a new GitHub repo
2. Push `index.html` and `README.md`
3. Go to **Settings → Pages → Source → main branch / root**
4. Your game will be live at `https://yourusername.github.io/your-repo-name`

## 🛠️ Project Structure

```
/
├── index.html   ← entire game (self-contained, no dependencies)
└── README.md
```

## 🧩 Extending the Game

Ideas for future improvements:

- [ ] Multiplayer (WebSockets or WebRTC)
- [ ] Better CPU AI with pathfinding
- [ ] Particle effects for goals and boosts
- [ ] Power-ups / arena hazards
- [ ] Multiple arenas / backgrounds
- [ ] Mobile touch controls
- [ ] Sound effects & music

## 📄 License

MIT — free to use, modify, and distribute.
