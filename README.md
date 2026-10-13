# ASNA Consultancy — Website

Premium single-file website for **ASNA Consultancy** — business, tax & accounting
solutions (Islamabad, Pakistan). Cream, deep-navy and gold editorial design.

## What's inside

- `index.html` — the entire site: styles, markup and scripts in one file. No build step, no dependencies.
- Utility bar + sticky blurred nav with mobile menu
- Hero with SECP incorporation tracker card and animated counters
- Industries marquee, About + ASNA Advantage card
- 8 service cards (Business Registration, FBR & Tax, Accounting & Finance, Corporate Compliance, Startup Consulting, Automation, Software Solutions, Business Intelligence)
- 6-stage process timeline (dark), 12-question FAQ accordion
- Contact section: office, phone, WhatsApp (+92 327 508 4710), email (asnasconsultancy@gmail.com), business hours, and a validated consultation-request form
- Footer with quick links, core services and hours

## Preview locally

Just open `index.html` in a browser, or serve it:

```bash
python3 -m http.server 8080
# then open http://localhost:8080
```

## Deploy

Any static host works — GitHub Pages, Vercel, Netlify, or plain shared hosting.
Upload `index.html` as the repo root and you're live.

## Customise

- Brand colours live in the `:root` block at the top of the `<style>` section.
- Type: [Instrument Serif](https://fonts.google.com/specimen/Instrument+Serif) for display,
  [Inter](https://fonts.google.com/specimen/Inter) for body (Google Fonts, with system fallbacks).
- The logo and favicon are served from their hosted URLs (see `<head>` and the
  brand lockups in `index.html`).

## Note

The consultation form validates in the browser and shows a success message — wire the
`submit` handler to your backend, Formspree, or CRM endpoint to receive enquiries.

© 2026 ASNA Consultancy. All Rights Reserved.
