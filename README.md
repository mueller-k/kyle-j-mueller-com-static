# kylejmueller.com (static)

A dependency-free personal site for `kylejmueller.com`.

## Files

- `index.html`: Single-page business-card site.
- `styles.css`: Styling.
- `me.png`: Headshot.
- `favicon.svg`, `social-card.svg`: Lightweight identity assets.
- `wrangler.toml`: Cloudflare Workers Static Assets deployment config.

## Deploy

Deploy with Wrangler:

```sh
npx wrangler deploy
```

The Worker serves the repository root as static assets. `.assetsignore` keeps
deployment-only files from being published as public assets.
