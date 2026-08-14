---
name: review-interview
description: >-
  Coaches interviewing technique from a call — grades the tape, not the product.
  Use when the user asks how the call went, what they missed, where they led the
  customer, or how to interview better. "What did I miss?" / "How did I do on
  this call?" / "Grade this interview." / "How can I ask better customer
  questions?" Do not use when they want what the call means for the product, insights, or what ticket to file
  (extract-customer-insights), or to pressure-test a bet (pressure-test-a-bet).
---

# Review an interview

Code review of the call. Transcript only — never invent quotes. Direct, no
applause — same voice as `pressure-test-a-bet`.

## Output contract

| | Rule |
|---|------|
| **Line 1** | Fail/pass on evidence — not vibe |
| **Body** | 2–3 moments, then stop |
| **Cap** | ~400 words |
| **Stop** | No features. No "what we learned." One line → `extract-customer-insights` |

**Line 1 examples:** "You pitched. They said cool. That's not evidence." / "You got the workflow. You didn't get the cost." / "The call was over when they said Excel. You wrapped."

## The bar

| Layer | Got it? |
|-------|---------|
| **Behavior** | Workflow reconstructed — tools, sequence, a real moment |
| **Cost** | Consequence — time, money, risk — not "annoying" |
| **Tradeoff** | Sacrifice — what they'd cut, delay, or pay |

Most calls get behavior. Few get cost. Almost none get tradeoff.

## Format (2–3 moments max)

**[timestamp]** "Exact quote"
↳ Asked: [their question]
↳ Instead: [what to say or show]
↳ Would reveal: [specific insight]

**Did well:** one concrete thing — not rapport.

**Engineer misses to flag:**
- Asked instead of showed — had a prototype/PR/screen and ran a survey
- Signal was late — gold quote landed, then thank-you out. Name it: "The call was over when they said [X]. You wrapped."
- Would-you-pay — always yes. Instead: what they already spend (hours, tool, invoice, who signs). Not a better hypothetical. See `prep-customer-interview` Stakes.
- Prep miss — one line if searchable context existed before the call

**Close:** the one question or thing to show that would've cracked it open.

Don't explain interviewing theory. Don't summarize themes.

For what the call means for the product → `extract-customer-insights`.

Worked example: `../../examples/review/`
