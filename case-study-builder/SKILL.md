---
name: case-study-builder
category: content
description: Build metrics-first case studies - challenge-solution-results structure, quantified outcomes, and repurposed variants for every channel.
triggers:
  - "case study"
  - "customer story"
  - "success story"
  - "write a case study"
  - "testimonial long form"
inputs:
  - customer_interview
  - product_context
  - usage_data
  - permission_scope
outputs:
  - case_study_doc
  - metrics_section
  - customer_quotes
  - repurposed_variants
related_skills:
  - customer-language-bank
  - value-proposition
  - objection-handling
  - sales-deck
  - email-copy
  - marketing-channels/linkedin-content
required_context:
  - .context/product-marketing.md
allowed_tools: []
version: 1.0.0
---

## When to Use

Invoke when:
- A customer achieved a measurable, permissioned result worth telling
- Sales needs proof for a specific objection or vertical
- Launching a case study page, PDF, or sales collateral
- Repurposing one story across website, email, social, and decks

## Workflow

### Step 1: Select the Story

Score candidate customers on:
- **Measurable outcome** — real numbers the customer will verify (revenue, time, cost, churn)
- **ICP representativeness** — does the target buyer recognize themselves?
- **Novelty** — a fresh angle (segment, use case, objection defeated)
- **Permission** — explicit, scoped approval to publish names, numbers, and quotes (before writing, not after)

Reject stories without numbers or without permission — a "great relationship" story is a testimonial, not a case study.

**Gate:** One customer selected; permission scope confirmed in writing.

### Step 2: Interview for the Arc

Run a structured interview covering:
- **Before:** what the situation, tool, or process looked like; what it cost them (their words)
- **Trigger:** the moment they decided to change
- **Alternatives:** what else they evaluated and why it lost
- **Decision:** what convinced them (feature, proof, team, price)
- **Implementation:** timeline, effort, friction, who was involved
- **After:** measured results, plus the emotional payoff ("what changed for you personally")

Record verbatim; the interview is the source for quotes and customer-language phrasing.

**Gate:** Interview complete with answers for all six beats; quotes marked for potential use.

### Step 3: Extract and Verify Metrics

- List every number mentioned; separate hard metrics (system/report data) from soft estimates (memory, feeling)
- Quantify the before/after delta with timeframe ("from 3 days to 4 hours, monthly")
- Get written sign-off on every published number and quote
- Label anything unverifiable as an estimate or drop it — fabricating or inflating numbers is a hard stop

**Gate:** Metrics table with verified numbers and explicit customer sign-off.

### Step 4: Write the Headline

Metrics-first headline rule: lead with the outcome, not the customer's name or your product:

- "How [customer] cut [pain] by [X%] in [timeframe]" — outcome + delta
- Variation: "[Specific metric] in [timeframe]: the [segment] playbook"
- Include the one number that would stop your ICP mid-scroll

Write 3+ variants; pick the one with the most specific, most relatable metric.

**Gate:** 3+ headline variants, all leading with an outcome metric.

### Step 5: Build the Narrative (Challenge → Solution → Results)

- **Challenge (25%)** — the before-state in the customer's words: situation, cost of status quo, failed attempts. This is where the reader says "that's us"
- **Solution (30%)** — what they chose and why (include the alternatives considered — the comparison sells), how implementation went, what changed in practice
- **Results (45%)** — lead with the metrics table, then the narrative of the numbers (what each metric means for their business), close with a verbatim customer quote and the emotional payoff

Proof-placement rules: one metric in the challenge's stakes, the metrics table at the top of results, quotes at decision points — not all proof stacked at the end.

**Gate:** Three-part structure with the 25/30/45 emphasis split; quote closes the story.

### Step 6: Repurpose into Variants

One story, many assets:

| Variant | Format | Use |
|---|---|---|
| Long form | 800-1200 words + metrics table | website, SEO |
| One-pager | headline + metrics + quote + 3 bullets | sales follow-up |
| Slide | 3 slides: challenge/solution/results | decks |
| Social | quote card, metric card, thread | LinkedIn, X |
| Email | 2-3 paragraph teaser linking to long form | nurture, ABM |

Each variant keeps the same metrics-first headline logic and points to the full story.

**Gate:** Long form plus at least 2 variants produced; all share the same verified numbers.

## Practitioner Grounding & Decision Rules

Built from Joanna Wiebe (metrics-first proof), David Ogilvy (proof discipline), Clozd (verification/win-loss discipline), Ross Simmonds (repurpose/remix/reshare). Full research: practitioner-intelligence/syntheses/messaging.md, research.md, messaging-longtail.md.

- **Metrics-first headline: outcome + delta + timeframe** (Wiebe — FRAMEWORK, T1): lead with the number that stops your ICP mid-scroll, not the logo.
- **Proof discipline: every published number verified and signed off** (Ogilvy/Clozd — EMPIRICAL, T1): fabricating or inflating numbers is a hard stop; unverifiable numbers become estimates or get dropped.
- **Challenge-solution-results with proof placed at the moment of doubt** (Wiebe/Price — FRAMEWORK, T1): one metric in the challenge's stakes, metrics table at the top of results, quotes at decision points — not all proof stacked at the end.
- **Story selection requires numbers + permission** (skill standard — HEURISTIC): a "great relationship" story without verifiable outcomes is a testimonial, not a case study.
- **Repurpose with the same verified numbers** (Simmonds — FRAMEWORK, T1): create once, distribute forever — every variant keeps the same metrics-first logic and points to the full story.

Decision rules:
1. IF no verifiable numbers AND no written permission THEN don't build the case study (skill standard — HEURISTIC).
2. IF the headline doesn't lead with an outcome metric THEN rewrite it (Wiebe metrics-first — FRAMEWORK, T1).
3. IF a number can't be verified from system/report data THEN label it an estimate or drop it (Clozd/Ogilvy — EMPIRICAL, T1).
4. IF repurposing THEN keep the same verified numbers across variants — never re-derive or "improve" metrics per channel (Simmonds/skill standard — FRAMEWORK, T1).
5. IF the reader is an executive THEN lead results with the metrics table; IF technical THEN include implementation detail (conditional — HEURISTIC).
6. IF the story has no trigger moment or alternatives considered THEN the interview is incomplete — those beats sell the comparison (skill standard — HEURISTIC).

## Metrics

- **Verification rate**: 100% of published numbers signed off by the customer (Clozd — EMPIRICAL, T1).
- **Story conversion**: case study's influence on demo bookings/deal velocity (sales-sourced — HEURISTIC).
- **Variant yield**: number of repurposed assets per story (Simmonds — target ≥3 variants: one-pager, slide, social).
- **Timebox**: refresh or retire case studies when metrics age past ~18 months or the product materially changes.

## Sources

1. Joanna Wiebe, metrics-first proof structure | copyhackers.com | tier 1 | 2026-08-14
2. David Ogilvy, proof discipline | awai.com | tier 1 | 2026-08-14
3. Clozd, win/loss verification discipline | clozd.com | tier 1 | 2026-08-15
4. Ross Simmonds, create once/distribute forever + Three Rs | theagentsofchange.com + kpplaybook.com | tier 1 | 2026-08-15
5. Momoko Price, proof placement at moment of doubt | kantan.io | tier 2 | 2026-08-14

## Evaluation & QA

### Common Failure Modes
- Story led by the customer's logo instead of the outcome metric
- Challenge section too thin — readers can't recognize themselves
- Results buried under process detail; metrics not in a scannable table
- Unverified numbers or quotes published (permission and accuracy problems)
- One giant PDF used for every channel instead of channel-fit variants
- Writing the solution as a feature tour instead of a decision story
