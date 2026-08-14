---
name: value-proposition
category: strategy
description: Design a JTBD-based value proposition - quantified outcomes, uniqueness, and a defensible USP statement.
triggers:
  - "value proposition"
  - "value prop"
  - "USP"
  - "why should customers choose us"
  - "unique selling point"
  - "differentiation"
inputs:
  - customer_language_bank
  - icp
  - competitive_landscape
  - product_features
outputs:
  - value_prop_statement
  - value_prop_variants
  - outcome_quantifications
  - uniqueness_map
related_skills:
  - messaging-hierarchy
  - customer-language-bank
  - objection-handling
  - marketing-intelligence/positioning-framework
  - marketing-intelligence/icp-builder
  - marketing-intelligence/competitor-audit
required_context:
  - .context/product-marketing.md
allowed_tools: []
version: 1.0.0
---

## When to Use

Invoke when:
- Copy keeps defaulting to feature lists instead of outcomes
- Competitors make the same claims you do
- Pricing or packaging changes demand a fresh articulation of value
- Sales asks "what do I say when they ask why not the cheap option"
- A new segment or new product needs a value prop from scratch

## Workflow

### Step 1: Extract the JTBD

From research (customer language bank, interviews, review mining):
- **Job:** What functional progress is the customer hiring the product for? ("When... I want to... so I can...")
- **Pains:** Friction, risk, and cost in the current way of doing the job
- **Gains:** Outcomes they expect and would be delighted by
- **Success criteria:** How the customer themselves defines "it worked"

Write one sentence per element in the customer's own words, not product terms.

**Gate:** One job statement, 5+ pains, 5+ gains, and a customer-worded success criterion.

### Step 2: Quantify the Outcome

Value is the delta between before and after. For the top 3-5 pains/gains:
- **Before:** the cost of the status quo (time spent, money, errors, delay) — label estimates as estimates
- **After:** the measured or expected result with your product
- **Delta:** the difference, expressed as a number, percentage, or timeframe
- **Evidence strength:** observed (customer-reported), estimated (informed assumption), or aspirational (goal)

Prefer customer-reported numbers; never present an estimated figure as measured. Where no number exists, use a concrete before/after scenario instead of a fake metric.

**Gate:** Top 3 outcomes quantified with a delta and an evidence-strength label each.

### Step 3: Map Uniqueness

Run the three-way uniqueness check:
1. **Vs. direct competitors** — which claims do they also make (table stakes) and which can only you make?
2. **Vs. alternative categories** — spreadsheets, agencies, DIY, doing nothing. Why do customers stay with those?
3. **Vs. status quo and substitutes** — what inertia keeps them from switching at all?

For each candidate differentiator apply the "only" test: can you honestly write "the only [category] that [claim]"? If no competitor could copy it in one sentence and it is provable, it is a candidate USP.

**Gate:** Table-stakes vs. owned claims separated; 2-3 candidates pass the "only" test.

### Step 4: Draft the Value Prop Statement

Write the core statement using this formula:

**For [ICP] who [struggle with pain], [product] is a [category] that [outcome + quantified delta] — unlike [alternatives], [unique mechanism/proof].**

Then produce three derived variants:
- **Full version** — 2-3 sentences, for sales pages and decks
- **One-liner** — under 20 words, for homepage heroes and bios
- **Five-word version** — for nav bars, meta titles, pitch intros

Keep the language 80% customer vocabulary from Step 1.

**Gate:** Core statement plus 3 variants, each passing the "would the customer say this?" read-aloud test.

### Step 5: Stress-Test Against Five Questions

1. **Credible** — would a skeptic believe the quantified delta?
2. **Specific** — is there a concrete claim, or is it generic?
3. **Differentiated** — could a competitor paste their name in and use it?
4. **Customer language** — is this how buyers talk, or how marketers talk?
5. **Provable** — what evidence stands behind each clause (metric, testimonial, demo)?

Fail any question → return to the relevant step, not to word-smithing.

**Gate:** All 5 questions pass; every clause mapped to a proof source.

### Step 6: Attach Proof

For each claim in the final statement, attach the evidence (case study metric, customer quote, benchmark) and note where the gap is if no proof exists yet — unproven claims go to the product/customer team as a to-do, not into paid copy.

**Gate:** Proof map complete with gaps flagged as follow-ups.

## Practitioner Grounding & Decision Rules

Built from Bob Moesta/Clayton Christensen (JTBD), Tony Ulwick (outcome-driven), April Dunford (value elements), Marty Neumeier (onlyness), Hiten Shah (customer language), Joanna Wiebe (quantified outcomes). Full research: practitioner-intelligence/syntheses/research.md, positioning.md, messaging.md.

- **Value = quantified delta between before and after** (Wiebe/Dunford — FRAMEWORK, T1): the delta, expressed as number/percentage/timeframe, with an evidence-strength label (observed/estimated/aspirational).
- **JTBD framing in the customer's words** (Moesta/Christensen — FRAMEWORK, T1): job → pains → gains → success criteria; never product terms.
- **Story-first vs outcome-first JTBD** (Moesta vs Ulwick — DISAGREEMENT, conditional): story/timeline reconstruction for emotional/rare purchases; strict outcome statements for operational, measurable jobs. Both reject feature-wishlist research.
- **Differentiation = the "only" test** (Neumeier/Dunford — FRAMEWORK, T1): if a competitor could claim it, it's table stakes; provable uniqueness wins.
- **80% customer vocabulary** (Shah/Wiebe — FRAMEWORK, T1): "use their words for copy."

Decision rules:
1. IF no customer language exists THEN run customer research first — a value prop written from internal opinion is fiction (Wiebe/Shah — FRAMEWORK, T1).
2. IF a competitor could paste their name into the claim THEN treat it as table stakes, not differentiation (Neumeier "only" test — FRAMEWORK, T1).
3. IF a quantified claim is estimated THEN label it estimated or drop it — never present estimates as measured (skill standard — HEURISTIC).
4. IF the purchase is emotional or rare THEN reconstruct the switch story (timeline, forces); IF the job is operational THEN use outcome statements with the customer's success criteria (Moesta vs Ulwick — DISAGREEMENT, conditional).
5. IF the statement fails "would the customer say this?" THEN rewrite in customer words (Shah — FRAMEWORK, T1).
6. IF no proof exists for a clause THEN the clause is a to-do, not a value prop — route to product/customer teams (skill standard — HEURISTIC).

## Metrics

- **Proof coverage**: % of value-prop clauses with attached evidence (target 100% — Dunford evidence-first, T1).
- **Customer-language share**: % of statement vocabulary traceable to the language bank (Shah — FRAMEWORK, T1).
- **"Only" claim count**: number of provable uniqueness claims vs table stakes (Neumeier — FRAMEWORK, T1).
- **Timebox**: re-validate at pricing/packaging changes, new segments, or major competitor moves.

## Sources

1. Bob Moesta/Clayton Christensen, JTBD switch interviews | jobstobedone.org | tier 1 | 2026-08-15
2. Tony Ulwick, outcome-driven innovation | agiledata.io interview | tier 2 | 2026-08-15
3. April Dunford, value elements + evidence-first | via positioning.md | tier 1 | 2026-08-14
4. Marty Neumeier, onlyness | via positioning.md | tier 1 | 2026-08-14
5. Hiten Shah, PMF-language for copy | via positioning.md | tier 1 | 2026-08-14
6. Joanna Wiebe, quantified outcomes + five-second test | copyhackers.com | tier 1 | 2026-08-14

## Evaluation & QA

### Common Failure Modes
- Feature lists disguised as value props ("fast, easy, secure")
- Quantified claims without labels — estimates presented as measurements
- Differentiation claims any competitor can also make ("we care about customers")
- Value prop written in marketing speak, disconnected from the language bank
- Multiple value props instead of one — test which statement survives deletion
- Claiming the category instead of the delta ("CRM for startups" vs. "close 30% more demos")
