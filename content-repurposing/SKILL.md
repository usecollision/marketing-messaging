---
name: content-repurposing
category: content
description: Turn one long-form asset into many platform-native assets - threads, posts, carousels, and video with a tracking loop back to the source.
triggers:
  - "repurpose content"
  - "content repurposing"
  - "turn blog into social"
  - "1 to N content"
  - "content atomization"
  - "long form to short form"
  - "content recycling"
  - "derivative content"
inputs:
  - source_asset
  - target_platforms
  - brand_voice
  - audience_map
  - performance_data
outputs:
  - asset_map
  - platform_variants
  - repurposing_schedule
  - performance_tracker
related_skills:
  - content-strategy
  - video-scripts
  - thought-leadership
  - case-study-builder
  - brand-voice
  - marketing-channels/content-calendar
  - marketing-channels/linkedin-content
  - marketing-channels/youtube-strategy
required_context:
  - .context/product-marketing.md
allowed_tools: []
version: 1.0.0
---

## When to Use

Invoke when:
- A long-form asset (essay, webinar, podcast, report, talk) performed well or deserves a wider audience
- Publishing frequency is limited by production time, not by ideas
- The team keeps creating new content instead of squeezing existing assets
- Tracking which derivative formats perform, to steer the next repurposing wave

## Workflow

### Step 1: Choose the Source Asset

- Best candidates have — a strong thesis, multiple discrete insights, reusable examples, and evergreen shelf life
- Grade the asset — does it contain 5+ separable claims or stories? (heuristic threshold — fewer, and repurposing yields thin posts)
- Let performance data choose first — an asset that already resonated gets repurposed before an unproven one

**Gate:** Source asset chosen with rationale and 5+ extractable claims listed.

### Step 2: Extract the Atomic Units

- Break the asset into — core claim, supporting points, stories, stats, quotes, frameworks, objections answered
- Label every unit by type (claim, story, proof, framework, question) so format mapping stays consistent
- Apply the standalone test — every unit must make sense without "as mentioned earlier" or slides 2 through 5

**Gate:** Atom list with type labels; every unit passes the standalone test.

### Step 3: Map Units to Platforms

Format-to-unit matching:
- **X / Threads post** — one claim or question, hook first, white space as pacing
- **LinkedIn post** — hook + story + lesson + question; carousels for frameworks and step sequences
- **Thread / LinkedIn article** — a sequence of related units with connective tissue, for the deep-cut version
- **Short video** — one story or one claim with visual proof (script via video-scripts)
- **Newsletter / email** — the expanded version of the single highest-value unit
- **Image carousel** — steps, lists, before/after, frameworks, and checklists

Mapping rules:
- Match unit type to format — story to video or post, framework to carousel, stat to visual
- Reformat, never repost — the same unit becomes different content on each platform
- One unit can seed many formats; a format without a matching unit should be skipped, not forced

**Gate:** Unit-to-platform map covering every extractable unit, with no forced mismatches.

### Step 4: Write Platform-Native Variants

- Rewrite per platform — each has its own rhythm, conventions, and hook patterns; copy-paste reads as copy-paste
- Platform formatting — line breaks as pacing on X and LinkedIn, on-screen text for video, legible slides for carousels
- Hooks per platform — open loop for video, direct claim for feed posts, question for engagement formats
- Keep voice consistent (brand-voice) — the format changes, the voice does not

**Gate:** Variants drafted; each reads native to its platform when spoken aloud.

### Step 5: Schedule the Repurposing Wave

- Sequence the wave — long-form publishes first, then derivatives spread over days to weeks: summary/thread first, then stories, then framework posts, then video
- Do not flood one platform in a single day — space same-topic variants across surfaces and time (heuristic — same platform sees a given idea at most once every 48-72 hours)
- Flag evergreen units in the content calendar for recycling in later months
- Align the wave with the publishing calendar (content-calendar) instead of stacking against it

**Gate:** Schedule set with spacing rules; evergreen units flagged for reuse.

### Step 6: Track and Feed Back

- Tag every variant to its source asset (UTM or internal label) so performance rolls up to the atom, not just the post
- Weekly read — which units outperform? A unit that wins in one format gets remade in the others
- Update the source asset when variants reveal a sharper framing — repurposing is research
- Cut losers, double down on the top-performing fifth of units (heuristic — treat as a starting allocation, not law)
- Record the mapping in the performance tracker so the next wave starts from data, not memory

**Gate:** Tracking labels in place; weekly review cadence defined; tracker updated with the current wave.

## Evaluation & QA

### Common Failure Modes

- Copy-paste reposts that ignore platform conventions and die in the feed
- Extracting quotes instead of ideas — trivia repurposed as content
- Units that depend on the source asset's context and make no sense standalone
- Flooding every platform with the same idea within 24 hours
- Repurposing everything indiscriminately instead of only what performed or is evergreen
- No tracking from variant back to source atom, so nothing about the wave is learnable
- Forcing every unit into every format, producing filler for platforms the audience ignores
