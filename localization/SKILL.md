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

## Practitioner Grounding & Decision Rules

Built from Lokalise (localization workflow + transcreation), Phrase (TMS/orchestration), Transifex (TQI quality gating), documented i18n failure cases (Pepsi, HSBC, P&G Pampers, Schweppes, American Airlines). Full research: practitioner-intelligence/domains/messaging-longtail/localization-vendor-panel.md, transcreation-failure-cases.md; syntheses/messaging-longtail.md.

- **Depth ladder: translation → localization → transcreation** (Lokalise — FRAMEWORK): translation converts words, localization adapts for fit, transcreation rebuilds for the same feeling and action in the new culture.
- **Lock the narrative frame, let each market rewrite the punch line** (Mastercard "Priceless" — EMPIRICAL, T2): 53 languages/112 countries, 80%+ awareness; Snickers: same insight, local slang + casting, +15.9% global sales (~$376M) year one.
- **Literal translation inverts meaning at catastrophic cost** (HSBC "Assume nothing"→"Do nothing" $10M rebrand; Pepsi China "ancestors back from the grave" — EMPIRICAL, T2): 29% of marketers admit a cultural blunder damaged brand reputation (Lokalise survey).
- **Automation is safe when threshold-gated** (Transifex TQI — vendor EMPIRICAL, T3): score strings, auto-approve above threshold, route exceptions to humans; machine/AI translations enter TM only after review (TQI ≥0.95 recommended).
- **Adopt tooling after fixing the process** (Phrase — HEURISTIC, T2): configuring a platform around a broken workflow is the biggest implementation mistake; pilot 1 content type + 2-3 language pairs.

Decision rules:
1. IF a joke/idiom needs a footnote to make sense THEN cut it — humor transfers poorly (Lokalise — HEURISTIC).
2. IF the claim itself doesn't survive the market THEN the problem is the value prop, not the copy — re-run the value prop per market (skill standard — HEURISTIC).
3. IF content is legal/medical/financial/safety THEN back-translation review is mandatory (Lokalise — HEURISTIC).
4. IF scaling continuous releases across locales THEN use TMS with TM + glossary + conditional routing (100% TM match skips humans; MT below threshold; human above) (Phrase/Transifex — FRAMEWORK, T2).
5. IF the asset is brand/emotional (slogans, campaigns) THEN transcreate with a human linguist-copywriter and in-market testing — never bare MT (Lokalise/PoliLingua — FRAMEWORK, T2).
6. IF adopting a localization platform THEN document the current workflow first, then pilot one content type + 2-3 language pairs before full rollout (Phrase — HEURISTIC, T2).

## Metrics

- **Per-market performance vs home baseline** (primary — skill standard): a gap is a signal to re-audit, not a verdict.
- **Quality gate coverage**: % of strings scored (TQI) or reviewed before publish (Transifex/Phrase — T2).
- **TM/glossary adherence**: terminology drift incidents per quarter (vendors — T2).
- **Review sign-off rate**: % of assets passing the two-reviewer loop (native copywriter + in-market SME).
- **Timebox**: re-localize when home messaging shifts, not on a fixed calendar; re-audit on competitor entry or regulatory change.

## Sources

1. Lokalise, Localization Workflow Best Practices | lokalise.com/blog/localization-workflow-best-practices | tier 2 | 2026-08-15
2. Lokalise, Transcreation Examples (Mastercard/Snickers/Stabilo) | lokalise.com/blog/transcreation-examples | tier 2 | 2026-08-15
3. Lokalise, Localization Mistakes survey (29%) | lokalise.com/blog/localization-regrets-and-best-practices | tier 2 | 2026-08-15
4. Phrase platform + implementation guidance | phrase.com + languagesunlimited.com | tier 2 | 2026-08-15
5. Transifex, TQI + translation memory docs | transifex.com + help.transifex.com | tier 2 | 2026-08-15
6. PoliLingua, famous marketing translation fails | polilingua.com | tier 3 | 2026-08-15

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
