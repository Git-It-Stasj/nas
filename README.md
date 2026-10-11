# Nastasja Terry — one-page site

Static site served by Cloudflare Workers (static assets). Everything lives in `public/`.

## Edit
- **Hero photo:** save as `public/images/hero.jpg`, uncomment the `<img>` in `public/index.html` and delete the placeholder text.
- **Placeholders to fill:** booking email (`mailto:booking@example.com`), LinkedIn URL, the `[00]` stats, and the talk titles (drafts).
- **Logo:** `public/images/architect-mark.svg` (nav + favicon). Gold-to-navy gradient stroke, top-left to bottom-right.
- `og:image` should become an absolute URL once there is a domain.

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
