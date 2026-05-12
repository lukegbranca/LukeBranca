# LukeBranca Site

## Hosting
- Deployed via **Cloudflare Pages** (not Workers)
- Connected to the `main` branch of this GitHub repo
- Any push to `main` triggers an automatic deployment
- No build step — just static files (`index.html`, CSS, etc.)

## Important
- There is no `wrangler.json` or `wrangler.jsonc` file — it was deleted because it caused a conflict between Workers config (`assets`) and Pages config (`pages_build_output_dir`)
- Do NOT add a `wrangler.json` back unless it only contains Pages-compatible keys

## Making changes
- Edit files and push to `main` — Cloudflare Pages will pick it up automatically
- No special workarounds needed for deployment
