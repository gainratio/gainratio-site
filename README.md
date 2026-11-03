# gainratio.com

Source of the live `gainratio.com` one-page site, preserved after the 2026-10-25
edit that added the `open-source.gainratio.com` link.

The Cloudflare Pages project (`gainratio`) is **direct-upload only** — it has no
Git connection — so this folder is the deployable source of truth:

```sh
npx wrangler pages deploy . --project-name=gainratio --branch=main
```

Files:

- `index.html` — the page, including the hero “Open source” button and footer link
- `robots.txt`, `sitemap.xml`
- `_headers` — `X-Frame-Options`, `X-Content-Type-Options`
- the two mark PNGs

Preview before promoting:

```sh
npx wrangler pages deploy . --project-name=gainratio --branch=preview
```
