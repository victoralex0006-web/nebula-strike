# Nebula Strike

A fast-paced 2D space shooter built with plain HTML5 Canvas and JavaScript — no dependencies, no build step. Just open the file (or play on GitHub Pages) and shoot.

![Game title: NEBULA STRIKE](https://img.shields.io/badge/status-arcade%20game-7b2ff7)

## Play

Open [index.html](./index.html) in any modern browser, or play it live on GitHub Pages once enabled.

## How to Play

- Move: `W` `A` `S` `D` or arrow keys
- Shoot: hold `Space`
- Pause: `P`
- Rename your pilot: `U`
- Restart: `R`

Chain kills to build a combo multiplier (up to x8). Grab power-ups to survive longer:

- **P** — cycles to the next of 6 weapons, each with its own color and feel:
  - **Blaster** (gold) — 3-way spread
  - **Scatter** (teal) — wide 7-way fan
  - **Plasma** (blue) — slow heavy shots, 3x damage, explode into shrapnel on impact
  - **Rapid** (orange) — very fast rate of fire
  - **Laser** (pink) — piercing beam, hits up to 4 targets
  - **Missile** (purple) — 2 homing missiles with splash damage
- **S** — shield that absorbs one hit
- **L** — extra life

A boss with three attack patterns arrives every 5 waves. Dodge asteroids, dodge bullets, and see how high you can climb the score. Scores are tracked on a local leaderboard — you get a pilot name automatically (edit it before launching or press `U` in-game), and the top 10 runs appear on the game-over screen.

## Features

- 6 distinct weapons with colored projectiles and muzzle flash
- Wave-based enemy spawning with 3 enemy types plus a multi-pattern boss
- Breakable asteroids that split into smaller ones
- Combo multiplier system
- Screen shake, particles, floating score popups
- Synthesized sound effects (Web Audio API, no assets)
- Persistent best score
- Local leaderboard (top 10) with auto-assigned, editable pilot names

## Files

- `index.html` — the entire game (single file, self-contained)
