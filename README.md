# Dr. Kirthi George — digital card

Single-page digital business card, served by GitHub Pages. No build step:
everything is in `index.html`, plus self-hosted fonts and a vCard.

## Deploy
Settings → Pages → Source: *Deploy from a branch* → `main` / `(root)`.
`.nojekyll` makes Pages serve the files as-is.

## Editing details
Phone, email and WhatsApp number appear in `index.html` **and** `kirthi-george.vcf`.
Update both.

## Fonts
`fonts/` holds Latin-only subsets of Fraunces (400, upright + italic) and
Hanken Grotesk (400–600), cut down from Google Fonts with fontTools so the
page makes no third-party requests. Any basic Latin text renders; characters
outside that range fall back to Georgia / system sans.
