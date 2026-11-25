# THERMEX V2 — Deployable static web app
Extract this folder and open `index.html` in a modern browser.

## Deploy
**Netlify:** Add new site → Deploy manually → drag this folder.
**Vercel:** Import as a static project; no build command, output directory `.`.

## Features
- Editable thermal, geometry, and fluid inputs.
- Preliminary LMTD sizing and tube-side / simplified Kern-style shell-side pressure-drop screening.
- Parametric conceptual 2D longitudinal section, 2D end view, and 3D isometric SVG diagrams.
- Export current drawing as SVG; export results as CSV; print / save PDF.

## Engineering limitations
Prototype only. Diagrams are illustrative and not coordinate-accurate fabrication drawings. Shell-side pressure drop is not Bell–Delaware. No iterative thermal rating, TEMA/ASME mechanical design, vibration analysis, tubesheet design, nozzle reinforcement, or code compliance is implemented. Validate independently; do not use for procurement, fabrication, safety decisions, or guarantees.
