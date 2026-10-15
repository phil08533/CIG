# CIG — Zero District

A browser-based, first-person cyberpunk street exploration prototype built with Three.js.

## Play it

Open the repository's GitHub Pages deployment if enabled, or serve the repository locally:

```bash
python -m http.server 8000
```

Then visit http://localhost:8000. The prototype imports Three.js from jsDelivr, so an internet connection is required.

## Included

- First-person movement and mouse look
- Mobile touch movement pad and drag-to-look controls
- Neon-lit cyberpunk street with procedural buildings, glowing signs, overhead walkways, cables, hover traffic, barriers, and low-poly NPCs
- Rain streaks, fog, colored lighting, wet pavement accents, and retro scanline overlay
- First-person sidearm model and HUD with health, armor, ammunition, and minimap
- Objective progression: find Moth, hack the street terminal, recover the memory shard
- Interactions using E, F, I, M, and R
- Responsive start screen and HUD
- No build step, backend, or external assets required beyond the Three.js CDN

## Controls

- **W / A / S / D** — Move
- **Mouse** — Look around; click the scene to recapture mouse control
- **E** — Talk to the contact
- **F** — Hack the street terminal
- **I** — View inventory summary
- **M** — Map information
- **R** — Reload sidearm
- **Esc** — Release mouse capture
- **Mobile** — Direction pad to move, drag the right side of the scene to look, use Talk/Hack/Reload buttons

## Notes

This is a playable visual prototype, not a finished shooter. The weapon and HUD are visual, and the contact/hacking interactions advance a short objective sequence. Combat, enemy AI, full collision geometry, persistent saves, and a full quest system are future expansion points.
