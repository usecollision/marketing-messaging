---
name: conversion-copywriting
category: copy
description: Write high-converting copy for any marketing surface using research-backed frameworks and customer language.
triggers:
  - "write copy"
  - "conversion copy"
  - "copywriting"
  - "write landing page"
  - "headline"
  - "CTA"
  - "value proposition copy"
inputs:
  - product_context
  - icp
  - customer_language_bank
  - surface_type
outputs:
  - copy_document
  - headline_variants
  - cta_options
  - copy_rationale
related_skills:
  - marketing-intelligence/customer-research
  - marketing-intelligence/positioning-framework
  - marketing-optimize/landing-page-optimization
  - marketing-paid/ad-creative-generator
required_context:
  - .context/product-marketing.md
allowed_tools: []
version: 1.0.0
---

## When to Use

Invoke when writing copy for:
- Landing pages (hero, features, social proof, CTA)
- Email campaigns (subject, preview, body, CTA)
- Ad creative (headlines, descriptions, hooks)
- Product pages (value props, feature descriptions)
- Sales pages (long-form conversion copy)
- Signup flows and onboarding

## Read Context First

1. .context/product-marketing.md - Positioning, value props, voice
2. Customer research outputs (language bank, pain points) if available
3. Competitor copy for differentiation awareness

## Workflow

### Step 1: Copy Brief
Before writing a single word, define:
- **Surface:** Where will this copy live?
- **Audience:** Which ICP segment? What do they know already?
- **Goal:** What action should they take after reading?
- **Awareness level:** Unaware / Problem-aware / Solution-aware / Product-aware / Most aware
- **Emotional state:** What are they feeling when they see this?
- **One key message:** If they remember one thing, what is it?

**Gate:** Brief answers all 6 questions specifically.

### Step 2: Framework Selection
Choose copy framework based on awareness level:

| Awareness Level | Best Framework | Structure |
|----------------|---------------|-----------|
| Unaware | Story/Curiosity | Hook → Story → Reveal → CTA |
| Problem-aware | PAS | Problem → Agitate → Solution |
| Solution-aware | BAB | Before → After → Bridge |
| Product-aware | Features+Proof | Feature → Benefit → Proof → CTA |
| Most aware | Direct offer | Offer → Urgency → CTA |

**Gate:** Framework selected with awareness-level rationale.

### Step 3: Draft Copy
Write following these principles:

**Headlines:**
- Lead with the outcome, not the feature
- Use customer language (from research, not marketing speak)
- Specific > generic (numbers, timeframes, named outcomes)
- Test: Would this make your ICP stop scrolling?

**Body copy:**
- One idea per paragraph
- Short sentences. Fragments work.
- Transition with connectors (So... Here's the thing... But wait...)
- Use the word "you" more than "we"
- Concrete over abstract (show, don't tell)

**CTAs:**
- Value-first, not action-first (Get my free audit vs Submit)
- Low friction for low-awareness, high commitment for high-awareness
- Address the objection in the button vicinity

Write 3 headline variants and 2 body variants minimum.

**Gate:** Copy follows chosen framework, uses customer language, and has multiple variants.

### Step 4: Edit & Tighten
Run copy through these filters:
- [ ] Cut every word that doesn't earn its place
- [ ] Replace jargon with plain language
- [ ] Add specificity (replace vague claims with numbers/proof)
- [ ] Read aloud (does it sound natural?)
- [ ] Check: Would your ICP say this at a dinner party?
- [ ] Verify: Does each section advance toward the CTA?
- [ ] Remove weasel words (very, really, just, actually, basically)

**Gate:** Copy is 30-50% shorter than first draft with no loss of meaning.

### Step 5: Evaluate & Score
Score each variant:

| Criteria | Weight | Score (1-5) |
|----------|--------|-------------|
| Clarity (instant understanding) | 25% | |
| Relevance (speaks to ICP pain) | 25% | |
| Differentiation (unlike competitors) | 20% | |
| Emotion (creates feeling/urgency) | 15% | |
| Action (clear next step) | 15% | |

**Gate:** Best variant scores 3.5+ weighted average.

## Practitioner Grounding & Decision Rules

Built from Joanna Wiebe (Copyhackers), Momoko Price (Kantan), Eugene Schwartz (*Breakthrough Advertising*), Claude Hopkins, David Ogilvy, Gary Halbert, Ann Handley, Laura Belgray, Andre Chaperon, Alex Hormozi (T3, conditions). Full research: practitioner-intelligence/syntheses/messaging.md.

- **Copy comes from research, not creativity** (Wiebe, Price, Ogilvy, Hopkins, Halbert — FRAMEWORK, T1): five independent practitioners across 100 years agree — this is the strongest consensus in copywriting. Wiebe: "research and discovery is everything"; Ogilvy: "helpless without research". Customer language wins verbatim ("slightly revise" — Wiebe).
- **Market sophistication is the master variable** (Schwartz — FRAMEWORK, T1-canonical): stages 1-5 (direct claim → differentiated → mechanism → named mechanism → identity). Direct claims fail in saturated markets — "simple clear copy" advice is stage-1 logic applied to stage-3+ markets. Assess sophistication BEFORE choosing claim type.
- **Awareness levels** (Schwartz — FRAMEWORK, T1): the skill already maps frameworks to awareness — this is Schwartz's model; cold traffic needs problem-aware entry, warm/retargeting needs offer/close entry.
- **The offer precedes the copy** (Halbert, Hormozi, Schwartz — FRAMEWORK, T1/T2): copy amplifies existing demand; it does not manufacture it. If the offer can be compared away to alternatives, fix the offer first (Hormozi — T3, treat as heuristic).
- **Optimize a funnel, not a page** (Price — FRAMEWORK, T2): page-rewrite requests without funnel context are a category error.
- **Voice vs research are different layers** (Belgray/Handley vs Wiebe/Price — DISAGREEMENT, conditional): research supplies WHAT to say, voice supplies HOW. Voice is the differentiator in commoditized inboxes/social; message-match is the differentiator in unfamiliar categories.

Decision rules:
1. IF no customer language exists (no tickets, calls, surveys, reviews) THEN run research first — writing without it fails 99% of the time (Wiebe — FRAMEWORK, T1).
2. IF no baseline analytics exist THEN fix measurement before the copy project — unmeasurable copy work is gambling (Price — FRAMEWORK, T2).
3. IF the market is sophistication stage 3+ (competitors claiming the same outcomes) THEN lead with mechanism/proof, not outcome claims (Schwartz — FRAMEWORK, T1).
4. IF writing for cold traffic THEN enter at the problem-aware level; IF warm/retargeting THEN enter at the offer/close level — one message for all awareness levels is a category error (Schwartz — FRAMEWORK, T1).
5. IF the audience can compare the offer away to alternatives THEN stack the offer before writing more copy (Hormozi — HEURISTIC, T3).
6. IF the request is "rewrite this page" THEN reframe to "optimize this funnel step" — check drop-off context first (Price — FRAMEWORK, T2).
7. IF the category is commoditized (inboxes, social feeds) THEN lead with voice/personality; IF unfamiliar category THEN lead with message-match clarity (Belgray/Handley vs Wiebe — DISAGREEMENT, conditional, T2).
8. IF traffic supports conclusive tests THEN A/B test copy variants; IF not THEN use five-second clarity tests + funnel observation (Wiebe/Hopkins — FRAMEWORK, T1).

## Metrics

- **Baseline conversion + funnel drop-off deltas** per step (Price — FRAMEWORK, T2): the copy change is measured against the step's baseline, not the page's.
- **Response per variant** (Hopkins — EMPIRICAL, T1): test cheaply, keep winners, kill losers (test-measure-refine loop).
- **Clarity pass rate** on five-second tests (Wiebe — FRAMEWORK, T1).
- **Cost per acquisition per message variant** where trackable.

## Sources

1. Joanna Wiebe, Copyhackers 3-part copy process (research → write → validate) | copyhackers.com | tier 1 | 2026-08-14
2. Momoko Price, Kantan funnel-mapping method + TCC podcast #17 | kantan.io | tier 2 | 2026-08-14
3. Eugene Schwartz, *Breakthrough Advertising* (market sophistication, awareness) — exegesis via themarketingjuice | tier 2 (secondary on canonical) | 2026-08-14
4. Claude Hopkins, *Scientific Advertising* (test-measure-refine) | analyticstrategy.com | tier 1 | 2026-08-14
5. David Ogilvy, "11 rules" + *Ogilvy on Advertising* | awai.com | tier 1 | 2026-08-14
6. Gary Halbert, "The Starving Crowd" letter (offer-first, list bias) | thegaryhalbertletter.com | tier 1 | 2026-08-14
7. Ann Handley, *Everybody Writes* (simplicity, voice) | tier 1 | 2026-08-14
8. Laura Belgray, Talking Shrimp (voice-led email) | tier 2 | 2026-08-14
9. Alex Hormozi, *$100M Offers* (offer stacking — self-reported results, T3) | tier 3 | 2026-08-14

## Evaluation & QA

### Common Failure Modes
- Feature-first copy (speeds and feeds vs outcomes)
- Generic benefits that any competitor could claim
- Marketing voice instead of customer voice
- Burying the value below the fold
- Weak CTAs (Learn More, Submit, Click Here)
- No proof points (claims without evidence)
- Writing for everyone (copy that speaks to no one)