# ehmtoi.com

Personal portfolio of Mohit Eedupuganti, Supply Chain Management at Rutgers Business School.

Live at [ehmtoi.com](https://ehmtoi.com).

## About

A single-page, editorial-style portfolio built with plain HTML, CSS and JavaScript. No frameworks or build step.

- Glass panels over a scroll-driven color field
- Light and dark mode, remembered per visitor
- Pinned Experience section that turns pages as you scroll
- Sideways-scrolling Lookbook of projects
- Navigation guide pop-up on load
- Stacked layout on phones and for reduced-motion users

## Run locally

Open `public/index.html` in any browser.

## Deploy

Hosted on Cloudflare Workers as static assets. `wrangler.jsonc` points Cloudflare at the `public` folder, and every push to `main` redeploys the site automatically.
