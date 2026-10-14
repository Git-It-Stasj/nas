# Nastasja Terry — one-page site

Static site served by Cloudflare Workers (static assets). Everything lives in `public/`.

## Edit
- **Hero photo:** `public/images/hero.jpg` (square LinkedIn photo, cropped to 4:5 by CSS).
- **Placeholders:** none left.
- **Logo:** `public/images/architect-mark.svg` (nav + favicon). Gold-to-navy gradient stroke, top-left to bottom-right.
- `og:image` uses the absolute URL https://www.nastasjaterry.com/images/hero.jpg.

## Nutrition page (/nutrition)
- Lives in `public/nutrition/index.html`; Cloudflare serves it at https://www.nastasjaterry.com/nutrition.
- Same Architect fonts and logo as the home page, wellness palette (sage/forest + clay). Light by default; the theme toggle shares the `nt-theme` key with the home page.
- **Before publishing:** swap the `Start Begin 30` links (search `REPLACE`) for your Begin 30 / IBO link, add the real price and star rating only if you have them, and have the copy and the disclosure line checked against Amway's Rules of Conduct.

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
