# n1.care marketing website

Production-oriented marketing site for [n1.care](https://n1.care), based on the **Smoked Birch / Copper Patina** art direction.

This repository holds the static marketing redesign (HTML/CSS/JS + assets). It is not yet wired to production DNS.

## Local preview

From the repository root:

```bash
python3 -m http.server 8080
```

Then open http://localhost:8080/

Alternatively:

```bash
npx serve .
```

## Pages

| Page | File |
|------|------|
| Home | `index.html` |
| Product | `product.html` |
| Clinicians | `clinicians.html` |
| Patients | `patients.html` |
| Labs | `labs.html` |
| Reports | `reports.html` |
| Compliance | `compliance.html` |
| Pricing | `pricing.html` |
| About | `about.html` |
| Contact | `contact.html` |
| Case studies | `case-studies.html` |

Sample report demos linked from the home page: `Health_summary_demo-1.html`, `LHR_demo-1.html`, `Supplement_demo-_1_-1.html`.

## Shared styles & scripts

- `brand-tokens.css`, `art-directions.css`, `buttons.css`, `marketing-pages.css`
- `marketing-pages.js`, `contact-form.js`
- `assets/` (logos, photography, fonts, hero videos)
- `.nojekyll` (safe for GitHub Pages)

## Source

Seeded from the public design preview (`JasperNoBoxDev/preview`, gh-pages, Smoked Birch / Copper Patina homepage). Palette experiments (`index-NN-*`, `crimson-*`, `palette-gallery.html`) were intentionally omitted.
