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

## Practitioner Grounding & Decision Rules

Built from Ryan Law (audience-first), Tim Soulo (traffic potential), Ross Simmonds (distribution), Kieran Drew/Indig (content quality floor). Full research: practitioner-intelligence/syntheses/seo.md, messaging-longtail.md.

- **Audience-first, not keyword-volume-first** (Law — FRAMEWORK, T1): define the buyer and their problem before the keyword list; volume without intent converts no one (Soulo/Dunning — EMPIRICAL, T1).
- **Traffic potential over search volume** (Soulo — EMPIRICAL, T1): rank by realistic traffic potential × conversion likelihood, not raw volume.
- **Distribution is half the job** (Simmonds — FRAMEWORK, T1): "the work happens after you press publish"; a publish without a distribution checklist is invisible.
- **Quality floor over mass production** (Indig/Google enforcement — EMPIRICAL, T1): mass templated content without differentiation collapses (2024-26 scaled-content enforcement).
- **Publish-and-forget is the decay treadmill** (Indig — EMPIRICAL, T1): content decays; update/merge/kill is part of the strategy.

Decision rules:
1. IF a keyword has volume but no buyer intent THEN skip it (Soulo/Dunning — EMPIRICAL, T1).
2. IF the topic doesn't map to a defined buyer's problem THEN don't publish it (Law — FRAMEWORK, T1).
3. IF a piece is published without a distribution checklist THEN the plan is incomplete (Simmonds — FRAMEWORK, T1).
4. IF a page underperforms for 3-6 months THEN update, merge, or kill — don't just add more (Indig — EMPIRICAL, T1).
5. IF building programmatic/templated content THEN require a quality floor per template (differentiation + value per page) or don't scale it (Indig/Google — EMPIRICAL, T1).
6. IF the audience lives on a specific channel THEN allocate distribution budget there before expanding elsewhere (Simmonds — HEURISTIC, T1).

## Metrics

- **Traffic potential × conversion per topic** (primary — Soulo, T1): demos/leads from content, not just visits (Dunning).
- **Distribution coverage**: % of pieces with a full distribution checklist executed (Simmonds — FRAMEWORK, T1).
- **Content decay rate**: % of pages needing refresh per quarter (Indig — EMPIRICAL, T1).
- **Timebox**: quarterly content audit (keep/update/merge/kill); SEO compounding judged at 3-6 months minimum.

## Sources

1. Ryan Law, audience-first content | via seo.md synthesis | tier 1 | 2026-08-14
2. Tim Soulo, traffic potential vs volume | via seo.md synthesis | tier 1 | 2026-08-14
3. Ross Simmonds, distribution | rosssimmonds.com | tier 1 | 2026-08-15
4. Indig (Kevin Indig), content decay + quality floor | via seo.md synthesis | tier 1 | 2026-08-14
5. Alex Dunning, bottom-funnel intent | via seo.md synthesis | tier 2 | 2026-08-14

## Evaluation & QA

### Common Failure Modes
- Writing about what YOU find interesting vs what ICP searches for
- No keyword targeting (content without SEO = no compounding traffic)
- Publishing without distribution (build it and they will NOT come)
- Inconsistent cadence (2 posts one week, nothing for a month)
- No conversion mechanism (traffic without email capture = wasted)
- Only awareness content (need consideration + decision to convert)