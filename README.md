# O Max Media — Website

Official website for **O Max Media** — personal branding, social media management and growth studio (Hyderabad & Proddatur).

## Stack
- Single static `index.html` (no build step)
- GSAP + ScrollTrigger (animations), Lenis (smooth scroll) via CDN
- Google Fonts: Inter Tight, Instrument Serif
- Images in `assets/`

## Run locally
Open `index.html` in a browser, or:
```bash
npx serve .
```

## Deploy
Import this repo in Vercel (Framework preset: **Other**, no build command, output dir `.`). Every push to `main` auto-deploys.

## Editing
- Brands (marquee + Selected Work): `brands` array in the script at the bottom of `index.html`
- Services / FAQs: `svcs` and `faqs` arrays
- Logos & creatives: replace files in `assets/` (keep the same names)
