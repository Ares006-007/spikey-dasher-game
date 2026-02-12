<img width="1001" height="545" alt="Screenshot 2026-02-12 161501" src="https://github.com/user-attachments/assets/a6fc05e5-9b5c-4c88-a79a-d7bb4571f578" />

# Spiky Dasher


## 🎮 Play Demo

[**Play Spikey Dasher**](https://ares006-007.github.io/spikey-dasher-game/)
Spiky Dasher is a fast-paced 2D browser platformer where you dash, double-jump, and wall-slide through spike-filled levels while racing against a timer and tracking your deaths.

## Overview

The game is built entirely with HTML, CSS, and vanilla JavaScript and runs directly in the browser. A tile-based level system, animated portals, and custom character sprites create a compact, console-like platforming experience.

## Gameplay

- Navigate through multiple levels using tight platformer controls and gravity-based movement.  
- Avoid lava spike tiles and other hazards, or you will instantly die and respawn at the level start while increasing your death counter.
- Reach the portal / next-level tiles to progress while the HUD tracks your total time and total deaths for the run.
## Controls

- Left arrow: Move left and wall-slide on left walls when airborne.
- Right arrow: Move right and wall-slide on right walls when airborne.
- Up arrow: Jump, with support for double jump when enabled in the logic

(You can adjust movement parameters and abilities such as gravity, horizontal speed, double jump, and dash in `script.js`.)

## Tech stack

- **HTML**: Base structure and game console container, including HUD elements like time and death counters.
- CSS: Layout, tiles, lava spikes, portals, character skins, and animations (blinking, portal pulsing, etc.).
- JavaScript: Game loop, tilemap generation, physics (gravity, velocity), collision detection, level transitions, and HUD updates.

## Getting started

1. Download or clone this repository into a local folder. 
2. Open `index.html` in any modern browser, or use a simple static server (like Live Server in VS Code) and visit the local URL.
3. Use the arrow keys to play and try to complete all levels with the fewest deaths and fastest time.

## Project structure

- `index.html` – Main HTML file; defines the `#game_console`, HUD counters, and script includes. 
- `style.css` – Styling for the console, tiles, spikes, portals, player sprites, and UI overlays.  
- `script.js` – Core logic: level data, game initialization, rendering, input handling, physics, collisions, and state management.

## Customization

- Edit the `levels` array in `script.js` to add or redesign levels by changing numeric tile maps and start coordinates. 
- Change CSS variables such as `--root-clr`, tile sizes, and player visuals in `style.css` to reskin the environment and characters.
- Tune gameplay feel by updating `gravity`, `x_speed`, tile dimensions, and ability flags (e.g., `dbljump`, `dash`) in `script.js`.

## Possible improvements

- Add WASD and mobile touch controls, plus on-screen buttons for phones and tablets.
- Implement audio (jump, death, portal, background music), a main menu, level selection, and a persistent best-time / least-deaths high-score system.



