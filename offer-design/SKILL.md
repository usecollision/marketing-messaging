---
name: offer-design
category: strategy
description: Construct offers beyond discounts - value stacking, pricing psychology, guarantees and risk reversal, bonuses, and offer testing.
triggers:
  - "design an offer"
  - "offer structure"
  - "value stack"
  - "guarantee"
  - "risk reversal"
  - "bonus bundle"
  - "offer testing"
  - "pricing psychology"
inputs:
  - core_product
  - target_segment
  - pricing_model
  - objections
  - margin_limits
  - competitor_offers
outputs:
  - offer_stack
  - guarantee_design
  - bonus_selection
  - test_matrix
related_skills:
  - value-proposition
  - messaging-hierarchy
  - objection-handling
  - landing-page-copy
  - email-copy
  - marketing-intelligence/pricing-intelligence
  - marketing-intelligence/pricing-packaging-strategy
  - marketing-optimize/ab-testing
  - marketing-optimize/checkout-optimization
required_context:
  - .context/product-marketing.md
allowed_tools: []
version: 1.0.0
---

## When to Use

Invoke when:
- Conversion stalls despite decent traffic and copy — the offer itself is the bottleneck
- Discounting is the only lever anyone reaches for
- Launching a new product, plan, or bundle and the "offer" is currently just a price
- Competitors win on perceived value despite a weaker product

## Workflow

### Step 1: Diagnose Before Designing

- Name the conversion bottleneck first — attention, comprehension, trust, price objection, or risk aversion. The offer must fix the real blocker, not a guessed one.
- Audit the current offer — what is included, what is promised, and what is at risk for the buyer
- Lay competitor offers next to yours (pricing-intelligence) — where do they out-stack you?
- Pull objections (objection-handling) — price objections usually mean the value is unclear, not that the price is wrong

**Gate:** Bottleneck named with evidence; current offer and competitor offers documented side by side.

### Step 2: Build the Value Stack

- Start from the core promise — the outcome, from value-proposition. Everything else supports it.
- Add layers that either raise perceived value or remove a barrier — nothing neutral belongs in the stack
- Useful layers — setup/onboarding, templates, community access, support tiers, speed of results, integrations, training
- Quantify each element's value where honest — avoid fake "total value" arithmetic that inflates prices nobody has ever paid

**Gate:** Stack documented with each element's job labeled (value or barrier removal) and honest value figures.

### Step 3: Apply Pricing Psychology Honestly

- **Anchoring** — present a legitimate reference point before the price (cost of the alternative, competitor pricing, prior pricing)
- **The rule of one** — a single price is the easiest decision; multiple options need an obvious good/better/best structure
- **Tier design** — make the target option clearly the best deal; a decoy only earns its place if it guides choice
- **Framing** — monthly versus daily cost, per-seat versus flat, one-time versus subscription — where legitimate
- Treat every psychological lever as framing, not manipulation — misleading anchors get discovered and erode trust and reviews

**Gate:** Pricing presentation designed; each lever has an honest rationale written next to it.

### Step 4: Design Guarantees and Risk Reversal

- Match guarantee strength to perceived risk — a high-stakes purchase needs stronger reversal than an impulse one
- Types — money-back windows, results-based guarantees, try-before-you-buy, pay-what-it's-worth, partial refunds, double-the-difference
- Make the guarantee specific and easy to claim — vague or buried guarantees reduce no risk
- Keep public terms simple; handle abuse prevention in eligibility details, not in the headline promise
- Place the guarantee where doubt peaks — on the landing page near the price, not in the footer

**Gate:** Guarantee designed to match risk level; claim process specified in plain terms.

### Step 5: Select Bonuses and Bundles

- Every bonus must accelerate the core promise — a bonus that duplicates or distracts reduces perceived value
- Bonus logic — speed (get results faster), certainty (reduce setup risk), or expansion (use the outcome more widely)
- Scarcity and deadlines must be real — fake scarcity is discovered, screenshotted, and punished
- Bundle tiers map to segments — each tier's target customer is obvious, and nobody is confused about which to buy

**Gate:** Every bonus justified by acceleration logic; tiers mapped to segments with a recommended default.

### Step 6: Test the Offer

- Test one offer element at a time — price point, guarantee, bonus set, or tier count
- Define the test matrix — variant, hypothesis, metric, minimum sample before judging (ab-testing)
- Watch downstream metrics, not just conversion — an offer that converts but raises refunds or churn is a failure
- Re-test when context shifts — seasonality, competitor moves, new features, price changes

**Gate:** Test matrix with isolated variables, hypotheses, success metrics, and downstream guardrails.

## Evaluation & QA

### Common Failure Modes

- Discounting by default — price cuts train customers to wait and erode the margin that funds everything else
- Value stacking with junk bonuses that dilute the core promise
- Fake scarcity or fake total-value math that gets called out publicly
- Guarantees so vague or buried that they reduce zero risk
- Offers that convert but attract the wrong segment, driving refunds and churn
- Testing the entire offer at once, so no single lever is learnable
- Designing the offer without economics — a winning offer must still clear margin targets
- Pricing psychology used as manipulation instead of framing, betting long-term trust on a short-term lift
