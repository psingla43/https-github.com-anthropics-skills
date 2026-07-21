# Singla Law — Ontario Family Law Site

A small, self-contained website for an Ontario family law practice. No build
step, no frameworks, no external requests — just static files you can drop onto
any host (or open directly in a browser).

## Files

| File | Purpose |
|---|---|
| `index.html` | Homepage — firm overview, practice areas, approach, **lawyer bio**, consultation |
| `amicable-combined.html` | Uncontested / amicable divorce page |
| `separation-agreement.html` | Separation agreements page |
| `styles.css` | Shared design system used by all three pages |

All pages share one header, footer, and stylesheet, and link to each other.

## Design intent

Built to read as an established Ontario firm, not a template or an "AI/SaaS" site:

- **Palette** — warm ivory paper, deep ink-navy, one muted brass accent. No violet
  gradients, no neon, no glassmorphism.
- **Type** — classic serif headings (Palatino/Iowan family) paired with a Helvetica
  body; a print-derived, editorial pairing that uses only system fonts (fast, no
  external font loading).
- **Structure** — semantic HTML, one `<h1>` per page, landmark regions, accessible
  form labels, visible keyboard focus, native `<details>` FAQ (no JavaScript), a
  mobile disclosure menu, and reduced-motion support.
- **Copy & compliance** — calm family-law tone; visible "general information / not
  legal advice" and "no solicitor-client relationship" disclaimers; no guarantees,
  testimonials, superlatives, or manufactured urgency.

## Before you publish — fill these placeholders

Search the files for the bracketed tokens and replace them:

- **Lawyer bio** in `index.html` — `[Lawyer name]`, `[Title]`, the two `[…]`
  paragraphs, the credential list, and add a professional portrait where the
  `.portrait` placeholder sits.
- **Contact** (all pages, footer + consultation) — `[Firm phone number]` and the
  `tel:+10000000000` links, `[Street address]`, `[City]`, `[Postal code]`,
  `[Office hours]`.
- **Consultation form** — each `<form action="#">` needs to point at your form
  handler or email endpoint before it will send.
- **Footer links** — Privacy / Accessibility / Terms currently point to `#`.
- Confirm the firm name/wordmark ("Singla Law") and the email
  `singlalawoffice@gmail.com` are correct.

## A note on legal content

The procedural descriptions are written in general terms for Ontario. A licensee
should review all legal content for accuracy and currency before it is published,
and confirm the firm name, credentials, and jurisdiction statements are correct.
Under Law Society of Ontario rules, credentials must be accurate and current, and
"specialist" may be used only by lawyers certified through the LSO's program.
