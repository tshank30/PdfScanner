# PaperVault website

A responsive, buildless product website for the PaperVault PDF app.

## Preview locally

From this directory run `python3 -m http.server 8080 --directory dist`, then open http://localhost:8080.

## Contents

- `dist/index.html`: product page
- `dist/style.css`: responsive styles
- `dist/app.js`: accessible toolkit tabs
- `dist/privacy.html`: privacy policy from `../docs/privacy-policy.md`
- `dist/assets/`: original app logo and product screenshots

The App Store download buttons link to the PaperVault listing. Google Fonts is used for typography, with local system fallbacks.

## Google indexing

The static site includes canonical URLs, search/social metadata, SoftwareApplication structured data, `dist/robots.txt`, and `dist/sitemap.xml`. After deploying changes, add `https://tshank30.github.io/PdfScanner/` as a URL-prefix property in [Google Search Console](https://search.google.com/search-console), verify ownership, and submit `https://tshank30.github.io/PdfScanner/sitemap.xml`. You can then use URL Inspection to request indexing of the homepage. Google decides when and whether to index pages; submission does not guarantee inclusion.
