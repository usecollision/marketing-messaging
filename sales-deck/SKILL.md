---
name: sales-deck
category: content
description: Write pitch deck copy slide by slide - problem-solution-proof-CTA narrative, full-sentence headline claims, and speaker notes.
triggers:
  - "sales deck"
  - "pitch deck"
  - "investor deck"
  - "deck copy"
  - "slide by slide"
  - "pitch narrative"
inputs:
  - positioning
  - value_prop
  - proof_assets
  - audience_type
outputs:
  - deck_outline
  - slide_by_slide_copy
  - speaker_notes
related_skills:
  - value-proposition
  - messaging-hierarchy
  - case-study-builder
  - objection-handling
  - brand-voice
  - marketing-intelligence/positioning-framework
required_context:
  - .context/product-marketing.md
allowed_tools: []
version: 1.0.0
---

## When to Use

Invoke when:
- Building a pitch deck for investors, sales prospects, or partners
- An existing deck rambles or buries the ask
- Converting the messaging hierarchy into a narrated, slide-by-slide story
- Sales needs a narrative spine they can customize per prospect

## Workflow

### Step 1: Define Audience and Goal

- **Audience** — investor (risk/reward, market), enterprise buyer (pain/outcome, proof), partner (shared economics), webinar (education + pipeline)
- **Context** — first touch vs. second meeting; deck-only vs. presented live
- **Goal** — the single action after the last slide (book demo, fundraise meeting, pilot agreement)
- **Audience's frame** — what they believe today; where the story must start

Everything downstream changes with audience; an investor narrative is not a sales narrative.

**Gate:** Audience, context, goal, and starting frame written in one paragraph.

### Step 2: Design the Narrative Arc

Default arc: **Problem → Solution → Proof → CTA**, with these flow rules:
- Each slide must earn the next ("so what?" test on every transition)
- State the problem before the product — no solution without a felt problem
- Proof lands where the biggest doubt sits, usually between solution and CTA
- The ask appears exactly once, at the end, as the logical conclusion

Optional arcs: **Problem → Agitate → Solution → Proof → CTA** (sales, high skepticism), **Vision → Problem → Solution → CTA** (conference keynotes), **Story → Insight → Product → CTA** (brand-driven audiences).

**Gate:** Arc chosen with rationale; 8-12 slide skeleton listed with a one-line purpose each.

### Step 3: Write Slide-by-Slide Copy

Write each slide to these rules:

**Headline = a full-sentence claim.** The deck must be readable by headlines alone; body text is evidence, not the message.

Recommended sales structure:

1. **Title** — company + one-line value prop (the five-word version from the hierarchy)
2. **Problem** — the pain in customer language; one stat or quote if you have one
3. **Agitate/Stakes** — the cost of the status quo, quantified or concretely described
4. **Solution** — the mechanism and why now; no feature dump
5. **Product/Demo** — 3 capability clusters max, each tied to a pillar
6. **Proof** — metrics table, named customers, one short case study
7. **Differentiation** — comparison vs. alternatives, honest table
8. **Objection slide(s)** — the top 2 objections from research, pre-handled
9. **Offer/Plan** — options or pricing framing
10. **CTA/Ask** — the single next step, specific and dated

Investor decks swap differentiation/objections for market, business model, traction, team, and financials — same headline rules apply.

**Gate:** Every slide has a full-sentence headline claim; body copy ≤ 50 words per slide (heuristic ceiling).

### Step 4: Write Speaker Notes

- Notes = what you say that the slide can't (context, transition lines, stories)
- One opening line per slide that bridges from the previous slide's last idea
- Data slides: notes carry the interpretation ("this metric matters because...")
- Pre-script the transition into the ask ("which brings us to...")

**Gate:** Speaker notes for every slide with transition lines.

### Step 5: QA the Deck

- [ ] Headline-only read — read all headlines in order; the full story must survive
- [ ] 5-minute dry run — can the narrative be presented in 5 minutes without rushing?
- [ ] One-reader skim — a cold reader can state the problem, solution, and ask after one pass
- [ ] Objection check — the top 3 objections from research are addressed somewhere
- [ ] Consistency check — claims trace to the messaging hierarchy and verified proof (no fabricated numbers)
- [ ] Voice check — reads on-brand when spoken aloud

**Gate:** All checks pass; the headline-only story saved as slide one of the appendix.

## Practitioner Grounding & Decision Rules

Built from Andy Raskin (Greatest Sales Deck), April Dunford (evidence-first), David Perell (surprise structure). Full research: practitioner-intelligence/syntheses/positioning.md, messaging-longtail.md.

- **Raskin's 5 elements** (Raskin — FRAMEWORK, T1): 1) big change in the world, 2) land on the positive side (Promised Land), 3) the journey — why now, 4) the as/if — proof the change is real, 5) the new narrative — everyone tells the story. The deck is a story, not a spec.
- **Headline = full-sentence claim; deck readable by headlines alone** (Raskin — FRAMEWORK, T1): ≤8 slides to product (Raskin heuristic).
- **Evidence-first when there's no big change** (Dunford vs Raskin — DISAGREEMENT, conditional): a Raskin narrative without a credible big change rings false; stable markets use market-frame + evidence (Dunford).
- **Proof lands at the moment of doubt** (Dunford/Price — FRAMEWORK, T1): between solution and CTA, or where the biggest objection sits.
- **The ask appears once, at the end, as the logical conclusion** (Raskin — HEURISTIC, T1).

Decision rules:
1. IF no credible big change exists in the market THEN don't force the Raskin narrative — lead with competitive frame + evidence (Raskin vs Dunford — DISAGREEMENT, conditional).
2. IF a headline is a label ("Our Solution", "Why Us") THEN rewrite it as a claim (Raskin — FRAMEWORK, T1).
3. IF the product appears before the problem is felt (before ~slide 4-5 in sales) THEN restructure (Raskin — HEURISTIC).
4. IF the ask is missing or appears twice THEN fix it — once, at the end (Raskin — HEURISTIC).
5. IF the headline-only read doesn't tell the full story THEN restructure until it does (Raskin — FRAMEWORK, T1).
6. IF a claim lacks a named proof THEN remove or defer it to the proof slide (Dunford evidence-first — FRAMEWORK, T1).

## Metrics

- **Headline-only story pass** (primary): a cold reader states problem, solution, and ask from headlines alone (Raskin — FRAMEWORK, T1).
- **Slides-to-product count** (Raskin heuristic: ≤8 in sales decks).
- **Ask clarity**: the single next step is specific and dated (Raskin — HEURISTIC).
- **Timebox**: re-audit the deck at positioning changes or when the target audience's frame shifts.

## Sources

1. Andy Raskin, The Greatest Sales Deck I've Ever Seen (5 elements) | via positioning.md | tier 1 | 2026-08-14
2. April Dunford, evidence-first positioning/market frame | via positioning.md | tier 1 | 2026-08-14
3. Momoko Price, proof placement at moment of doubt | kantan.io | tier 2 | 2026-08-14
4. David Perell, surprise-based narrative structure | every.to Superorganizers | tier 1 | 2026-08-15

## Evaluation & QA

### Common Failure Modes
- Feature tour instead of narrative — slides describe the product rather than advance the story
- Headlines that are labels ("Our Solution", "Why Us") instead of claims
- Proof dumped on one slide instead of placed at the moment of doubt
- The ask buried mid-deck or never made explicitly
- Two different decks fighting in one file (sales + investor)
- Bullet walls that nobody reads during a live presentation
