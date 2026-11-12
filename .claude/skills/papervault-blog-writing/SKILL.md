---
name: papervault-blog-writing
description: Write or revise an original PaperVault PDF guide for this static HTML site. Use for blog posts, how-to articles, outlines, and editorial updates.
---

# PaperVault blog writing

Write for people trying to finish a real document task. Lead with a useful answer and a recognizable reader problem, then give actionable guidance in a helpful, privacy-conscious voice.

## Before drafting

- Read `docs/content-skills.md`, the App Store listing, the privacy policy, and existing relevant blog pages.
- Decide what the page uniquely answers and avoid repeating another guide's intent.
- Research before writing. Prefer authoritative primary sources for technical claims and the current App Store listing and privacy policy for PaperVault claims. If delegating research, specify the question and where to save findings, then verify the source material yourself.
- Keep a short claim/source note while drafting. Cite sources next to the claims they support; never invent citations or attribute a claim to a source that does not support it.
- If an app interaction is not shown in the source material, describe the feature without fabricating button names or exact screen sequences.

## Reader-first structure

- Open in 2-3 sentences: name a concrete reader problem and answer the main question early.
- Give enough context to explain when the guidance matters, then use 3-5 purposeful H2 sections.
- Include practical steps, a checklist, or a decision point where it helps the reader act.
- Close with up to three concise takeaways and a relevant next step. Skip a repetitive recap when the opening already covers it.
- Keep the page scannable with short paragraphs, meaningful lists, and the site's existing article visuals. Use genuine app screenshots only for features they actually show; never invent a screen or require generated cover art.

## Product accuracy

- PaperVault features and compatibility must match its current App Store listing.
- Privacy statements must match the published privacy policy; distinguish on-device app processing from any file provider a reader chooses.
- Do not claim every PDF is searchable, every signature is legally sufficient, compression is lossless, passwords can be recovered, or metadata removal redacts visible content.
- Treat product availability, pricing, OS compatibility, and third-party integrations as changeable; verify them at publication time.

## Static page requirements

- Add a unique, descriptive page title under 60 characters where practical, a useful meta description (aim for 150-160 characters without padding), canonical URL, Open Graph basics, one H1, and readable section headings.
- Use the main search phrase naturally in the title and opening. Do not repeat keywords just to meet a frequency target.
- Use semantic HTML, accessible links, descriptive image alt text, and links to related PaperVault guides.
- Add appropriate `BlogPosting` JSON-LD only when its visible page data is accurate.
- Include a source list with working links. Do not include decorative or unsupported citations.
- Add the page to `dist/blog/index.html` and `dist/sitemap.xml`; check canonical URLs use the GitHub Pages project path.
- Link to the App Store only where it genuinely helps the reader.

The research-first structure and visual/SEO checklist adapt ideas from LangChain AI's MIT-licensed [blog-post skill](https://github.com/langchain-ai/deepagents/tree/main/examples/content-builder-agent/skills/blog-post). This PaperVault workflow is tailored to a static HTML site and its fact-checking rules; it does not copy the upstream tool-specific workflow. See [the license notice](../../../docs/licenses/langchain-deepagents-MIT.txt).
