# GENEVIEVE Synchronicity — Tarot × Astrology

**Canonical Tarot repository for ON TRACK by TRACE / GENEVIEVE.**

This is the active source for the Synchronicity Tarot × Astrology concept. The application is a static single-page app and does not require a database.

## Canonical status

- Active application: `index.html`
- Source control: GitHub
- Deployment standard: Cloudflare Pages connected to this GitHub repository
- Database: none required; Neon is intentionally not used because this build has no persistent server-side data
- Legacy duplicate/reference: `tracey727/Synchronicity.1`
- Vercel / Netlify: not part of the active deployment standard

## Application

The app provides a three-card reflective Tarot spread linked to natal-chart themes. It contains a 78-card deck model and keeps the reading framed as reflective symbolism rather than certainty, diagnosis or professional advice.

## Cloudflare Pages deployment

Connect this repository to Cloudflare Pages.

- Production branch: `main`
- Framework preset: None
- Build command: leave empty
- Build output directory: `/` (repository root)

The site is static, so no build step or Neon connection is required.

## Repository files

- `index.html` — complete application
- `.github/workflows/ci.yml` — lightweight repository integrity checks
- `README.md` — canonical/deployment documentation

## Historical note

The earlier `Synchronicity.1` repository did not contain another working application. It preserved an external source-package link and is retained only as historical/reference evidence. Unique historical material is not deleted from Git history.
