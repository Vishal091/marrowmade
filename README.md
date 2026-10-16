# Marrowmade

A premium, responsive website for an independent digital studio focused on service businesses. Built as a static HTML/CSS/JavaScript site with no framework or build step.

## Experience

- High-contrast art direction: midnight ink, warm paper, electric blue, and signal orange
- Clear service-business positioning and action-led hero
- Live-site portfolio previews for Happy Cleaning, Joana's Cleaning, and Yosef Cleaning Solutions
- Responsive navigation, scroll progress, reveal transitions, animated service ribbon, and reduced-motion support
- Project enquiry form that prepares an email draft in the visitor's default email application
- Custom favicon, Open Graph image, canonical link, robots.txt, sitemap, and privacy page

## Run locally

Open `index.html` in a browser, or start a static server:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Required before public outreach

1. **Confirm the enquiry inbox.** The form currently uses `hello@marrowmade.com` as a placeholder recipient. Replace it in the script inside `index.html` with an email address that exists and is monitored.
2. **Verify the brand/domain spelling.** This repository and Vercel URL use `marrowmade`. Keep the wordmark, email, project domain, social handles and future custom domain consistent. Check availability before buying a custom domain or trademarking the name.
3. **Review the portfolio destinations.** The site links to the public destinations listed in `index.html`. Confirm each is the intended showcase link. Joana's Cleaning links to the current public business site; if a separate redesign preview is available, replace the link and corresponding screenshot source with that verified preview.
4. **Review screenshot-provider dependence.** Website preview images are fetched from Thum.io at runtime so they reflect public live sites. Its free service may be rate-limited and is not under this repository's control. For a more reliable production portfolio, capture approved screenshots and commit optimized local WebP files to this repo.
5. Test the deployed site on desktop and mobile, test the form with the confirmed recipient, and verify the final deployment URL.

## Privacy

The project form is not submitted to a server. After required fields validate, it opens an email draft with the visitor's entries, which are only sent if that visitor chooses to send the message. Embedded Google Fonts and website preview images are requested from their respective providers; see `privacy.html`.

## Deploy

This is a static site and can be deployed with Vercel, Netlify, GitHub Pages, or another static host. No environment variables are required.
