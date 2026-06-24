# onsiteai.network

Static marketing site for **Onsite AI** — sovereign, on-premises AI infrastructure.

Single-file site (`index.html`) with embedded CSS + vanilla JS. No build step.

## Develop

```bash
python3 -m http.server 8000
# visit http://localhost:8000
```

## Deploy

GitHub Pages — push to `main`. `CNAME` points the site at onsiteai.network.

## Theme

Amber → copper accents on warm carbon (`--accent: #ffb020`, `--accent-2: #ff7849`),
defined as CSS variables at the top of `index.html`.

## Deployment

Optionally through cloudflare
