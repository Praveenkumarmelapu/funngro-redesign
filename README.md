# Funngro Website Revamp - Redesign Concept

Two-page redesign of [funngro.com](https://www.funngro.com/) built as the Funngro Website Revamp assignment:

- `index.html` - **Teen page** (redesign of the earn/teen-facing page): earn money online with real brand work, UPI payouts.
- `company.html` - **Company page** (redesign of the for-brands/company-facing page): youth marketing campaigns for brands.

## Stack

Plain HTML5 + CSS3 + vanilla JavaScript. No build step, no dependencies - deployable as a static site anywhere (Vercel, Netlify, GitHub Pages).

## SEO implementation

- Unique title + meta description per page, canonical URLs, Open Graph + Twitter cards
- JSON-LD structured data: `Organization`, `FAQPage` (Teen), `Service` (Company)
- Semantic HTML5 landmarks (`header/main/section/footer`), one `h1` per page, descriptive `alt`/`aria-label` text
- `robots.txt` + `sitemap.xml`, `lang="en-IN"`, mobile viewport, fast static delivery

## Local preview

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

Concept by M. Praveen Kumar - built with AI assistance. Not the official Funngro website.
