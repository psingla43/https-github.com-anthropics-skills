# Uncontested & Amicable Divorce — Landing Page

A single-file, self-contained landing page for an Ontario family law practice
(`amicable-combined.html`). No build step, no dependencies — open it in a browser
or drop it onto any host.

## Design intent

Built to read as an established Ontario firm, not a template or an "AI/SaaS" site:

- **Palette** — warm ivory paper, deep ink-navy, one muted brass accent. No violet
  gradients, no neon, no glassmorphism.
- **Type** — classic serif headings (Palatino/Iowan family) paired with a Helvetica
  body; a print-derived, editorial pairing that uses only system fonts (fast, no
  external requests).
- **Structure** — semantic HTML, one `<h1>`, landmark regions, accessible form
  labels, visible keyboard focus, native `<details>` FAQ (no JavaScript), a mobile
  disclosure menu, and reduced-motion support.
- **Copy & compliance** — calm family-law tone; visible "general information / not
  legal advice" and "no solicitor-client relationship" disclaimers; no guarantees,
  testimonials, superlatives, or manufactured urgency.

## Before you publish — fill these placeholders

Search the HTML for the bracketed tokens and replace them:

- `[firm phone number]` / `[Firm phone number]` and the `tel:+10000000000` links
- `[Street address]`, `[City]`, `[Postal code]`, `[Office hours]` in the footer
- The consultation `<form action="#">` — point it at your form handler or email endpoint
- Privacy / Accessibility / Terms footer links (currently `#`)
- Confirm the firm name/wordmark ("Singla Law") and the email
  `singlalawoffice@gmail.com` are correct

The email address is used as-is; everything in `[brackets]` is a placeholder.

## A note on legal content

The procedural descriptions are written in general terms for Ontario. A licensee
should review all legal content for accuracy and currency before it is published,
and confirm the firm name, credentials, and jurisdiction statements are correct.
