# The Working Margin — v0.2

Personal writing site for Bagus Bachtiar.

## Writing system

Articles live in `src/content/writing/` as Markdown files. Each article has frontmatter for title, description, date, category, featured and draft. The homepage, archive and category pages update automatically when a new Markdown file is added.

Categories:
- Energy & Climate
- Impact
- Personal Development
- Essays & Ideas

## Cloudflare

The site is statically generated into `dist/` and deployed using Cloudflare Workers Static Assets via `wrangler.jsonc`.

## Local development

```bash
npm install
npm run dev
```
