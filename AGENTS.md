# Project Instructions

## Things that have broken before

- TypeScript builds failed after renaming JSX entry files → `index.html` still pointed at `src/main.jsx` and CSS imports had no Vite type shim → update the HTML entry and keep `src/vite-env.d.ts` when converting Vite React apps to TypeScript.
