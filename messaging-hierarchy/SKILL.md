---
name: messaging-hierarchy
category: strategy
description: Build a messaging architecture - positioning statement, value pillars, proof points, and taglines that cascade to every surface.
triggers:
  - "messaging architecture"
  - "message hierarchy"
  - "value pillars"
  - "tagline"
  - "message map"
  - "our messaging is inconsistent"
inputs:
  - positioning
  - customer_language_bank
  - proof_assets
  - competitor_messaging
outputs:
  - messaging_architecture_doc
  - value_pillars
  - proof_point_map
  - tagline_variants
related_skills:
  - value-proposition
  - brand-voice
  - customer-language-bank
  - conversion-copywriting
  - sales-deck
  - marketing-intelligence/positioning-framework
required_context:
  - .context/product-marketing.md
allowed_tools: []
version: 1.0.0
---

## When to Use

Invoke when:
- Every asset tells a different story about the product
- Positioning exists but copywriters keep inventing new claims
- Sales, marketing, and support describe the product differently
- Launching a new product, segment, or rebrand that needs a message system
- Need one source of truth to hand to agencies, contractors, and new hires

## Workflow

### Step 1: Lock the Positioning Statement

Before hierarchy, the foundation. Write the positioning statement:

- **Category** — what market/box the product lives in (the comparison customers make)
- **ICP** — who it is for, named segment
- **Problem** — the pain or unmet job, in customer language
- **Promise** — the outcome, quantified where possible
- **Differentiators** — the 2-3 provable "only" claims
- **Proof** — the strongest evidence per differentiator

This normally comes from the positioning framework or value-proposition skills; if it exists, verify and restate it — do not redesign it here.

**Gate:** Six-element positioning statement written and traceable to research.

### Step 2: Build the Value Pillars

Cluster the benefit evidence (pains, gains, differentiators, proof) into 3-5 pillars — no more. Each pillar:
- **Name** — an outcome label, not a feature name ("Ship releases in days, not quarters")
- **Core message** — one sentence per pillar, customer language, no jargon
- **Sub-messages** — 2-3 supporting points each
- **Proof** — the evidence assigned to this pillar
- **Objection it answers** — which hesitation it dissolves

Order pillars by: (1) what the ICP cares about most (from research, not internal opinion), (2) what differentiates most. Pillar 1 becomes the homepage hero; the rest become sections, email themes, and ad angles.

**Gate:** 3-5 pillars, each with core message, sub-messages, proof, and mapped objection.

### Step 3: Inventory and Map Proof Points

Build a proof table and map every piece to a pillar:

| Proof type | Examples | Use |
|---|---|---|
| Metrics | case study numbers, benchmarks | claims in heroes, decks |
| Testimonials | quotes, video | objection sections, sales |
| Named customers | logos, names with permission | trust bars, enterprise pages |
| Credentials | certifications, security, uptime | pricing pages, procurement |
| Demonstrations | demo, free tier, samples | CTAs, evaluation stage |

Flag pillar gaps: a pillar with no proof is an assertion until proof exists. Assign an owner and timeline for filling each gap.

**Gate:** Proof inventory mapped to pillars; gaps flagged with owners.

### Step 4: Derive Taglines and Soundbites

Taglines come from the top of the hierarchy, not from a thesaurus:
- Start from Pillar 1's core message and the five-word value prop variant
- Rules: 3-7 words, concrete noun/verb, no jargon, says something a competitor would not say
- Generate 10+ variants across tones (direct, witty, aspirational); shortlist 3

Soundbites: one quotable line per pillar for decks, ads, and PR ("what we say when someone asks").

**Gate:** 10+ tagline variants, 3 shortlisted, 1 soundbite per pillar.

### Step 5: Cascade to Surfaces

Write the surface map — where each layer of the hierarchy appears:

| Layer | Homepage | Sales deck | Emails | Ads | Support |
|---|---|---|---|---|---|
| Positioning | hero subtext | slide 2 | signature | — | internal |
| Pillars 1-5 | sections | narrative arc | campaign themes | ad angles | macro templates |
| Proof points | social proof band | traction slide | case study links | proof angles | — |
| Tagline | hero eyebrow | title slide | subject line patterns | headline variants | — |

Then the consistency test: take any existing asset and verify every claim traces to a pillar; anything that doesn't is either new research or noise — delete it.

**Gate:** Surface map complete; audit of 3 existing assets shows zero orphan claims.

## Practitioner Grounding & Decision Rules

Built from April Dunford (positioning/hierarchy), Andy Raskin (narrative), Anthony Pierri (message maps), David Perell (surprise), Hiten Shah (evidence-first). Full research: practitioner-intelligence/syntheses/positioning.md, messaging.md, messaging-longtail.md.

- **Hierarchy derives from positioning — it is not a redesign step** (Dunford — FRAMEWORK, T1): if positioning doesn't exist, do that work first; a hierarchy without a market frame is a feature list.
- **3-5 outcome pillars, each with proof and a mapped objection** (Dunford/Pierri — FRAMEWORK, T1): >5 pillars collapse into a feature list; a pillar with no proof is an assertion.
- **Narrative vs map** (Raskin vs Dunford — DISAGREEMENT, conditional): stable markets → hierarchy artifact + evidence; shifting markets with a credible big change → Raskin's story (big change → Promised Land → why now → as/if → new narrative).
- **Taglines come from Pillar 1, not a thesaurus** (skill standard + Dunford — HEURISTIC).
- **Consistency is the test**: every asset claim must trace to a pillar or it is noise (Dunford — FRAMEWORK, T1).

Decision rules:
1. IF positioning doesn't exist or is unproven THEN run the positioning work first — the hierarchy inherits everything from it (Dunford — FRAMEWORK, T1).
2. IF a pillar has no proof point THEN flag it as an assertion with an owner and timeline — never ship it as fact (Dunford evidence-first — FRAMEWORK, T1).
3. IF more than 5 pillars emerge THEN merge until 3-5 remain (Dunford/Pierri — HEURISTIC).
4. IF a tagline says something a competitor would also say THEN reject it (positioning synthesis — FRAMEWORK, T1).
5. IF a credible big change exists in the market THEN add the Raskin narrative layer (why now, Promised Land) on top of the hierarchy (Raskin — FRAMEWORK, T1); IF not THEN skip it — a story without a real shift rings false.
6. IF an existing asset contains a claim tracing to no pillar THEN delete it or re-research it (consistency test — FRAMEWORK, T1).

## Metrics

- **% of shipped assets with zero orphan claims** (primary — consistency audit; Dunford — FRAMEWORK, T1).
- **% of pillars with proof assigned** (evidence coverage; target 100% — Dunford).
- **Message/sales consistency**: sales and support describe the product using pillar language (qualitative check).
- **Timebox**: light review every 6 months; full re-workshop at new segment, major competitor, or category shift (Bare Strategy cadence — T2).

## Sources

1. April Dunford, positioning/hierarchy method | via positioning.md | tier 1 | 2026-08-14
2. Andy Raskin, Greatest Sales Deck (5 elements) | via positioning.md | tier 1 | 2026-08-14
3. Anthony Pierri, message maps | via positioning.md | tier 2 | 2026-08-14
4. Hiten Shah, PMF-language evidence | via positioning.md | tier 1 | 2026-08-14
5. David Perell, surprise-based structure | every.to Superorganizers | tier 1 | 2026-08-15

## Evaluation & QA

### Common Failure Modes
- Pillars that are features, not outcomes ("built on Rust" vs. "no downtime")
- More than 5 pillars — hierarchy collapses into a feature list
- Proof mapped to the wrong pillar (logo used as a metric)
- Tagline chosen for cleverness, disconnected from Pillar 1
- Hierarchy written but never cascaded — surfaces still tell their own story
- Copywriters kept out of the process, so adoption never happens
