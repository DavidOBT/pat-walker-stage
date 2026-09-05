# Pat Walker stage model — OBT Nutcracker 2026

A working 3D model of the hang at Pat Walker Theater, Springdale, for The Nutcracker, December 18–20, 2026.
Open it here, no account needed: **https://davidobt.github.io/pat-walker-stage/**

- `index.html` — the model (single file, three.js). Cues, trims, drag pieces between pipes, sightline audit.
- `data/project.json` — the **shared state** everyone sees when they open the page. Change this file to change the model for everyone.
- `docs/the-moving-room.html` — set direction and the Gladsbuy cut plan.
- `docs/moving-room-templates.html` — piece geometry and the template kit (`docs/nutcracker-set-templates.zip`).

## Editing
1. Open the page, make your changes in the model.
2. Click **Download project.json** (say what changed).
3. Either commit it over `data/project.json` (write access, or a pull request from a fork), or attach it to an issue.

## Requesting a change
Click **Request a change** on the page, or open an issue here. Screenshots welcome.

## Local copy
The page works from a local file too, but the shared state only loads when served over http (Pages, or any local server).
