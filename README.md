# Kyle Mueller Static Card

A dependency-free temporary personal site for `kylejmueller.com`.

## Files

- `index.html`: Single-page business-card site.
- `styles.css`: Responsive light/dark styling.
- `me.png`: Header portrait.
- `favicon.svg`, `social-card.svg`: Lightweight identity assets.

## Deploy

Deploy the repository root as static assets. There is no build command and no output
directory.

For Cloudflare Pages:

- Build command: leave blank.
- Build output directory: `/`.
- Production branch: `main`.

## Execution Plan Questions

- Which deployment path owns the temporary site: this static repo or the fuller Astro repo?
- Do DNS and Pages project settings already point `kylejmueller.com` at this repo?
- Should email remain the visible contact method, or should the page avoid public email?
- Do you want this to be the canonical live site until the real one ships, or a short-lived fallback?
