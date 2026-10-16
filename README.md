# Morrowmade

A self-contained, responsive agency/studio site for Morrowmade. Built with semantic HTML, CSS and vanilla JavaScript; no framework or build step is required.

## Features

- Editorial brand system: ink, warm paper, and acid-lime accents
- Responsive navigation with a mobile menu
- Scroll progress indicator, staggered reveal motion and animated marquee
- Three portfolio previews linking to Happy Cleaning, Joana's Cleaning and Yosef Cleaning Solutions
- Service list, working-process section and project CTA
- Reduced-motion support, semantic landmarks, focus styles and image lazy loading
- Custom SVG favicon, search description, and Open Graph basics

## Run locally

Open `index.html` in a browser, or serve the folder with any static server. For example:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Before launch

1. Replace `hello@morrowmade.com` in the contact link in `index.html` with the confirmed business email address.
2. Confirm that the three portfolio destination URLs are the preferred public links. The mockup cards are art-directed previews; their links open each referenced site.
3. Add a canonical URL and sitemap once the production domain is confirmed.
4. Test the published site on real mobile devices, check that all external destinations work, and review any chosen imagery/licensing for commercial use.

## Deployment

This is a static site and can be deployed directly with Vercel, Netlify, GitHub Pages, or any static web host. No environment variables are required.
