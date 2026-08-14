---
name: ad-copy
category: copy
description: Write paid media ad copy for Meta, Google, LinkedIn, and TikTok - platform constraints, headline formulas, primary text, CTAs, and funnel-stage variants.
triggers:
  - "ad copy"
  - "paid social copy"
  - "search ad copy"
  - "ad headline"
  - "ad primary text"
  - "meta ad copy"
  - "google ads copy"
  - "tiktok ad copy"
inputs:
  - audience_segment
  - offer
  - platform
  - funnel_stage
  - customer_language
  - creative_angle
outputs:
  - ad_variants
  - headline_set
  - primary_text
  - cta_options
  - compliance_notes
related_skills:
  - conversion-copywriting
  - customer-language-bank
  - messaging-hierarchy
  - value-proposition
  - objection-handling
  - brand-voice
  - marketing-paid/meta-ads
  - marketing-paid/google-ads
  - marketing-paid/hook-frameworks
  - marketing-optimize/ab-testing
required_context:
  - .context/product-marketing.md
allowed_tools: []
version: 1.0.0
---

## When to Use

Invoke when:
- Writing copy for paid campaigns on Meta, Google, LinkedIn, TikTok, or other ad platforms
- Existing ads have healthy CTR but weak conversion, or the reverse — copy and offer are out of sync
- Preparing a campaign and needing platform-native variants derived from one message
- Testing angles and needing a structured batch of variants that isolate one variable at a time

## Workflow

### Step 1: Lock Platform, Funnel Stage, and Single Goal

- **Platform determines constraints, not just format.** A Meta feed ad, a Google RSA, and a TikTok spark ad are different mediums with different reading behavior.
- **Funnel stage** — awareness (attention + relevance), consideration (differentiation + proof), conversion (offer + risk reversal). Stage dictates how direct the ask can be.
- **Single goal per ad set** — clicks, leads, purchases, engagement. One goal per variant set; copy that serves two goals serves neither.

Platform truncation thresholds to design around (platform specs as of writing — re-verify current limits before finalizing):
- Meta Feed — primary text truncates around 125 characters; headline ~40; link description ~30. The first line of primary text is the visible hook.
- Google RSA — up to 15 headlines at 30 characters; 4 descriptions at 90 characters. The system mixes and matches, so every combination must read standalone.
- LinkedIn — intro text truncates around 150 characters on desktop feed; headline ~70; description ~100. Professional register expected.
- TikTok — the on-screen text overlay carries the message; caption is secondary. The hook must land in the first 1-2 seconds, spoken and overlaid.

**Gate:** Platform, funnel stage, single goal, and current character limits recorded in the brief.

### Step 2: Mine the Inputs

- Pull exact customer phrases from research (customer-language-bank) — the hook should sound like the audience, not the brand
- Pull the message hierarchy (messaging-hierarchy) — which pillar and proof points lead for this audience
- Pull objections (objection-handling) — the top objection gets pre-handled in consideration and conversion stage ads
- Record the offer in one sentence: what, for whom, why now
- Scan competing ads in the same placement so the angle is not the fourth copy of the same claim

**Gate:** Hook angle chosen with rationale; customer phrases, pillar, and offer sentence written into the brief.

### Step 3: Write Headlines First

Headline formulas (mix and match, one idea per headline):
- Outcome — "Get [result] in [timeframe]"
- Problem — "[Pain]? There is a better way"
- Mechanism — "The [differentiated] way to [job]"
- Question — "Still [doing it the hard way]?"
- Proof — "[N] teams [outcome] with [product]"
- Contrarian — "Stop [common advice]. Do this instead."

Rules:
- Specific over clever; jargon kills headlines in cold feeds
- Write 10-15 candidates per angle, keep the best 5
- RSA-specific — every headline must pair sensibly with every description, since the system assembles them
- Test whether the headline survives without the image — strong creative can rescue a weak line, but copy should not rely on it

**Gate:** 10+ headline candidates per angle, each tagged with formula and source pillar.

### Step 4: Write Primary Text

Feed-ad structure:
- **Line 1 hook** — the customer's problem in their words, or the boldest defensible claim. Earns the "see more" tap.
- **Middle** — mechanism + proof in 2-3 lines. One proof point, not a list.
- **CTA line** — what to do next, one verb.

Search-ad structure differs: headline = claim + keyword; description = proof + CTA; both must survive mix-and-match assembly.

Length rules:
- Say the whole message inside the hook window; do not pad to the character limit
- Cut after the message is complete — truncation is a feature, not a failure
- One idea per ad; a second idea belongs in a second variant

**Gate:** Primary text passes the scroll test — the hook alone communicates the ad's point, and no line can be cut without losing meaning.

### Step 5: Design CTAs

- CTAs name the action and the payoff — "Get the checklist", "Start free trial", "Book a demo" — not "Learn more"
- Match CTA to funnel stage — learn/download for awareness, compare/see-how for consideration, buy/start for conversion
- Cold audiences get low-friction CTAs; warm audiences can carry direct asks
- Keep CTA and landing page promise identical — the click must not cross a gap

**Gate:** One CTA per funnel stage recorded, with friction level justified by audience temperature.

### Step 6: Build the Variant Matrix

- Change exactly one variable per variant — hook, angle, CTA, or format
- A standard starting grid is 3 angles x 2 hooks x 2 CTAs, trimmed to budget (heuristic — treat as a starting point, not a rule)
- Label every variant with the variable it isolates, so the results are learnable
- Testing principles — let volume accrue before judging (do not kill on early hunches), never test a variable you would not act on, and iterate the winner instead of restarting from zero

**Gate:** Variant matrix written; every variant isolated to one changed variable and labeled.

### Step 7: QA Against Platform Rules and Voice

- Platform compliance — no personal-attribute targeting claims, no misleading or unverifiable claims, required disclosures present
- Voice check against brand-voice — an ad that wins clicks but breaks voice is a brand tax
- Claims trace to the proof bank — no fabricated numbers, ever
- Read aloud for rhythm — ad copy is heard, not just read

**Gate:** Compliance and voice checklist passed; every claim traces to recorded proof.

## Practitioner Grounding & Decision Rules

Built from Eugene Schwartz (sophistication/awareness), Dara Denney (creative testing), Claude Hopkins (test-measure-refine), Joanna Wiebe (customer language). Full research: practitioner-intelligence/syntheses/messaging.md, paid-longtail.md, messaging-longtail.md.

- **Awareness level sets the entry point** (Schwartz — FRAMEWORK, T1): cold traffic needs problem-aware entry; warm/retargeting gets offer/close entry.
- **Market sophistication sets the claim type** (Schwartz — FRAMEWORK, T1): stage 3+ markets (competitors claim the same outcomes) require mechanism/proof, not direct outcome claims.
- **Test creatives, not audiences** (Dara Denney — EMPIRICAL, T2): creative is the highest-leverage paid variable; audiences are platform-managed.
- **Learn on statics, scale on video** (Denney — HEURISTIC, T2): statics give cheap messaging learnings; winners move into video.
- **One variable per variant** (Hopkins/Denney — EMPIRICAL, T1): change exactly one thing so results are learnable; let volume accrue before judging.

Decision rules:
1. IF the market is sophistication stage 3+ THEN lead with mechanism/proof, not outcome claims (Schwartz — FRAMEWORK, T1).
2. IF the audience is cold THEN use a low-friction CTA and problem-entry; IF warm THEN a direct ask is safe (Schwartz — FRAMEWORK, T1).
3. IF monthly budget is $5k-30k THEN test 1-3 new creatives per week in one consolidated campaign, capping total creatives near 10 (Denney — EMPIRICAL, T2).
4. IF an ad is winning THEN iterate the winner 10 ways before testing brand-new concepts (Denney — HEURISTIC, T2).
5. IF a hook or claim would not survive without the image/creative THEN rewrite — neither element should carry the other (skill standard + Denney — HEURISTIC, T2).
6. IF a variant changes more than one variable THEN split it — results are unlearnable (Hopkins — EMPIRICAL, T1).

## Metrics

- **CPA/ROAS per creative variant** (primary — Denney/Hopkins); CTR is directional, not the verdict.
- **3-second hook retention for video ads** (Denney + retention data — EMPIRICAL, T2).
- **Iteration ratio**: winners iterated (target ≥10 iterations per winning creative — Denney, HEURISTIC).
- **Timebox**: don't kill on early hunches; let volume accrue to statistical meaning (Hopkins TMR — EMPIRICAL, T1); re-measure on offer or audience changes.

## Sources

1. Eugene Schwartz, *Breakthrough Advertising* (sophistication, awareness) | tier 2 (secondary on canonical) | 2026-08-14
2. Dara Denney, creative testing frameworks | scribd notes + Motion series + YouTube | tier 2 | 2026-08-15
3. Claude Hopkins, *Scientific Advertising* (test-measure-refine) | analyticstrategy.com | tier 1 | 2026-08-14
4. Joanna Wiebe, customer-language copy | copyhackers.com | tier 1 | 2026-08-14
5. Platform truncation specs (Meta/Google/LinkedIn/TikTok) | platform docs — re-verify at use | tier 1 | 2026-08-15

## Evaluation & QA

### Common Failure Modes

- Writing one "universal" ad and resizing it — platforms reward native formats and punish ported ones
- Hook buried after pleasantries, wasting the truncation window
- RSA headline sets that repeat one idea in different words instead of covering angles
- CTA mismatch with funnel stage — asking cold traffic to book a demo
- Changing multiple variables per variant, so nothing is learnable
- Padding to the character limit instead of cutting
- Copy that depends on the creative to make sense — neither element should carry the other
