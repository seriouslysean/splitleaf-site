# AGENTS.md

Static Astro site for splitleaf.net, deployed to GitHub Pages.

- Install: `npm ci` (Node version in `.nvmrc`). Copy `.env.example` to `.env` for the `PUBLIC_*` values.
- Gate before a PR: `npm run lint && npm run format:check && npm run check && npm run build`, the same checks as `.github/workflows/ci.yml`.
- Where things live: `src/pages/` pages, `src/styles/` styles, `public/` static files (including `CNAME`).
