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
- Late-PS1 low-resolution rendering, chunkier silhouettes, higher-contrast blue, teal, amber, and crimson color accents, fog, rain, scanlines, and drifting smoke
- Mobile touch controls: on-screen movement pad, drag-to-look, Interact, and Match buttons
- Low-poly character models for Iris Vance, Clara Vance's eerie silhouette, and the masked Basin Watcher
- Expanded dialogue, the missing-person case, the Deep Well clue, the dead engineer Elias Rook, radio dispatch, and the Warehouse 19 lead
- A correctly oriented cigarette with a glowing tip and smoke wisps that rise from the lit cigarette
- Desk-lamp interaction, photograph inspection, and chapter-ending story beat
- Responsive start screen and HUD

This is still an in-progress prototype. The story now reaches the Warehouse 19 lead, but the warehouse/tunnel chapter, full character animation, voice acting, and a complete multi-level campaign remain future work.

## Controls

- **W / A / S / D** — Move (or use the on-screen directional pad on mobile)
- **Touchscreen** — Drag the right side of the scene to look; use Interact and Match buttons
- **Mouse** — Look around (click the game to recapture the pointer)
- **E** — Interact / inspect
- **F** — Light or extinguish the cigarette; watch the smoke rise from the glowing tip
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
