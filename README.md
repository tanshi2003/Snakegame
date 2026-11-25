# Snake Game

A classic Snake game built with Python and Pygame, now with a browser-playable edition so people can play without installing Python or PyCharm.

## Play online

**Browser version:** https://tanshi2003.github.io/Snakegame/

Open the link on desktop or mobile. No installation is required.

## Browser game controls

- **Move:** Arrow keys or W, A, S, D.
- **Mobile:** Use the on-screen directional pad.
- **Pause / resume:** Space bar or the Pause button.
- **Restart:** Restart button.
- **Goal:** Eat the glowing fruit, gain 10 points per fruit, and avoid hitting the walls or your own tail.

### Browser game options

- Easy, Normal, and Fast starting speeds.
- Optional wall wrapping.
- Toggle the grid and simple sound effects.
- Personal best saved in your browser using local storage.

Scores are stored locally in the browser and are not shared across devices.

## Run the original Python desktop version

The original Pygame edition is still included in this repository.

1. Install Python 3.
2. Clone or download this repository.
3. Open a terminal in the project folder.
4. Install the dependency:

   ```bash
   python -m pip install -r requirements.txt
   ```

5. Run:

   ```bash
   python Snake.py
   ```

Keep the `Screen/` and `Music/` folders alongside `Snake.py`. The desktop version loads its images and music from those folders.

### Windows executable

The packaged Windows executable is retained in the repository at `dist/Snake.exe`. Download it from the repository if you prefer the desktop build. Only run executables you trust.

## Technologies

- Python + Pygame (desktop edition)
- HTML, CSS, and JavaScript (browser edition)

## GitHub Pages

The browser edition is published from the `web/` folder using GitHub Actions. Every push to `main` that changes the web game or deployment workflow triggers a deployment.
