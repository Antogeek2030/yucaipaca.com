# Plumbing Repair Yucaipa CA

Professional plumbing repair, drain cleaning, water heater service, and emergency plumbing website built with Astro and deployed on Cloudflare Pages / Workers.

**Live site:** https://plumbingrepairyucaipaca.com

## Features

- Fully responsive, mobile-friendly design
- Service pages: Plumbing Repair, Drain Cleaning, Water Heater, Emergency Plumbing, Fixture Installation
- Service Areas page with embedded Google Map
- Contact page with form and map pinpointing 33520 Liberty Rd, Yucaipa, CA 92399
- SEO-ready (sitemap, robots.txt, meta tags, canonical URLs)
- Cloudflare adapter for Pages / Workers deployment
- Updated teal color scheme

## Commands

| Command | Action |
| --- | --- |
| `npm install` | Install dependencies |
| `npm run dev` | Start local dev server |
| `npm run build` | Build production site to `./dist/` |
| `npm run deploy` | Deploy to Cloudflare |
| `npm run preview` | Preview production build locally |

## Deploy to Cloudflare Pages

1. Connect the repository to Cloudflare Pages (or use Wrangler).
2. **Build command:** `npm run build`
3. **Build output directory:** `dist`
4. Framework preset: Astro (or None).

Alternatively with Wrangler:

```bash
npm run build
npm run deploy
```

## Customize

- Update phone, email, and address in `src/consts.ts`
- Replace Formspree form ID in `src/pages/contact.astro` with your own endpoint
- Colors and styling are in `src/styles/global.css`

## Location

33520 Liberty Rd  
Yucaipa, CA 92399  
USA
