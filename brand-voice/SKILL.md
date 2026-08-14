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

## Evaluation & QA

### Common Failure Modes
- Traits too abstract ("authentic", "human") — nobody can act on them
- Voice cloned from a competitor or category leader instead of evidence
- Customer phrases pasted in without adaptation (grammar errors in headlines)
- Tone fixed at one setting — brand sounds cheerful during an outage
- Guide too long to read, so teams never use it
- Voice chosen to impress marketers, not to sound like the customer's own thinking
