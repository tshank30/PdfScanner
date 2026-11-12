---
name: papervault-seo-review
description: Review PaperVault static pages and blog posts for search crawlability, on-page metadata, canonical URLs, internal links, and sitemap coverage.
---

# PaperVault SEO review

Review the rendered HTML and deployed static-file paths; do not infer indexability from a title tag alone.

## Checks

- The page is public, returns a successful response, and is not blocked from crawling or indexing.
- There is one descriptive title, useful meta description, one clear H1, and a canonical URL matching the page's actual GitHub Pages path.
- Article content is present in HTML without requiring JavaScript. Headings are semantic and links are crawlable anchors.
- Article or SoftwareApplication structured data (if present) is valid JSON and agrees with visible content.
- Internal links point to existing pages; links to external sites are useful and correctly attributed.
- Every new canonical, indexable blog URL is included in `dist/sitemap.xml`; the sitemap contains no staging or duplicate URLs.
- Images have suitable dimensions, file sizes, and meaningful alt text when informative.

Report concrete defects and exact paths. Do not promise rankings or treat keyword repetition, arbitrary word counts, or AI-citation scores as ranking factors. Revalidate changed pages after editing.
