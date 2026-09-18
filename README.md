# Recruit — marketing site

Single static page selling the Recruit platform (the app lives in `../recruit`).

- `index.html` — the whole site: copy, styles, interactions. No build step.
- `vercel.json` — clean URLs and security headers.

## Run locally

Open `index.html` in a browser, or serve the folder with any static server.

## Deploy

Pushes to `main` deploy through Vercel (project linked with `vercel link`).
Manual: `npx vercel --prod --yes`.

## Placeholders to replace before launch

- Pricing numbers ($49 / $89 / Custom) are placeholders.
- The testimonial is illustrative, not a named customer.
- The demo form opens a `mailto:`; swap for a form endpoint when one exists.
- "Sign in" links to the live app at recruit-two-pi.vercel.app.
