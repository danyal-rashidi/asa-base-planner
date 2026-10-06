# ASA Base Planner

A browser-based 3D planner for designing bases in **ARK: Survival Ascended**. Players build a base on a grid, then export it as **Template Hammer** code they can paste into the game, so they can plan and test a design before spending materials in-game.

**Live site:** https://asa-base-planner.netlify.app

> Status: in active development. The planner is designed for desktop (mouse and keyboard); phones show a notice recommending a computer.

## Features

- **3D and top-down plan views** with free camera, fit view, and a walk mode to look around the base at player height; metal pieces reflect the sky, edges are bevelled and shadows are soft
- **Piece library** grouped into categories: structure, doors, defense, utility, stone, Tek, farming, pillars and railings, and custom pieces
- **Snapping options** that follow ARK's building rules (on top of walls, sideways on walls, full / half / quarter squares, or free placement)
- **Tower generator** and **turret wall generator** for building common PvP layouts in a few clicks
- **Turret coverage view** to check defensive coverage before placing
- **Editing tools:** rotate, mirror, copy, repeat up, turret fill, and keyboard shortcuts for faster building
- **Box select:** in Select mode, click and drag a box round any part of the build (or all of it) to select everything inside, on every floor that's showing
- **Controls you can change:** every shortcut key can be rebound (handy on AZERTY keyboards), plus camera, zoom and walk-look speed and mouse invert, saved in the browser
- **Contact form:** messages go to the site's Netlify Forms page (turn on form detection and an email notification in Netlify to get them in your inbox)
- **Template import and export:** copy the finished design as Template Hammer code, or import a template and drop it onto what you've already built; imported pieces keep their paint, skins and mod paths
- **Move and copy parts:** pick up a selection (or the whole build), turn or mirror it while holding it, and drop it anywhere; copy the Template Hammer code for just the selected part
- **Pieces list:** totals for every piece against the turret cap and the 2,000-piece template limit; click a row to select those pieces
- **Hover tips:** hover a tool for a one-line "what to do" and a short looping clip of it (can be switched off in Controls)
- **First-time tour:** a short spotlight tour of the planner on the first visit, which can be taken again from the Guide
- **Illustrated guide** with pictures and clips of each tool
- **Example designs** for PvP (core cage tower, turret spire, cage tower) and PvE to start from

## Built with

- JavaScript
- [three.js](https://threejs.org/) for 3D rendering
- HTML and CSS
- Hosted on **Netlify**, with automatic deployment from this repository's `main` branch

## Running it locally

No build step is needed. Download or clone the repository and open `index.html` in a modern browser:

```bash
git clone https://github.com/danyal-rashidi/asa-base-planner.git
```

## Contact

Questions or suggestions: asabaseplanner@gmail.com

## Disclaimer

This is an independent fan-made tool. It is not affiliated with or endorsed by the developers or publishers of ARK: Survival Ascended.

---

Created by **Danyal Rashidi**, Engineering Science student at Simon Fraser University.
