# ASNA Consultancy — Financial Advisory Landing Page

A premium, single-file landing page for **ASNA Consultancy** (Perth · Sydney · Remote).
Cream, deep-navy and gold editorial design — serif display type, animated portfolio dashboard,
scroll-reveal sections, and a validated discovery-request form.

## What's inside

- `index.html` — the entire site: styles, markup and scripts in one file. No build step, no dependencies.
- Utility bar + sticky blurred nav with mobile menu
- Hero with animated "Live Portfolio Model" dashboard (chart bars rise on scroll)
- Scrolling credentials marquee
- Services grid (6 advisory lines), dark "How We Work" timeline, About, testimonials,
  contact section with booking slots + discovery form, full footer with compliance note
- Count-up hero stats, reveal-on-scroll animations, inline form validation with success state

## Preview locally

Just open `index.html` in a browser, or serve it:

```bash
cd financial-consultancy-landing
python3 -m http.server 8080
# then open http://localhost:8080
```

## Deploy

Any static host works — GitHub Pages, Vercel, Netlify, or plain shared hosting.
Upload `index.html` (optionally as the repo root) and you're live.

## Customise

- Brand colours live in the `:root` block at the top of the `<style>` section
  (`--navy`, `--gold`, `--gold-2`, `--bg`).
- Type: [Instrument Serif](https://fonts.google.com/specimen/Instrument+Serif) for display,
  [Inter](https://fonts.google.com/specimen/Inter) for body (Google Fonts, with system fallbacks).

## Note

The discovery form validates in the browser and shows a success message — wire the
`submit` handler to your backend, Formspree, or CRM endpoint to receive enquiries.

The logo and favicon are served from their hosted URLs (see `<head>` and the
brand lockups in `index.html`).

© 2026 ASNA Consultancy.
