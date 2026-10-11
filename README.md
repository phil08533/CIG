# CIG — Ash & Embers

A browser-based, Three.js first-person noir horror prototype inspired by the **Ash & Embers** story and storyboard.

## Play the prototype

Open `index.html` through a local web server or deploy the repository with GitHub Pages. The page imports Three.js as an ES module from jsDelivr, so it needs an internet connection.

For local testing, from the project directory run:

```bash
python -m http.server 8000
```

Then open http://localhost:8000.

## Current prototype

- First-person camera and mouse look
- WASD movement in a low-poly detective's office
- Retro noir lighting, rain, fog, scanline treatment, and environmental props
- Interactions for the office door and photograph
- Opening dialogue from the story
- A cigarette/match toggle with a small light and synthesized match sound
- Responsive start screen and HUD

This is an early greybox/atmosphere pass, not the finished game. The character model, full Iris animation, detailed inspection UI, robust smoke mechanic, and later scenes are not implemented yet.

## Controls

- **W / A / S / D** — Move
- **Mouse** — Look around (click the game to recapture the pointer)
- **E** — Interact / inspect
- **F** — Light or extinguish the cigarette ember
- **Enter** — Continue dialogue
- **Esc** — Release mouse capture

## End credits

Keep contributor and asset attribution in [`CREDITS.md`](CREDITS.md). Portal Music is listed there as a potential music source; we will fill in the specific track and verify its attribution requirements when you choose one.

## Direction

The production target is a deliberately low-poly, late-PS1-inspired first-person detective horror game: oppressive spaces, sparse combat, tactile clue inspection, cigarette/smoke as a focus mechanic, and choices with consequences.

The story document supplied for the project is titled **Ash & Embers — Complete Story Script & Storyboard**. CIG is the working project/repository name.

## Technical notes

- Plain HTML + JavaScript ES modules + Three.js
- No build step and no backend
- Three.js is loaded from a CDN
- Local browser storage and cloud services are not required for this prototype
