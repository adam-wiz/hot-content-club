# Hot Content Club

Waitlist landing page for Hot Content Club — Angelina Balandina's private consulting group.

**Live:** https://hotcontentclub.com

## Tech

Single-file static HTML. No build step. Deployed via Vercel.

## Edit

`index.html` is self-contained — Tailwind-free, vanilla CSS, Google Fonts CDN, vanilla JS form handler.

To preview locally:

```bash
python3 -m http.server 4174
# Open http://localhost:4174
```

## Open items before driving traffic

- Wire `<form action="">` to ConvertKit / Mailchimp / Formspree (currently captures zero emails — JS shows success state only)
- Add Meta Pixel + GA4 IDs in the commented placeholders at the bottom of `<head>`

## Authoring

Working copy lives in the DWY vault at `Clients/Angelina-Balandina/landing-page/`. Source of truth for design specs is `Clients/Angelina-Balandina/page-foundation.md`.
