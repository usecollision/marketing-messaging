---
name: brand-voice
category: voice
description: Define brand voice and tone from customer language and founder voice, producing a voice guide teams can actually write with.
triggers:
  - "brand voice"
  - "tone of voice"
  - "voice guide"
  - "our copy sounds generic"
  - "inconsistent copy"
  - "founder voice"
  - "how should we sound"
inputs:
  - customer_language_bank
  - founder_writing_samples
  - positioning
  - audience_segments
outputs:
  - voice_guide
  - trait_definitions
  - say_never_say_lexicon
  - rewrite_examples
related_skills:
  - customer-language-bank
  - messaging-hierarchy
  - conversion-copywriting
  - email-copy
  - marketing-intelligence/customer-interviews
  - marketing-intelligence/review-mining
required_context:
  - .context/product-marketing.md
allowed_tools: []
version: 1.0.0
---

## When to Use

Invoke when:
- No voice guide exists and copy sounds different across pages, emails, and ads
- Copy is grammatically correct but reads like every other competitor
- A founder writes great things personally but the team can't replicate it
- New writers or contractors need onboarding to "how we sound"
- Rebranding, repositioning, or a messaging overhaul is in progress
- Customer research exists but hasn't been converted into how the brand speaks

## Workflow

### Step 1: Gather Voice Evidence

Collect raw material from three sources:

**Customer language** (primary signal):
- The customer language bank — real phrases customers use for pains, outcomes, objections
- Reviews, support tickets, interview transcripts

**Founder voice** (personality signal):
- Founder-written blog posts, newsletters, pitch decks, podcast transcripts
- Support replies or sales emails the founder wrote personally that worked
- Note: what do they say that competitors wouldn't? Which opinions, metaphors, rhythm?

**Constraint signals:**
- Category expectations (legal/finance = formal floor; developer tools = direct)
- The positioning document — what the brand claims to be

Compile 10-20 snippets per source with a note on what each one reveals.

**Gate:** Evidence file has 10+ customer snippets and 10+ founder snippets, each annotated with the trait it suggests.

### Step 2: Choose 3-4 Voice Traits

From the evidence, pick at most four traits. For each trait:
- **Name it concretely** — "plainspoken" beats "authentic"; "cheerfully direct" beats "friendly"
- **Define it** — what it means in practice, in one sentence
- **How to do it** — 3 concrete writing behaviors (contractions, second person, short paragraphs)
- **How not to do it** — 2 behaviors to avoid (e.g., never sarcastic at a customer's expense)
- **Evidence** — the snippets that inspired it

Trait menu (heuristic, from common brand-voice systems): clever, plainspoken, confident, warm, direct, playful, provocative, precise, optimistic, irreverent. Pick what the evidence supports — never "all of them."

**Gate:** 3-4 named traits, each with definition, do/avoid behaviors, and supporting evidence.

### Step 3: Define Tone Ranges

Voice is constant; tone shifts with situation. For each trait, define the range with anchor points:

| Situation | Trait adjustment | Example |
|---|---|---|
| Success/celebration | Playful +1 | "That's the whole point." |
| Error/outage | Playful 0, Direct +2 | "We broke it. Here's what happens next." |
| Billing/apology | Warm +1, Confident -1 | Plain words, no defensiveness |
| Technical docs | Direct +1, Clever -1 | Clarity over charm |

Also define "never" situations: where the brand will not joke or be casual (churned customer, security incident, legal notices).

**Gate:** At least 5 situations mapped with trait adjustments and one example line each.

### Step 4: Write the Voice Guide

Assemble the artifact. Minimum sections:
1. **Voice summary** — 2-3 sentences plus the 3-4 traits with definitions
2. **Before/after rewrites** — 5+ real lines rewritten from generic to on-voice (headline, CTA, error message, email subject, feature description)
3. **Say / Never-say lexicon** — banned words (jargon, weasel words, competitor cliches) and preferred replacements, drawn from customer language
4. **Grammar & syntax rules** — sentence length, contractions, questions allowed, em-dash/ellipsis policy
5. **Example pieces** — one short fully on-voice sample (email, hero, or ad) with annotations

Keep the guide under 3 pages of content; length kills adoption.

**Gate:** Guide contains all 5 sections and every rule traces back to evidence from Step 1.

### Step 5: Pressure-Test and Roll Out

- Rewrite 3 existing assets (homepage hero, one email, one ad) using the guide
- Read every rewrite aloud — if it doesn't sound like the founder talking to a friend, revise
- Run past the founder: "Would you say this?" not "Do you like this?"
- Create a 10-line editing checklist teams can run in 5 minutes

**Gate:** 3 rewrites approved, checklist attached to the guide, guide committed alongside positioning in the repo.

## Practitioner Grounding & Decision Rules

Built from Ann Handley (*Everybody Writes*), Laura Belgray (Talking Shrimp), Joanna Wiebe (customer language), Hiten Shah (PMF language). Full research: practitioner-intelligence/syntheses/messaging.md, research.md.

- **Voice is HOW, message is WHAT — different layers** (Belgray vs Wiebe — DISAGREEMENT, resolved as layers): research supplies what to say; voice supplies how. Voice is the differentiator in commoditized inboxes/social; message-match is the differentiator in unfamiliar categories.
- **Voice comes from customer language + founder voice, not competitor cloning** (Handley, Belgray — PRINCIPLE, T1/T2): "slightly revise" customer phrases (Wiebe); founders write what competitors wouldn't say.
- **Traits must be concrete** (Handley — HEURISTIC, T1): "plainspoken" beats "authentic"; a trait you can't turn into writing behaviors is decoration.
- **Voice constant, tone shifts with situation** (Handley — FRAMEWORK, T1): errors/apologies get directness, not playfulness.
- **Personality converts in the inbox** (Belgray — OPINION, T2): "people want relatable, not perfect"; polished, personality-free copy reads as spam.

Decision rules:
1. IF copy reads like every other competitor THEN rebuild voice from customer language + founder samples — never from category norms or a competitor's guide (Handley/Belgray — FRAMEWORK, T1).
2. IF a trait can't be defined as 3 concrete writing behaviors THEN rename it until it can (Handley — HEURISTIC, T1).
3. IF the situation is an apology, outage, or security incident THEN drop playfulness and raise directness (Handley tone ranges — HEURISTIC, T1).
4. IF a rewritten line doesn't sound like the founder talking to a friend THEN revise (Belgray — HEURISTIC, T2).
5. IF the voice guide exceeds ~3 pages THEN cut — length kills adoption (Handley — HEURISTIC, T1).
6. IF writing for an unfamiliar category THEN weight message-match (customer language) over personality; IF a commoditized category THEN weight personality (Wiebe/Belgray — DISAGREEMENT, conditional).

## Metrics

- **Voice consistency score**: % of shipped assets that pass the 10-line editing checklist (skill standard — HEURISTIC).
- **Rewrite acceptance**: founder approval on "would you say this?" not "do you like this?" (skill standard — HEURISTIC).
- **Copy performance deltas before/after voice rollout** (directional; voice is a brand tax/asset — HEURISTIC).
- **Timebox**: re-audit the guide at positioning changes or major segment entry; light review every 6 months (Bare Strategy cadence — T2).

## Sources

1. Ann Handley, *Everybody Writes* (simplicity, voice, tone) | tier 1 | 2026-08-14
2. Laura Belgray, Talking Shrimp (voice-led copy) | talking-shrimp.com | tier 2 | 2026-08-14
3. Joanna Wiebe, customer-language copy ("slightly revise") | copyhackers.com | tier 1 | 2026-08-14
4. Hiten Shah, PMF survey language → copy | via positioning.md | tier 1 | 2026-08-14
5. Nicolas Cole, atomic essays/4A framework (voice via frameworks) | ship30for30.com | tier 1 | 2026-08-15

## Evaluation & QA

### Common Failure Modes
- Traits too abstract ("authentic", "human") — nobody can act on them
- Voice cloned from a competitor or category leader instead of evidence
- Customer phrases pasted in without adaptation (grammar errors in headlines)
- Tone fixed at one setting — brand sounds cheerful during an outage
- Guide too long to read, so teams never use it
- Voice chosen to impress marketers, not to sound like the customer's own thinking
