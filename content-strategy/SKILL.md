---
name: content-strategy
category: content
description: Build a content strategy that drives organic traffic, builds authority, and converts readers to customers.
triggers:
  - "content strategy"
  - "what should we write about"
  - "content plan"
  - "editorial calendar"
  - "content marketing"
inputs:
  - product_context
  - icp
  - keyword_research
  - competitive_content
outputs:
  - content_strategy_doc
  - editorial_calendar
  - content_pillars
  - distribution_plan
related_skills:
  - blog-writer
  - content-repurposing
  - marketing-channels/keyword-research
  - marketing-channels/content-calendar
required_context:
  - .context/product-marketing.md
allowed_tools:
  - mcp:web-search
version: 1.0.0
---

## When to Use

Invoke when:
- Starting content marketing from scratch
- Current content isn't driving traffic or conversions
- Need to plan next quarter's content
- Want to build topical authority in your space
- Content exists but has no strategy behind it

## Workflow

### Step 1: Content Audit (if existing content)
Assess what you already have:

| URL | Topic | Traffic/mo | Conversions | Ranking Keywords | Action |
|-----|-------|-----------|-------------|-----------------|--------|
| | | | | | Keep/Update/Merge/Kill |

Categories:
- **Keep:** Performing well, leave alone
- **Update:** Good topic, outdated or thin content
- **Merge:** Multiple posts on same topic, consolidate
- **Kill:** No traffic, no rankings, no relevance (redirect or remove)

**Gate:** Existing content categorized with clear actions.

### Step 2: Content Pillars
Define 3-5 content pillars (themes you want to own):

Each pillar should:
- Align with your product's value props
- Have search demand (validated by keyword research)
- Match ICP information needs at different funnel stages
- Be defensible (you have unique expertise/data)

`
Pillar 1: [Topic area]
  - Why: [connects to product value prop X]
  - ICP need: [what question this answers for them]
  - Funnel stage: [awareness/consideration/decision]
  - Keyword cluster: [from marketing-channels/keyword-research]
  - Content types: [blog, guide, tool, template]
`

**Gate:** 3-5 pillars defined with business rationale and keyword backing.

### Step 3: Content Types & Funnel Mapping
Map content types to funnel stages:

| Funnel Stage | Content Type | Goal | CTA |
|-------------|-------------|------|-----|
| Awareness | How-to guides, listicles, trends | Traffic + email capture | Newsletter signup |
| Consideration | Comparisons, case studies, guides | Trust + evaluation | Free trial/demo |
| Decision | Product tutorials, ROI calculators | Conversion | Start free trial |
| Retention | Best practices, advanced guides | Activation + expansion | Feature adoption |

Content mix recommendation:
- 60% Awareness (traffic engine)
- 20% Consideration (conversion engine)
- 10% Decision (sales enablement)
- 10% Retention (customer success)

**Gate:** Content types mapped with clear funnel alignment and CTA strategy.

### Step 4: Editorial Calendar
Build a realistic publishing cadence:

| Week | Pillar | Content Type | Topic | Target Keyword | Funnel | Owner | Status |
|------|--------|-------------|-------|---------------|--------|-------|--------|

Cadence guidelines:
- 1 person: 1-2 posts/week
- Small team (2-3): 3-4 posts/week
- Content team (4+): Daily

Quality > quantity always. One great post beats four mediocre ones.

**Gate:** 4-8 weeks of content planned with topics, keywords, and owners.

### Step 5: Distribution Strategy
Content without distribution is invisible:

**Owned channels:**
- Email newsletter (every new post)
- Social media (LinkedIn, X, Reddit - native format per platform)
- Community (Discord, Slack, relevant forums)

**Earned channels:**
- SEO (the long game, 3-6 months to compound)
- Social sharing (design for shareability)
- Backlinks (outreach for key pieces)

**Repurposing:**
- Blog → Twitter thread → LinkedIn post → Newsletter section → Video script
- Every piece should be repurposed into 5+ formats

**Gate:** Distribution checklist defined for each piece of content published.

## Evaluation & QA

### Common Failure Modes
- Writing about what YOU find interesting vs what ICP searches for
- No keyword targeting (content without SEO = no compounding traffic)
- Publishing without distribution (build it and they will NOT come)
- Inconsistent cadence (2 posts one week, nothing for a month)
- No conversion mechanism (traffic without email capture = wasted)
- Only awareness content (need consideration + decision to convert)