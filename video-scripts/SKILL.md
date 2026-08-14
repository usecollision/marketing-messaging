---
name: video-scripts
category: content
description: Write short-form video scripts for ads and organic - hook-retain-payoff structure, retention beats, and platform-fit formatting.
triggers:
  - "video script"
  - "short form video"
  - "tiktok script"
  - "reel script"
  - "ad script"
  - "video hook"
inputs:
  - video_goal
  - platform
  - audience_awareness
  - product_context
outputs:
  - video_script
  - hook_variants
  - retention_beat_map
  - cta_options
related_skills:
  - conversion-copywriting
  - brand-voice
  - case-study-builder
  - marketing-paid/hook-frameworks
  - marketing-paid/ad-creative-generator
  - marketing-channels/youtube-strategy
required_context:
  - .context/product-marketing.md
allowed_tools: []
version: 1.0.0
---

## When to Use

Invoke when:
- Writing scripts for paid social ads (TikTok, Reels, Shorts)
- Writing organic short-form content to grow an account
- Hook ideas feel stale and scroll-past rates are climbing
- Need a repeatable script format a creator or editor can execute

## Workflow

### Step 1: Define the Format Brief

- **Goal** — what the viewer should do (follow, click, book, remember)
- **Platform & placement** — ad vs. organic; feed behavior differs
- **Awareness level** — unaware viewers need the problem stated; product-aware viewers need the offer
- **Length** — target 20-40s for most paid and organic short-form (heuristic); longer only if retention data supports it
- **Creator** — on-camera founder, voice-over + b-roll, or talking head

**Gate:** Brief written; goal and platform stated before any hook is drafted.

### Step 2: Write the Hook (Seconds 0-3)

The hook's only job: stop the scroll. Write 5+ variants using distinct patterns:

- **Cold open** — start mid-action/mid-sentence, no intro ("So we deleted our onboarding flow. Signups went up.")
- **Contrarian** — challenge a belief the audience holds ("Your customers don't want better features")
- **Question** — a real, hard customer question ("Why does your churn spike every March?")
- **Pattern interrupt** — visual or verbal mismatch ("I'm a founder and I have one piece of advice: stop talking")
- **POV/roleplay** — put the viewer in the scene ("It's Monday. Your demo just no-showed.")
- **Open loop with stakes** — tease a reveal with a cost ("The pricing mistake that cost us $40k" — only with a true number)

Rules: the first 3 words are the most important words in the script; the hook must deliver on its promise by the payoff; no "Hey guys, welcome back."

**Gate:** 5+ hook variants from 3+ patterns; each passes the "would this stop a stranger mid-scroll?" test.

### Step 3: Build Retention Beats

Map the middle as beats, not paragraphs:

- **Open loop** — pose a question or tension the payoff will resolve
- **Beat structure** — one idea per 3-5 seconds; a pattern break (visual change, cut, question, on-screen text change, tone shift) at every beat boundary
- **Raise stakes or escalate** — each beat should increase specificity or tension, not repeat
- **B-roll/visual notes** — note what changes on screen at each beat (a static talking head is a retention killer — heuristic, not a rule)

For awareness levels: problem-aware viewers get agitate-then-hope beats; solution-aware get before/after/bridge; product-aware get proof and offer beats.

**Gate:** Beat map with 3-5s segments, each with a scripted pattern break.

### Step 4: Write the Payoff and CTA

- **Payoff** — resolve the open loop with the specific insight, result, or lesson; tie it to a value prop or pillar (not a feature list)
- **CTA** — one ask, matched to goal: follow (organic), click/book (ads), remember (brand)
- **Loop logic** — end with a line that invites a replay or part two ("comment the metric you'd fix first" — engagement CTAs on organic only)
- The last line should be as quotable as the first

**Gate:** Payoff resolves the hook's loop; single CTA matched to the goal.

### Step 5: Format the Script

Use a 4-column script format:

| Time | Visual / B-roll | Spoken (VO/on-camera) | On-screen text |

Rules:
- Spoken word pace: ~2.5 words per second is a safe drafting heuristic (~150 wpm); a 30s script lands around 70-80 spoken words
- On-screen text carries the claim or the number; never duplicate the voiceover word-for-word
- Captions assumed (most watch muted) — the story must survive mute-only
- Mark where music/beat drops and where cuts happen

**Gate:** Script in 4-column format with timed beats; story is coherent mute-only.

### Step 6: QA and Variants

- [ ] Read aloud against the timer — does it land in the target length?
- [ ] Retention map — replay the beat map; any 5s stretch without a change gets rewritten
- [ ] Hook/payoff link — the payoff genuinely resolves the hook's promise
- [ ] Voice check — matches the brand voice guide when spoken
- [ ] Variant plan — produce 2-3 hook variants of the same body for testing (test hooks before rewriting bodies)
- [ ] Compliance — no fabricated stats, no stolen footage, licensed music noted

**Gate:** All checks pass; 2+ hook variants ready for testing.

## Practitioner Grounding & Decision Rules

Built from Dara Denney (creative testing), Billo/ClipSpeed/Postigniter/Opus retention data (1.5s hook), Eugene Schwartz (awareness), Laura Belgray (voice). Full research: practitioner-intelligence/domains/messaging-longtail/dara-denney.md, short-form-hook-retention.md; syntheses/messaging.md.

- **The hook window is 1.5-3 seconds** (retention data — EMPIRICAL, T2): the stay-or-scroll decision happens in 0.3-0.8s; 50-70% of leavers exit in the first 1-2 seconds; improving 1s retention 50%→70% doubles the audience.
- **Layered hooks beat single-element** (Postigniter/Hootsuite — EMPIRICAL, T2): visual + auditory + text ~3x the 3-second hold; 60%+ of mobile views are sound-off, so text must carry the claim.
- **Core message in the first 3 seconds ≈ +60% total retention** (Billo — EMPIRICAL, T2); nearly half of viewers past 3s watch the full 30s.
- **Retention beats: one pattern break every 2-4 seconds** (Opus — EMPIRICAL, T2); high-performing Shorts average a cut every 2-4s.
- **Test creatives, not audiences; iterate winners** (Denney — EMPIRICAL, T2): 2-3 hook variants of one body, read the 3s retention as the score.
- **Conversational hooks read as authentic** (Denney — HEURISTIC, T2): "No because...", "Wait why is this..." take a second to process — viewers don't scroll past instantly.

Decision rules:
1. IF the first frame contains setup, logo, or dead air THEN cut it — that's where the steepest drop lives (retention data — EMPIRICAL, T2).
2. IF the video may be watched muted THEN every claim must survive as on-screen text (sound-off dominance — EMPIRICAL, T2).
3. IF any 5-second stretch has no pattern break (cut, text change, tone shift) THEN rewrite that beat (Opus — EMPIRICAL, T2).
4. IF the payoff doesn't resolve the hook's promise THEN cut the curiosity — both viewers and algorithms penalize mismatch (Billo — EMPIRICAL, T2).
5. IF testing paid video THEN produce 2-3 hook variants of one body and test hooks before rewriting bodies (Denney — HEURISTIC, T2).
6. IF platform is TikTok THEN the hook must land in ~1s; IF YouTube Shorts THEN ~1.5-2s is available; IF Reels THEN lead with the visual (ClipSpeed — EMPIRICAL, T2).

## Metrics

- **1-second / 3-second retention rate** (primary — platform analytics; EMPIRICAL, T2): the score for hook quality.
- **Completion rate + watch-through %** (retention curve shape, not just average).
- **Hook variant win rate** per test batch (Denney — HEURISTIC, T2).
- **Timebox**: judge a hook variant on platform retention data within its learning window; re-measure when the feed algorithm or format shifts.

## Sources

1. Dara Denney, creative testing + hooks | YouTube / scribd notes | tier 2 | 2026-08-15
2. Billo TikTok ad performance review | via reelzila Medium | tier 3 | 2026-08-15
3. ClipSpeed, first-second retention analysis | clipspeed.ai | tier 3 | 2026-08-15
4. Postigniter, hook formulas from 10,000+ Shorts | postigniter.com | tier 3 | 2026-08-15
5. Opus, Shorts length/format retention | opus.pro | tier 2 | 2026-08-15
6. Eugene Schwartz, awareness levels | tier 2 (secondary on canonical) | 2026-08-14

## Evaluation & QA

### Common Failure Modes
- The first 3 seconds wasted on an intro ("Hi, I'm...") — the scroll already happened
- A hook the payoff never delivers (curiosity without resolution)
- Feature-list bodies with no beats or pattern breaks
- One script stretched across every platform without format adaptation
- CTA not matched to goal (hard sell on organic awareness content)
- 60-second scripts written for a 30-second attention span
