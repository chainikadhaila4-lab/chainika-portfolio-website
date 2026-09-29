# chainika.in

Static site — no build step.

## Files
- index.html — desktop site (phones auto-redirect to mobile.html)
- mobile.html — mobile site (desktops auto-redirect back)
- support.js — page runtime (keep it)
- images/ — your photos. See images/README.md for filenames.

## Cloudflare Pages
1. Push this folder to a GitHub repo.
2. Cloudflare → Workers & Pages → Create → Pages → Connect to Git.
3. Framework preset: None. Build command: empty. Output directory: /
4. Add your custom domain under Custom domains.

To add or change a photo: drop the file into images/, commit, push. Cloudflare redeploys automatically.
