# tschnorpfeil.com

Personal website of Tobias Schnorpfeil — engineer & entrepreneur.
Live at [tschnorpfeil.com](https://tschnorpfeil.com/) (DE) and [tschnorpfeil.com/en/](https://tschnorpfeil.com/en/) (EN).

## Stack

- Static HTML/CSS/JS, no build step, no runtime dependencies
- Self-hosted Geist font family (GDPR-friendly, no CDN)
- Hosted on GitHub Pages with a custom domain

## SEO / GEO

- Bilingual via dedicated URLs (`/` DE, `/en/` EN) with `hreflang` + `x-default`
- Schema.org JSON-LD (`Person` + `WebSite` + `ProfilePage` graph) on both versions with bidirectional entity links (`sameAs`, `subjectOf`, `hasOccupation`)
- Open Graph, Twitter Cards, canonical URLs, sitemap with hreflang annotations
- `llms.txt` and `llms-full.txt` plus explicit AI search crawler permissions in `robots.txt`

