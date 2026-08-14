---
name: email-copy
category: copy
description: Write lifecycle and marketing email copy: subject lines, preview text, body structure, and CTAs that get opened and clicked.
triggers:
  - "email copy"
  - "write an email"
  - "email subject line"
  - "newsletter copy"
  - "lifecycle email"
  - "welcome email"
  - "winback email"
inputs:
  - email_goal
  - audience_segment
  - lifecycle_stage
  - offer_details
outputs:
  - email_copy
  - subject_line_variants
  - preview_text
  - cta_options
related_skills:
  - conversion-copywriting
  - objection-handling
  - customer-language-bank
  - brand-voice
  - case-study-builder
  - marketing-channels/lifecycle-sequences
required_context:
  - .context/product-marketing.md
allowed_tools: []
version: 1.0.0
---

## When to Use

Invoke when:
- Writing lifecycle emails (welcome, activation, retention, winback)
- Writing marketing sends (launch, newsletter, promo, event)
- Open rates are fine but clicks are weak — the body isn't earning the CTA
- Subject lines are an afterthought written in 30 seconds
- Need a repeatable email structure across segments and stages

## Workflow

### Step 1: Write the Email Brief

Define before writing:
- **Type** — lifecycle stage or marketing send (see table below)
- **Goal** — one action, one metric that defines success
- **Segment** — who gets it; what do they already know?
- **One message** — if they forget everything, what one idea remains?
- **Tone** — per the voice guide; email is the most personal surface, write like a human writing to one person

Lifecycle reference (goal → approach):

| Stage | Goal | Approach |
|---|---|---|
| Welcome | set expectation, first value | deliver the promised thing, one CTA, warm |
| Activation | get the key action done | single task, remove friction, short |
| Nurture | move toward readiness | teach one useful thing, soft CTA |
| Conversion | get the yes | offer + proof + objection handling |
| Retention | deepen usage | new capability, success stories |
| Winback | recover the relationship | acknowledge absence, new reason, low ask |

**Gate:** Brief answers all five questions; stage's goal and approach stated.

### Step 2: Subject Line and Preview Text

Write 5+ subject variants using distinct formulas:
- **Benefit** — the outcome ("Close books in 2 hours this month")
- **Curiosity** — open loop without clickbait ("The spreadsheet trick we stole from our CFO")
- **Question** — only when it matches a real customer question
- **Numbered list** — concrete and skimmable ("3 reports that show churn coming")
- **Scarcity/urgency** — only when true

Rules:
- Front-load key words (mobile inboxes truncate; keep the important words in the first ~40 characters — heuristic, not a hard limit)
- No ALL CAPS, no excessive punctuation, no "Re:" tricks
- Preview text continues the thought, never repeats the subject — treat the pair as one two-line ad

**Gate:** 5+ variants from at least 3 formulas; preview text written as a continuation for the chosen subject.

### Step 3: Body Structure

Structure by email type:
- **Transactional/lifecycle:** 1-3 short paragraphs, one idea each; the CTA within the first scroll
- **Nurture/educational:** hook line → the one lesson → why it matters → soft CTA
- **Launch/promo:** what's new → why it matters to them → proof → CTA
- **Winback:** acknowledge → what changed → small ask

Copy rules:
- Second person ("you") throughout; "we" only for accountability
- Scannable: short paragraphs (2-3 sentences max), bullets for features/benefits
- One primary CTA per email; a secondary link only if it doesn't compete
- Personalization beyond the first name — reference their segment, usage, or stage (only with real data)

**Gate:** Body follows the type's structure, one CTA, readable in a 15-second skim.

### Step 4: Write the CTA

- Value-first label: name the outcome or the thing they get ("Get the 2-hour close checklist" > "Download now" > "Click here")
- Match commitment to stage: low-friction actions for early stages (read, watch), direct asks for conversion
- Place the objection-killer (guarantee, no-credit-card, proof) directly under the CTA
- Write 3 CTA variants for testing

**Gate:** CTA is value-first, stage-appropriate, with adjacent risk-reversal.

### Step 5: QA and Send-Readiness

- [ ] Read aloud — does it sound like one person talking to another?
- [ ] Plain-text version — re-render without images; does it still work?
- [ ] Spam check — no excessive punctuation, spammy phrases, or ALL CAPS
- [ ] Deliverability hygiene — working from-name, honest subject (matches content), unsubscribe present
- [ ] Mobile skim — subject, preview, first line, and CTA visible before scrolling
- [ ] Variant plan — which element gets A/B tested first (subject is the default first test)

**Gate:** All checks pass; test variant documented with a hypothesis.

## Evaluation & QA

### Common Failure Modes
- Subject and preview written in isolation — the pair should read as one continuous hook
- Every email a sales email — lifecycle stages get promo copy instead of stage-appropriate help
- Multiple competing CTAs
- Subject promises what the body doesn't deliver (clickbait → spam complaints, unsubscribes)
- Writing to "all subscribers" instead of a segment with a known state
- Ignoring plain-text and mobile rendering until after send
