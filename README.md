# chainika.in

Static site — no build step.

## Cloudflare Pages
1. Push this folder to a GitHub repo.
2. Cloudflare dashboard → Workers & Pages → Create → Pages → Connect to Git.
3. Framework preset: None. Build command: (leave empty). Output directory: `/` (or this folder's path).
4. Deploy, then add your custom domain (chainika.in) under Custom domains.

Or drag this folder into Pages → "Upload assets".

## Files
- index.html — the site
- support.js — page runtime
- image-slot.js — photo component
- portrait.webp — your portrait
