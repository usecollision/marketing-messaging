---
name: messaging-hierarchy
category: strategy
description - Build a messaging architecture - positioning statement, value pillars, proof points, and taglines that cascade to every surface.
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

## Evaluation & QA

### Common Failure Modes
- Pillars that are features, not outcomes ("built on Rust" vs. "no downtime")
- More than 5 pillars — hierarchy collapses into a feature list
- Proof mapped to the wrong pillar (logo used as a metric)
- Tagline chosen for cleverness, disconnected from Pillar 1
- Hierarchy written but never cascaded — surfaces still tell their own story
- Copywriters kept out of the process, so adoption never happens
