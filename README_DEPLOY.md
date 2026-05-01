# Book Horror Site — upload/deploy notes

This archive is ready to upload to GitHub and deploy on Vercel.

## Important
Do not upload this ZIP file itself as the only file in GitHub. Extract the ZIP first, then upload the project contents: `app`, `src`, `public`, `docs`, `package.json`, `package-lock.json`, etc.

## Local commands
```bash
npm ci
npm run lint
npm run build
npm run dev
```

## Vercel
Framework: Next.js
Build command: `npm run build`
Install command: `npm ci`
Output directory: leave default

## Notes
- `node_modules` and `.next` are intentionally excluded.
- Google font network dependency was removed from `app/layout.tsx` so production builds are safer.
- The canon flow is preserved: interactive preloader → book → pages 1–40 with 100-page illusion → forced interruption → breaking scene → horror texts → game cards → mini-games → win/game over → corrupted home.
