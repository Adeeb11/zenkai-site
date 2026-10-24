# ZENKAI Web

The marketing and product-preview website for ZENKAI — the low-code application
platform. A single, self-contained `index.html` (no build step): HTML, CSS and
vanilla JS in one file, with Three.js and Google Fonts loaded from their CDNs.

## Pages

Public: Home, About, Features, Plans, Contact, Login/Register.
Product preview: Customer Dashboard, ZENKAI Studio, Application Editor,
Admin Dashboard, Notifications Center. Navigation is client-side via `#` routes.

## Highlights

- Brand palette and typography (forest green, neon lime, charcoal), light + dark.
- Fully responsive down to phone width.
- Animated Three.js backdrop — runs on marketing pages, freezes on app pages,
  theme-aware (light backdrop in light mode), respects `prefers-reduced-motion`.
- "Zen" mascot that peeks from the logo, lands, follows the cursor, and explains
  elements tagged with `data-bot-help="..."`. Click it to mute.

## Run locally

It's static — just open `index.html`, or serve the folder:

```bash
npx serve zenkai-web
# or
python3 -m http.server --directory zenkai-web 8080
```

## Notes

This is a design/preview build: the contact form and auth are front-end previews
(not wired to a backend), dashboards show example data, and the founder/team
section uses clearly-labelled sample content.
