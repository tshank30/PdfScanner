---
name: papervault-blog-writing
description: Write or revise an original PaperVault PDF guide for this static HTML site. Use for blog posts, how-to articles, outlines, and editorial updates.
---

# PaperVault blog writing

Write for people trying to finish a real document task. Start with a direct answer, then give ordered, actionable steps, common mistakes, and a concise takeaway. Use plain, specific language and a helpful, privacy-conscious voice.

## Before drafting

- Read `docs/content-skills.md`, the App Store listing, the privacy policy, and existing relevant blog pages.
- Decide what the page uniquely answers and avoid repeating another guide's intent.
- Gather trustworthy sources for material claims. Cite sources next to the claims they support; never invent citations or attribute a claim to a source that does not support it.
- If an app interaction is not shown in the source material, describe the feature without fabricating button names or exact screen sequences.

## Product accuracy

- PaperVault features and compatibility must match its current App Store listing.
- Privacy statements must match the published privacy policy; distinguish on-device app processing from any file provider a reader chooses.
- Do not claim every PDF is searchable, every signature is legally sufficient, compression is lossless, passwords can be recovered, or metadata removal redacts visible content.
- Treat product availability, pricing, OS compatibility, and third-party integrations as changeable; verify them at publication time.

## Static page requirements

- Add a unique title, meta description, canonical URL, Open Graph basics, one H1, and readable section headings.
- Use semantic HTML, accessible links, descriptive image alt text, and links to related PaperVault guides.
- Add appropriate `BlogPosting` JSON-LD only when its visible page data is accurate.
- Include a source list with working links. Do not include decorative or unsupported citations.
- Add the page to `dist/blog/index.html` and `dist/sitemap.xml`; check canonical URLs use the GitHub Pages project path.
- Link to the App Store only where it genuinely helps the reader.
