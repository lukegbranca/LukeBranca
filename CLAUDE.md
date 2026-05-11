# Claude Instructions

## Cloudflare Pages Setup
Every new website project must include a `wrangler.jsonc` file in the root with the following structure:

```json
{
  "name": "project-name",
  "compatibility_date": "2026-05-11",
  "assets": {
    "directory": "./"
  },
  "pages_build_output_dir": "./"
}
```

- Replace `project-name` with the repo/project name in lowercase
- Always include this file when creating or setting up a new site
- Always push `wrangler.jsonc` to `main`

## Git
- Development branches follow the format `claude/description-xxxxx`
- Always push changes and confirm they are live on the remote before finishing
