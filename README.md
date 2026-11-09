# ШОВ / SEAM — v0.9
Interactive art adventure designed for iPhone Safari and standalone installation.

This isolated deployment branch is NOT the original project's main branch.
The game is currently a polished **vertical slice**: paper tear, stitched city, folding horizon and a responsive etched ocean with a creature encounter. The complete six-chapter story is still in development.

## How to host
Serve this directory over HTTPS. `index.html` contains the complete illustration assets and interactive logic; `manifest.webmanifest`, `icon-*.png` and `sw.js` enable installation and offline support.
`sw.js` uses network-first navigation so updates don't stay stale.

## QA
The test workflow checks JS syntax and bundled images. Full automated Chromium gameplay and PNG export passed locally on the 390×844 mobile viewport; this does not substitute for real iPhone Safari QA.

## v0.9
Hand-drawn ring seal animation, additional city light planes, safe PWA update prompt, improved visibility-state cleanup, and progress migration from previous builds.
