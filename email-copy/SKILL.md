---
name: email-copy
category: copy
description: Write lifecycle and marketing email copy - subject lines, preview text, body structure, and CTAs that get opened and clicked.
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

## Practitioner Grounding & Decision Rules

Built from Jay Schwedelson (subject-line/send-time data), Chad White (lifecycle), Val Geisler (behavior branching), Laura Atkins (deliverability), Andre Chaperon (sequences), Laura Belgray (voice), Kath Pay (journey). Full research: practitioner-intelligence/syntheses/email.md, messaging.md.

- **Subject + preview are one two-line ad** (Schwedelson — EMPIRICAL, T2): time-commitment framing in subject/preheader +28% opens / +19% preheader; off-hour sends ~+15% opens; never on the hour.
- **Stage-appropriate copy beats promo-everything** (White lifecycle; Geisler — FRAMEWORK, T1): branch content on activation state — "don't serve dessert to someone still on the appetizer."
- **Deliverability is reputation from recipient behavior** (Atkins — FACT/EMPIRICAL): honest subjects, consent, complaint control; clickbait subjects decay the list.
- **Human voice wins in the inbox** (Belgray, Geisler — PRINCIPLE, T2): welcome email from a named founder with a story; relatability over polish.
- **Post-MPP opens are directional, not truth** (White — EMPIRICAL, T1): clicks are the primary signal when Apple-Mail mix dominates.

Decision rules:
1. IF subject and preview don't read as one continuous hook THEN rewrite the pair before touching the body (Schwedelson — EMPIRICAL, T2).
2. IF sending to a stale/inactive segment THEN winback → re-permission → prune before more sends (White — FRAMEWORK, T1).
3. IF complaints or spam rate rise THEN cut frequency and re-qualify the list — "more isn't always better" (Atkins vs Geisler — DISAGREEMENT, conditional; Atkins' context is reputation at scale).
4. IF the list is Apple-Mail-heavy THEN optimize clicks and engagement, not opens (White — EMPIRICAL, T1).
5. IF the email's CTA lands on a page with friction THEN fix the after-click experience first — optimizing the email alone is silo optimization (Pay — FRAMEWORK, T2).
6. IF a sequence step assumes progress the subscriber hasn't made THEN branch by behavior, not calendar (Geisler — FRAMEWORK, T1).

## Metrics

- **Clicks + conversions per journey stage** (primary, post-MPP — White, T1); open rate directional only.
- **Spam complaints (<0.3% bulk senders), bounce, unsubscribe per step** (Gmail/Yahoo rules + Atkins — FACT).
- **Reply rate** (voice signal — Belgray/Geisler, HEURISTIC).
- **Timebox**: evaluate sends at 7-14 days; re-measure when list, offer, or authentication changes.

## Sources

1. Jay Schwedelson, subject-line and send-time data | jayschwedelson.com EP63 + MarketingProfs 2024 | tier 2 | 2026-08-14
2. Chad White, lifecycle + re-permissioning | emailmarketingrules.com | tier 1 | 2026-08-14
3. Val Geisler, behavior-branching onboarding | Intercom podcast | tier 2 | 2026-08-14
4. Laura Atkins, deliverability/reputation | wordtothewise.com + stripo interview | tier 1 | 2026-08-14
5. Andre Chaperon, sequence structure/open loops | via messaging.md | tier 2 | 2026-08-14
6. Laura Belgray, voice-led email | talking-shrimp.com | tier 2 | 2026-08-14

## Evaluation & QA

### Common Failure Modes
- Subject and preview written in isolation — the pair should read as one continuous hook
- Every email a sales email — lifecycle stages get promo copy instead of stage-appropriate help
- Multiple competing CTAs
- Subject promises what the body doesn't deliver (clickbait → spam complaints, unsubscribes)
- Writing to "all subscribers" instead of a segment with a known state
- Ignoring plain-text and mobile rendering until after send
