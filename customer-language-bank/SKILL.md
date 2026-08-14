---
name: customer-language-bank
category: research
description: Extract exact customer phrases from interviews and reviews and organize them by stage and pain into a reusable language bank.
triggers:
  - "customer language"
  - "language bank"
  - "voice of customer"
  - "exact phrases customers use"
  - "what words do customers use"
  - "message mining"
inputs:
  - interview_transcripts
  - review_corpus
  - support_tickets
  - survey_responses
outputs:
  - language_bank_doc
  - phrase_catalog
  - stage_pain_matrix
related_skills:
  - brand-voice
  - value-proposition
  - objection-handling
  - marketing-intelligence/customer-research
  - marketing-intelligence/customer-interviews
  - marketing-intelligence/review-mining
required_context:
  - .context/product-marketing.md
allowed_tools: []
version: 1.0.0
---

## When to Use

Invoke when:
- Copy sounds like it was written by a marketer, not a customer
- You have interviews, reviews, or tickets but they aren't organized or reusable
- Writing a value prop, voice guide, or messaging hierarchy needs raw material
- Headlines feel generic because nobody recorded how customers actually talk
- New copywriters keep guessing at customer vocabulary

## Workflow

### Step 1: Gather Sources

Collect every place customers speak unprompted:
- Interview transcripts and call recordings
- Reviews — yours and competitors' (competitor reviews reveal category vocabulary)
- Support tickets, chat logs, sales call notes
- Surveys with open-ended responses, community posts, Reddit threads

Priority order for quality: interviews > support tickets > reviews > surveys > social posts.

**Gate:** Source list with file locations and rough volume per source.

### Step 2: Extract Verbatim Phrases

For each source, pull phrases that meet three tests:
- **Specific** — names a concrete pain, outcome, comparison, or trigger ("I dread month-end close" beats "I'm busy")
- **Emotional** — carries feeling: frustration, relief, pride, fear
- **Self-contained** — makes sense out of context

Rules:
- Keep exact wording including grammar quirks, abbreviations, and odd phrasing — the quirks are the signal
- Don't clean up, don't translate into marketing speak
- Record the source and stage context for each phrase

**Gate:** 50+ extracted phrases (or exhaustive for small corpora), each with source attribution.

### Step 3: Tag Every Phrase

Apply three tags per phrase:
- **Stage** — awareness: unaware / problem-aware / solution-aware / product-aware (which frame the customer is in)
- **Category** — pain, desired outcome, objection, comparison (to competitor or status quo), trigger (what started the search), praise
- **Segment** — which ICP or persona said it, if known

Mark emotion intensity (low/high) — high-intensity phrases are headline candidates.

**Gate:** 100% of phrases tagged with stage, category, and segment.

### Step 4: Organize the Bank

Build the bank as a living document with two indexes:

1. **By stage → category** (the writing index): for each awareness stage, sections for pains, outcomes, objections, comparisons — copywriters pull from here per awareness level
2. **By pain → theme** (the research index): cluster phrases into themes like "setup friction", "reporting depth" with counts, so you can see what customers emphasize most

For each entry keep: verbatim phrase | source | stage | category | segment | intensity.

**Gate:** Both indexes complete; every phrase reachable from at least one index; file committed to the repo.

### Step 5: Put It to Work

Usage rules that keep the bank valuable:
- **Headlines** — rewrite generic headlines by swapping in high-intensity customer phrases
- **Quotes** — only verbatim phrases (with permission) in proof sections
- **Voice** — feed to the voice guide as the primary evidence for how the brand should sound
- **Objection pages** — comparison and objection phrases seed the objection-handling skill
- **Refresh cadence** — append after every interview round or review batch; prune phrases that no longer match the product

**Gate:** Bank cited in at least one real asset (headline, email, or landing section) within the current workstream.

## Practitioner Grounding & Decision Rules

Built from Joanna Wiebe (verbatim customer language), Bob Moesta (their words become copy), Clozd (recording + win/loss discipline), Hiten Shah (PMF language), ziellab (persona fiction warning). Full research: practitioner-intelligence/syntheses/research.md, messaging.md.

- **Verbatim or nothing — quirks are the signal** (Wiebe — FRAMEWORK, T1): "slightly revise" customer phrases; never clean up grammar into marketing speak.
- **Record and transcribe; never paraphrase from memory** (Clozd — EMPIRICAL, T1): note-taking kills follow-up questions and loses exact wording.
- **The bank exists to feed assets** (Wiebe — FRAMEWORK, T1): extraction without a consumer (headline, email, value prop) is premature.
- **Stage-organization matches awareness** (Schwartz/Wiebe — FRAMEWORK, T1): copywriters pull per awareness level; one index organized by stage → category.
- **AI on your transcripts, never as persona oracle** (ziellab — HEURISTIC, T2): AI personas trained on generic internet content are "the same fiction at lower cost."
- **Recruit the full spectrum** (Moesta/Revella — PRINCIPLE, T1): winners AND losers, switchers AND almost-switched — happy customers alone produce survivorship-biased language.

Decision rules:
1. IF a phrase doesn't name a concrete pain, outcome, comparison, or trigger THEN don't bank it (Wiebe — HEURISTIC).
2. IF a phrase is high-emotion AND self-contained THEN tag it as a headline candidate (Wiebe — HEURISTIC).
3. IF there's no asset waiting to consume the phrases THEN defer the extraction or define the asset first (Wiebe — FRAMEWORK, T1).
4. IF mining win/loss for language THEN require ≥20 interviews per segment before trusting themes (Clozd — EMPIRICAL, T1).
5. IF using AI to build personas or language THEN train it on your transcripts and reviews, never on general internet content (ziellab — HEURISTIC, T2).
6. IF a phrase is vague ("great product") THEN discard even if plentiful (skill standard — HEURISTIC).

## Metrics

- **Bank size + tagged coverage**: 100% of phrases tagged (stage/category/segment) (skill standard — HEURISTIC).
- **Usage rate**: % of shipped assets citing bank phrases (target: every headline batch uses ≥1 verbatim phrase — Wiebe, T1).
- **Quote yield**: % of interview content usable verbatim in proof sections (Clozd recording discipline — EMPIRICAL, T1).
- **Timebox**: append after every interview round or review batch; prune phrases that no longer match the product (skill standard).

## Sources

1. Joanna Wiebe, customer-language copy process | copyhackers.com | tier 1 | 2026-08-14
2. Bob Moesta, switch interviews (language → positioning/copy) | jobstobedone.org | tier 1 | 2026-08-15
3. Clozd, win/loss discipline (record, ≥20 interviews) | clozd.com | tier 1 | 2026-08-15
4. Hiten Shah, PMF survey language | via positioning.md | tier 1 | 2026-08-14
5. ziellab, persona-fiction guide (AI personas warning) | via research.md | tier 2 | 2026-08-15

## Evaluation & QA

### Common Failure Modes
- Phrases sanitized into marketing speak during extraction ("dread month-end close" becomes "accounting teams face monthly challenges")
- Vague phrases kept because they're plentiful ("great product")
- Bank built and never used — extraction without an asset to feed
- No source or stage tags, so phrases can't be traced or filtered
- Bank treated as a one-time artifact instead of a living document
