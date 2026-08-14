---
name: objection-handling
category: copy
description: Mine objections from research, write rebuttals with a proven formula, and place pre-emptive copy across every surface.
triggers:
  - "objection handling"
  - "rebuttals"
  - "why do customers say no"
  - "pre-empt objections"
  - "FAQ objections"
  - "handle objections in copy"
inputs:
  - customer_language_bank
  - review_corpus
  - sales_call_notes
  - competitor_messaging
outputs:
  - objection_inventory
  - rebuttal_library
  - objection_placement_map
related_skills:
  - customer-language-bank
  - value-proposition
  - conversion-copywriting
  - landing-page-copy
  - email-copy
  - marketing-intelligence/review-mining
required_context:
  - .context/product-marketing.md
allowed_tools: []
version: 1.0.0
---

## When to Use

Invoke when:
- Conversion stalls at a specific step (pricing page, demo booking, trial signup)
- Sales hears the same objections on every call
- Competitor comparisons consistently favor someone else
- Landing pages ignore the reasons prospects hesitate
- Reviews and churn interviews surface recurring complaints

## Workflow

### Step 1: Mine Objections

Extract objections from research, in the customer's words:
- Negative reviews (yours and competitors' — 2-4 star reviews carry the richest objections)
- Sales call notes and lost-deal summaries
- Support tickets and cancellation surveys
- Reddit threads and community posts
- Competitor comparison pages — what claims do they make against you?

Record each objection verbatim with its source.

**Gate:** 15+ raw objections logged with sources (or exhaustive for small datasets).

### Step 2: Categorize and Rank

Classify each objection:
- **Risk** — "what if it fails / breaks / doesn't work for us"
- **Cost** — price, budget, ROI doubt
- **Trust** — credibility, security, "we've been burned before"
- **Inertia** — status quo bias, switching cost, "not a priority right now"
- **Technical** — integration, scale, capability doubt
- **Competitive** — "why not [alternative]"

Rank by frequency × severity (how many prospects hold it × how hard it blocks the sale). The top 5 are your must-handle objections; the rest go to FAQ and support docs.

**Gate:** All objections categorized; top 5 ranked list produced.

### Step 3: Write Rebuttals

For each top objection, write a rebuttal using this formula:

1. **Acknowledge** — validate the concern in their words; never dismiss ("Fair — a lot of tools do break during setup")
2. **Reframe** — shift the frame from risk/cost to the real tradeoff, or correct a misconception
3. **Proof** — attach the strongest specific evidence (metric, case study, guarantee, third-party validation)
4. **Pivot** — bridge to the next step or the bigger promise

Write two versions per objection:
- **Direct rebuttal** — for FAQs, sales enablement, objection sections
- **Pre-emptive copy** — folded into prose so the reader never has to voice the objection

**Gate:** Top 5 objections each have a formula-complete direct rebuttal and a pre-emptive version.

### Step 4: Place Pre-emptive Copy

Map objections to surfaces where they arise in the funnel:

| Funnel stage | Surface | Objection format |
|---|---|---|
| Awareness | ads, social | hook that names the fear |
| Consideration | landing page, product page | FAQ band, comparison table, risk-reversal guarantee |
| Evaluation | pricing page | cost objection section, ROI framing, security badges |
| Decision | demo/sales call | one-pager, case study, references |
| Onboarding | welcome emails, in-app | inertia and setup-risk reassurances |

Place the strongest objection-killer (guarantee, case study, named customer) nearest the CTA — that is where hesitation peaks.

**Gate:** Every top objection has a home in the funnel map; CTA-adjacent placements identified.

### Step 5: QA and Arm the Team

Check each rebuttal:
- [ ] Empathy check — would a skeptical prospect feel heard, not managed?
- [ ] Proof check — is the evidence specific and true (no fabricated numbers)?
- [ ] Tone check — matches the voice guide, never defensive or sarcastic
- [ ] Honesty check — if the objection is partly true, admit it; partial admission raises credibility for everything else

Package the rebuttal library for sales (copy-paste blocks) and support (macro templates).

**Gate:** All four checks pass; library shared in a format sales and support will actually use.

## Evaluation & QA

### Common Failure Modes
- Rebuttals that argue instead of acknowledge — starting with "Actually..."
- Generic proof ("trusted by thousands") instead of specific evidence
- Handling every objection equally instead of the top 5
- Objection copy buried in an FAQ nobody scrolls to
- Inventing statistics to win an argument — fabrications surface and destroy trust
