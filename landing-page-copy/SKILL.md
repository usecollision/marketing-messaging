---
name: landing-page-copy
category: copy
description: Write complete landing page copy with hero, features, social proof, objection handling, and CTA sections.
triggers:
  - "landing page copy"
  - "write a landing page"
  - "homepage copy"
  - "sales page"
  - "product page copy"
inputs:
  - product_context
  - icp
  - page_goal
  - awareness_level
outputs:
  - full_page_copy
  - section_breakdown
  - headline_variants
  - social_proof_strategy
related_skills:
  - conversion-copywriting
  - marketing-optimize/landing-page-optimization
  - marketing-intelligence/positioning-framework
required_context:
  - .context/product-marketing.md
allowed_tools: []
version: 1.0.0
---

## When to Use

Invoke when building or rewriting:
- Product landing pages
- Feature-specific pages
- Campaign landing pages (ads, launches)
- Homepage
- Pricing pages
- Sales/long-form pages

## Workflow

### Step 1: Page Strategy
Define the page's job:
- **Traffic source:** Where are visitors coming from? (ads, SEO, email, social)
- **Awareness level:** What do they already know?
- **Primary CTA:** One action you want them to take
- **Secondary CTA:** Fallback for not-ready visitors
- **Page length:** Short (awareness), Medium (consideration), Long (decision)

**Gate:** Page strategy defined with traffic source and CTA clarity.

### Step 2: Section Architecture
Build the page structure (adapt based on awareness):

**Standard landing page structure:**
1. **Hero** - Headline + subhead + CTA + visual (5 seconds to communicate value)
2. **Problem** - Agitate the pain they feel (empathy before solution)
3. **Solution** - How you solve it (bridge from pain to product)
4. **Features/Benefits** - 3-5 key capabilities with outcomes
5. **Social Proof** - Testimonials, logos, metrics, case studies
6. **Objection Handling** - FAQ or content addressing top concerns
7. **Final CTA** - Restate value + clear action + urgency if appropriate

**Gate:** Section order matches awareness level and traffic source expectations.

### Step 3: Hero Section (most critical)
Write the hero with:
- **Headline:** One clear statement of transformation or outcome (not feature)
- **Subheadline:** Expand on how or for whom
- **Supporting copy:** 1-2 sentences of proof or context
- **CTA:** Action-oriented, value-first button text
- **Visual direction:** What image/video supports the message

Write 5 headline options:
1. Outcome-focused
2. Pain-focused
3. Curiosity-driven
4. Specific/numbers
5. Customer language (verbatim from research)

**Gate:** Hero communicates who this is for, what they get, and what to do next in <5 seconds.

### Step 4: Body Sections
For each section, write:
- Section headline (scannable, standalone meaning)
- Body copy (2-4 sentences max per block)
- Proof element (metric, quote, screenshot)
- Transition to next section

**Rules:**
- Every feature must have a "so what" benefit
- Every claim must have proof
- Every section must advance toward CTA
- Scanners should get the message from headlines alone

**Gate:** Page reads coherently when only headlines are read (the scanner test).

### Step 5: Social Proof Strategy
Design proof elements:
- **Logos:** 5-8 recognizable customer logos
- **Metrics:** 2-3 aggregate stats (X users, Y% improvement, Z customers)
- **Testimonials:** 2-3 quotes with name, role, company, photo, specific outcome
- **Case study teaser:** One mini story (problem → solution → result)

**Gate:** Proof directly supports the claims made in feature sections.

## Practitioner Grounding & Decision Rules

Built from Joanna Wiebe (Copyhackers), Momoko Price (Kantan), Michael Aagaard (message-match CRO), Chris Widener (LIFT), Eugene Schwartz, Ann Handley, Alex Hormozi. Full research: practitioner-intelligence/syntheses/messaging.md, cro.md, messaging-longtail.md.

- **Optimize a funnel step, not a page** (Price — FRAMEWORK, T2): page-rewrite requests without funnel context are a category error; baseline analytics gate the project.
- **Message-match is the biggest copy lever** (Aagaard — EMPIRICAL, T1): Saxo +99.4%, Bettingexpert +31.5% from value-clarity/message fixes; if the value prop isn't clear in 5 seconds, layout and testing are premature (Wolf agrees: messaging audit first).
- **LIFT factors as the diagnosis lens** (Widener — FRAMEWORK, weakly validated): value proposition, relevance, clarity, urgency, distraction, anxiety reduction — organize leaks by factor before rewriting.
- **Research before writing; customer language verbatim** (Wiebe, Ogilvy, Hopkins — FRAMEWORK, T1): the strongest consensus in copywriting across 100 years.
- **Awareness level decides entry and structure** (Schwartz — FRAMEWORK, T1): unaware → story/curiosity; product-aware → proof + offer; one message for all awareness levels is a category error.

Decision rules:
1. IF no baseline conversion/drop-off data exists for the step THEN set up measurement before rewriting the page (Price — FRAMEWORK, T2).
2. IF the hero's value prop isn't clear in 5 seconds (five-second test fails) THEN fix message-match before anything else (Wiebe/Aagaard — FRAMEWORK, T1).
3. IF drop-off concentrates below the fold or at the CTA THEN check LIFT anxiety/distraction factors (guarantee, clarity of next step) before rewriting copy (Widener — FRAMEWORK, T2).
4. IF traffic can't support conclusive A/B tests THEN validate with five-second tests + funnel observation instead (Wiebe/Hopkins — FRAMEWORK, T1).
5. IF the offer can be compared away to alternatives THEN stack the offer before writing more copy (Hormozi — HEURISTIC, T3).
6. IF writing for cold traffic THEN enter at the problem-aware level; IF warm/retargeting THEN enter at offer/close level (Schwartz — FRAMEWORK, T1).

## Metrics

- **Step conversion + funnel drop-off deltas** (primary — Price, T2): the page is measured against its step's baseline, not the site average.
- **Five-second clarity pass rate** (Wiebe — FRAMEWORK, T1): hero test with a cold reader before launch.
- **CTA click-through and completion** per variant (Hopkins test-measure-refine — EMPIRICAL, T1).
- **Timebox**: 2-4 weeks per test at meaningful traffic; re-measure when traffic sources, offer, or funnel structure change.

## Sources

1. Joanna Wiebe, Copyhackers 3-part copy process | copyhackers.com | tier 1 | 2026-08-14
2. Momoko Price, Kantan funnel mapping + TCC podcast #17 | kantan.io | tier 2 | 2026-08-14
3. Michael Aagaard, message-match case studies (Saxo +99.4%, Bettingexpert +31.5%) | via cro.md synthesis | tier 2 | 2026-08-14
4. Chris Widener, LIFT model | via cro.md synthesis | tier 3 | 2026-08-14
5. Eugene Schwartz, *Breakthrough Advertising* (awareness/sophistication) | tier 2 (secondary on canonical) | 2026-08-14
6. Alex Hormozi, *$100M Offers* (offer stacking — T3) | tier 3 | 2026-08-14

## Evaluation & QA

### Landing Page Scorecard
| Element | Check | Score (1-5) |
|---------|-------|-------------|
| Hero clarity | Value prop clear in 5 sec | |
| Benefit focus | Outcomes > features | |
| Proof density | Claims backed by evidence | |
| Objection handling | Top 3 objections addressed | |
| CTA strength | Clear, value-first, low friction | |
| Scannability | Headlines tell full story | |
| Voice match | Sounds like the brand | |
| Mobile readability | Short paragraphs, clear hierarchy | |

### Common Failure Modes
- Hero that describes the product instead of the outcome
- No clear primary CTA (multiple competing actions)
- Social proof that doesn't match the ICP (wrong logos/quotes)
- Feature lists without benefits
- No objection handling (FAQ at minimum)
- Wall of text (nobody reads paragraphs online)