# therealmdwhite.github.io

The official hub site for **MD White** — entrepreneur, real estate investor, M&A/turnaround specialist, and bestselling author.

Live at **https://therealmdwhite.github.io**

## What it is

A single-file static site (`index.html`) that ties together everything:

- **The Vault** — all 22 Gumroad playbooks, toolkits & free lead magnets (prices + links pulled from the live catalog)
- **The Writing** — Substack, Medium, HackerNoon, Vocal Media, Blogger, Quora
- **Elsewhere** — LinkedIn, Reddit, and every other profile, one name: `therealmdwhite`
- **About** — the short bio

## Notes

- No build step, no dependencies — plain HTML/CSS/JS, served directly by GitHub Pages.
- Product list lives in the inline `PRODUCTS` array in `index.html` (generated from `~/workspace/mdwhite-hub/products.json`). To refresh prices/links, regenerate from the Gumroad catalog snapshot and re-upload.
- The LAUNCH30 sale banner shows automatically only while the sale is live (through Oct 26, 2026).
- Portrait is embedded as base64 — the whole site is one file.
