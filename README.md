# Nastasja Terry — one-page site

Static site served by Cloudflare Workers (static assets). Everything lives in `public/`.

## Edit
- **Hero photo:** `public/images/hero.jpg` (square LinkedIn photo, cropped to 4:5 by CSS).
- **Placeholders:** none left.
- **Logo:** `public/images/architect-mark.svg` (nav + favicon). Gold-to-navy gradient stroke, top-left to bottom-right.
- `og:image` uses the absolute URL https://www.nastasjaterry.com/images/hero.jpg.

## Preview locally
```
npx wrangler dev
```

## Deploy (Cloudflare dashboard)
1. Workers & Pages → Create application → Import a repository.
2. Pick the GitHub account and this repo.
3. Project name `nastasja-terry`, build command empty, deploy command `npx wrangler deploy`.
4. Save and Deploy.

Or from the terminal: `npx wrangler deploy`.
