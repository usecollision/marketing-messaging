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

## Evaluation & QA

### Common Failure Modes
- Phrases sanitized into marketing speak during extraction ("dread month-end close" becomes "accounting teams face monthly challenges")
- Vague phrases kept because they're plentiful ("great product")
- Bank built and never used — extraction without an asset to feed
- No source or stage tags, so phrases can't be traced or filtered
- Bank treated as a one-time artifact instead of a living document
