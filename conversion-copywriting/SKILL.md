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

## Evaluation & QA

### Common Failure Modes
- Feature-first copy (speeds and feeds vs outcomes)
- Generic benefits that any competitor could claim
- Marketing voice instead of customer voice
- Burying the value below the fold
- Weak CTAs (Learn More, Submit, Click Here)
- No proof points (claims without evidence)
- Writing for everyone (copy that speaks to no one)