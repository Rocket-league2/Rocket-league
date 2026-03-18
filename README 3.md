# 🚀 Rocket League 2D

A browser-based Rocket League clone — zero dependencies, single HTML file, runs anywhere.

🎮 **[Play it live on GitHub Pages](https://yourusername.github.io/rocket-league-2d)**  
*(replace with your actual URL after publishing)*

---

## Controls

| Key | Action |
|-----|--------|
| `A` / `D` or `←` / `→` | Drive |
| `Space` | Jump (press again mid-air = double jump / dodge) |
| `Shift` or `W` or `↑` | Boost |
| `R` | Reset ball & cars |

**Goal:** Hit the ball into the opponent's net. Blue attacks right, Orange attacks left. Most goals in 5 minutes wins!

### ⚡ Boost Pads
- **Centre pad** (large) — full boost, 10s cooldown
- **Side pads** (small) — 25 boost, 5s cooldown

---

## Features

- Arcade physics: gravity, bounce, air drag, ball spin
- Boost mechanic with exhaust flame
- Double jump & air dodge
- CPU opponent with AI
- Boost pad pickups with cooldowns
- Car-car collision with momentum transfer
- 5-minute match timer & live scoreboard
- Goal celebration flash
- Fully responsive (scales to any screen)

---

## Run locally

```bash
# Just open the file — no build needed
open index.html

# Or serve it (optional)
npx serve .
python3 -m http.server 8080
```

---

## 🌐 Publish to GitHub Pages (step by step)

1. **Create a new GitHub repository** (e.g. `rocket-league-2d`)
2. **Push the files:**
   ```bash
   git init
   git add index.html README.md
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/rocket-league-2d.git
   git push -u origin main
   ```
3. Go to your repo → **Settings** → **Pages**
4. Under *Source*, select **Deploy from a branch** → **main** → **/ (root)**
5. Click **Save** — your game will be live in ~1 minute at:
   `https://YOUR_USERNAME.github.io/rocket-league-2d`

---

## Extend it

- [ ] Two-player local co-op (second set of keys)
- [ ] Particle effects on goals and boosts
- [ ] Sound effects via Web Audio API
- [ ] Multiple arena themes
- [ ] Mobile touch controls
- [ ] Online multiplayer via WebSockets

---

## License

MIT
