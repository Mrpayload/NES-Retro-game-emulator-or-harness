# Retro Galaxy - Neon Arcade

Retro Galaxy is a single-file browser arcade built with plain HTML, CSS, and JavaScript. It includes multiple built-in retro mini-games plus NES ROM loading through a JSNES-based emulator.

## Features

- 7 built-in games: Neon Snake, Cosmic Pong, Galaxy Shooter, Astro Runner, Crystal Breakout, Rainbow Bird, and Alien Slingshot
- NES `.nes` ROM loader with keyboard and mobile touch controls
- Mobile-friendly layouts with customizable NES control options
- Fullscreen support
- Animated neon arcade UI with particles, galaxy mode, and visual effects
- Single static `index.html` file, ready for Vercel, Netlify, or GitHub Pages

## Controls

- `1-7`: Switch built-in games
- `P`: Pause
- `R`: Restart
- Arrow keys / WASD: Movement
- NES mode: `X` / `K` / `Space` = A, `Z` / `J` = B, `Enter` = Start, `Ctrl` / `Backspace` = Select

## Deploy To Vercel

This project is static and needs no build command.

1. Push `index.html` and `README.md` to a GitHub repository.
2. Import the repository in Vercel.
3. Leave the build command empty.
4. Use the project root as the output directory.

Vercel will serve `index.html` automatically.

## Notes

NES ROMs are loaded locally from the user's device and are not included in this repository. Only use ROM files you legally own or are permitted to use.
