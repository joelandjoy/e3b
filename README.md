# Decoding Universe — Episode 3: Gluons

**Start with `START-HERE.txt`.** This folder is ready to upload to the root of a GitHub repository and deploy on Vercel.

## Files

- `index.html`: website entry point
- `src/main.jsx`: React entry point (must remain at this exact path)
- `src/App.jsx`: player, chapter navigation, and export interface
- `src/renderer.js`: silent procedural animation renderer
- `src/episode.js`: 17 chapter timings
- `src/styles.css`: website styling
- `package.json`, `vite.config.js`, `vercel.json`: build and deployment configuration

## Vercel settings

- Framework: Vite
- Root Directory: `./`
- Install Command: `npm install`
- Build Command: `npm run build`
- Output Directory: `dist`

No environment variables are required. The site is client-rendered and records its silent animation locally in the visitor's browser. See `START-HERE.txt` for the simplest upload steps and export limitations.
