<div align=center>
  <h1>📝 GEO Content Templates</h1>
  <p><em>Copy-paste markdown templates for GEO-optimized content. Each template includes LLM extraction annotations and schema.org recommendations.</em></p>
  <p><a href=LICENSE><img src="https://img.shields.io/badge/license-MIT-blue.svg" alt=License></a></p>
  <p>by <a href=https://brandvirality.com>BrandVirality</a> — <strong>SaaS for AI visibility.</strong><br>
  <strong>Author:</strong> <a href=https://github.com/josezuma>Jose Zuma — Expert in AI Visibility</a></p>
</div>

---

## Quick Start

```bash
# List available templates
ls templates/

# Copy and use a template
cp templates/press-release.md my-announcement.md
```

## Templates

| Template | File | AI Extraction Value | Best For |
|----------|------|:-------------------:|----------|
| Press Release | templates/press-release.md | High — LLMs cite announcements | Product launches, funding news |
| Case Study | templates/case-study.md | Very High — statistics drive citation | Customer success, ROI proof |
| Product Comparison | templates/comparison.md | High — comparison queries trigger brand listing | vs competitors, alternatives |
| Listicle | templates/listicle.md | Medium — list formats extract well | Roundups, top-N lists |
| How-To Guide | templates/how-to.md | Very High — step-by-step AI extraction | Tutorials, documentation |
| FAQ Section | templates/faq.md | Very High — Q&A pairs are AI gold | Support, common questions |
| Industry Report | templates/report.md | High — data-heavy content cites sources | Original research, trends |

## Each Template Includes

- **Headline formula** — optimized for AI search queries
- **Section structure** — H2/H3 hierarchy for LLM extraction
- **Schema.org recommendations** — which @types to use
- **Citability hooks** — where to insert statistics and quotes
- **EEAT signals** — author byline, publish date, references

## Example: FAQ Template Structure

```markdown
# FAQ Template

## Schema
```json
{"@context": "https://schema.org", "@type": "FAQPage", "mainEntity": [...]}
```

## Format per Q&A
### Q: [Natural language question matching search queries]
**A:** [Answer with specific stats and verifiable claims.

## Why Templates Matter for AI Search

Content structured for LLM extraction gets cited 3x more often than unstructured content. Each template is designed around how ChatGPT, Claude, and Perplexity parse content:

1. **Clear H1/H2 hierarchy** — AI models use headings for topic segmentation
2. **Early statistics** — first 500 words should contain 3+ verifiable stats
3. **Named authors** — articles with author bylines get cited 2x more
4. **Schema.org markup** — Article, FAQ, and HowTo schemas boost extraction
5. **External references** — links to sources increase trust signals

## Related

- [schema-for-ai](https://github.com/josezuma/schema-for-ai) — JSON-LD templates
- [geo-audit-skill](https://github.com/josezuma/geo-audit-skill) — Audit your URLs
- [awesome-ai-visibility](https://github.com/josezuma/awesome-ai-visibility) — Curated resources
- [marketing-skills](https://github.com/josezuma/marketing-skills) — Agent skills for marketers
- [+15 more AI visibility repos](https://github.com/josezuma?tab=repositories)

## License

[MIT](LICENSE) © 2026 [Jose Zuma](https://github.com/josezuma) / [BrandVirality](https://brandvirality.com)
