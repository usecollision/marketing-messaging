---
name: localization
category: copy
description: Adapt marketing copy for new markets - cultural adaptation over translation, market-specific value props, idioms, local proof, and review workflow.
triggers:
  - "localize copy"
  - "localization"
  - "translate marketing"
  - "new market copy"
  - "cultural adaptation"
  - "market-specific value prop"
  - "transcreation"
  - "launch in new country"
inputs:
  - source_copy
  - target_market
  - market_research
  - brand_voice
  - local_proof
outputs:
  - localization_brief
  - adapted_copy
  - term_glossary
  - review_checklist
related_skills:
  - brand-voice
  - value-proposition
  - messaging-hierarchy
  - customer-language-bank
  - conversion-copywriting
  - marketing-intelligence/customer-research
  - marketing-intelligence/personas
required_context:
  - .context/product-marketing.md
allowed_tools: []
version: 1.0.0
---

## When to Use

Invoke when:
- Launching existing marketing into a new market or language
- Copy that translates literally but lands flat, confusing, or offensive
- The value proposition resonates differently in a new market and needs re-prioritization
- Scaling content across regions and needing a repeatable localization workflow

## Workflow

### Step 1: Define the Localization Depth

- Decide per market — translation (words only), localization (words plus cultural adaptation), or transcreation (rewrite for the market)
- Drivers of depth — market maturity, category awareness, differences in buying criteria, campaign budget
- Depth can differ per market within one campaign — a mature market gets translation, a new one gets transcreation

**Gate:** Depth decided per market with rationale recorded.

### Step 2: Research Market-Specific Value Drivers

- Establish what the market already believes about the category and what the local status-quo product is
- Buying criteria and objections differ by market — mine local reviews, forums, and competitor messaging (customer-research, personas)
- Re-run the value-prop analysis per market (value-proposition) — the same outcome can rank differently across markets
- Note regulatory and norm differences that constrain claims, before writing anything

**Gate:** Local value-driver list with evidence; differences from the home market flagged explicitly.

### Step 3: Adapt the Message, Not Just the Words

- Keep the brand promise and voice (brand-voice); change emphasis, proof, and framing
- Replace home-market examples with local equivalents — currencies, prices, tools, competitors, names, cultural references
- Idioms and humor — translate meaning, not words; if a joke needs a footnote, cut it. Humor transfers poorly across cultures as a rule (heuristic — err toward clarity)
- Recalibrate tone where norms differ — directness versus indirectness, formality versus casual, deference to authority versus flat structure
- Preserve the core claim — if the claim itself does not survive the market, the problem is the value prop, not the copy

**Gate:** Adapted copy per surface; every home-market example replaced or consciously justified.

### Step 4: Localize Proof and Numbers

- Case studies and testimonials — swap in local customers where available; otherwise add context (industry, scale, outcome) so foreign proof still persuades
- Convert units, currencies, date formats, time zones, phone formats, and measurement systems
- Localize social-proof markers — logos, awards, certifications, and review platforms that carry weight in the market
- Replace home-market benchmarks in stats with local equivalents, or drop the stat — a number that means nothing reads as filler

**Gate:** Every number and proof element localized or consciously retained with rationale.

### Step 5: Run the Review Loop

- Two-reviewer model — a native copywriter for style and register, and an in-market subject-matter expert for meaning and cultural risk
- Back-translation check for high-risk copy — legal, medical, financial, and safety claims
- Brand-voice check — localization bends tone, it does not break the voice
- Maintain a term glossary so recurring terminology stays consistent across assets and campaigns
- Record decisions — which idioms were cut, which examples were swapped, and why, so the next round does not re-litigate them

**Gate:** Review checklist signed off by both reviewer roles; glossary updated; decisions logged.

### Step 6: Maintain and Iterate

- Track localized asset performance against the home-market baseline, not in isolation — a gap is a signal, not a verdict
- Feed local comments, support tickets, and sales objections into a per-market language bank (customer-language-bank)
- Re-localize when the home-market message shifts, not on a fixed calendar
- Re-audit when market context shifts — new competitor entry, regulatory change, category maturity

**Gate:** Per-market tracking in place; feedback loop defined; re-localization triggers listed.

## Evaluation & QA

### Common Failure Modes

- Literal translation that reads like a foreign ad and quietly kills trust
- One value prop for every market, ignoring local buying criteria
- Home-market idioms, humor, and cultural references that baffle or offend
- Foreign case studies, currencies, and units left inside local ads
- No native review, so register errors and cultural risks ship unnoticed
- Translating the brand voice away entirely — localization is adaptation, not reinvention
- Translating assets in bulk without per-market depth decisions, wasting budget on markets that needed transcreation
- Ignoring local legal and claim constraints until a regulator notices
