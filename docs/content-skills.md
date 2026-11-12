# PaperVault content skills

These repo-local skills are original workflows for PaperVault's product facts, static site, and publishing process:

- `.claude/skills/papervault-content-strategy/SKILL.md` plans useful, non-duplicative reader topics.
- `.claude/skills/papervault-blog-writing/SKILL.md` drafts and formats original articles for this static site.
- `.claude/skills/papervault-fact-checking/SKILL.md` verifies product and editorial claims against sources.
- `.claude/skills/papervault-seo-review/SKILL.md` reviews crawlability, metadata, internal links, and sitemap coverage.

The workflows were informed by the open-source [Marketing Skills](https://github.com/coreyhaines31/marketingskills) and [Claude Blog](https://github.com/AgriciDaniel/claude-blog) projects. Their MIT licenses permit reuse with notices; this repository does not include their skill text or code. These project-specific instructions are not affiliated with or endorsed by either project. Search ranking or AI citation outcomes are not guaranteed.

## Editorial source of truth

Use the [PaperVault App Store listing](https://apps.apple.com/in/app/papervault-pdf-page-tools/id6809174782) and the website's [privacy policy](../dist/privacy.html) for product capabilities and privacy claims. The App Store listing currently states iOS 17.6 or later. Recheck the live listing before repeating version, compatibility, or feature details. Never invent app screens, customer results, review counts, or legal/privacy guarantees.

## Publish checklist

1. Write original, useful articles rather than paraphrasing another publisher.
2. Link readers to relevant guides, the privacy policy, and the App Store listing where helpful.
3. Give each public page a unique title, description, canonical URL, one clear H1, and crawlable links.
4. Add every new public, indexable article URL to `dist/sitemap.xml`.
5. Check every claim and link, then validate the sitemap and page markup before deployment.
