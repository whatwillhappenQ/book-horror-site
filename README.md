# ШОВ / SEAM — v1.1

Interactive engraved art adventure for iPhone Safari. This branch is isolated from the unrelated `main` project.

## Current gameplay
A tactile paper tear reveals a stitched impossible city; three ring interactions collapse the skyline into the ocean. Holding the ocean's red knot reveals a creature, after which the scene becomes a zero-gravity room with a draggable mechanical moon. A personalized collectible imprint records both the red thread's path and the moon's actual trajectory.

## Deployment
The root `index.html` embeds three visual assets; `manifest.webmanifest`, `icon-192.png`, `icon-512.png`, and `sw.js` implement standalone PWA support. Service worker cache version is `shov-v11`. HTTPS hosting is required for installable PWA behavior.

**This GitHub branch is not confirmation of a live website.** Updating the existing ChatGPT Sites URL requires an actual Sites deployment operation. See `SITES_HANDOFF.md`.

## QA
Automated full path on Chromium 390×844 passed without JS errors, including downloadable 900×1600 PNG. iPhone Safari and offline install are not yet verified; local HTTP tests were blocked by the test environment.

The remainder of chapters IV–VI and the real story ending are not yet implemented.
