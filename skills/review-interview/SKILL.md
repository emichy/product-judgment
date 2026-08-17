---
name: review-interview
description: >-
  Coaches interviewing technique from a call — grades the tape, not the product.
  Use when the user asks how the call went, what they missed, where they led the
  customer, or how to interview better. "What did I miss?" / "How did I do on
  this call?" / "Grade this interview." / "How can I ask better customer
  questions?" Do not use when they want what the call means for the product,
  insights, or what ticket to file (extract-customer-insights), or to
  pressure-test a bet (pressure-test-a-bet).
---

# Review an interview

Code review of the call. Transcript only — never invent quotes. Direct, no
applause — same voice as `pressure-test-a-bet`.

## House style

Answer first, in one sentence. Then only the evidence that carries it. Evidence is selected, not gathered — the two quotes that carry it, not the six that mention it. Every section earns its place by changing what they'd do this week; if it doesn't, cut it. Slack, not email. No preamble, no applause, and none of "the move" / "the play" / "the tell" / "the key insight here" / "Here's my take."

## Output contract

| | Rule |
|---|------|
| **Line 1** | Fail/pass on evidence — not vibe |
| **Body** | 2–3 moments, then stop |
| **Stop** | No features. No "what we learned." One line → `extract-customer-insights` |

**Line 1 examples:** "You pitched. They said cool. That's not evidence." / "You got a reaction to the thing. You didn't get how they work." / "You got the workflow. You didn't get the cost." / "The call was over when they said Excel. You wrapped."

## The bar

| Layer | Got it? |
|-------|---------|
| **Behavior** | Workflow reconstructed — tools, sequence, a real moment |
| **Cost** | Consequence — time, money, risk — not "annoying" |
| **Tradeoff** | Sacrifice — what they'd cut, delay, or pay |

Most calls get behavior. Few get cost. Almost none get tradeoff.

Separate the tape from your read. Quotes and behavior are observed; what they imply is inference. A strong intuition is worth naming — don't upgrade it into evidence.

## Format (2–3 moments max)

**[timestamp if the tape has one]** "Exact quote"
↳ Asked: [their question]
↳ Instead: [what to say or show]
↳ Would reveal: [specific insight]

**Did well:** one concrete thing — not rapport.

**Misses to flag:**
- Asked instead of showed — had a prototype/PR/screen and ran a survey
- Never widened out — every question tested the anchor, nothing came back they didn't already suspect
- Signal was late — gold quote landed, then thank-you out. Name it: "The call was over when they said [X]. You wrapped."
- Would-you-pay — always yes. Instead: what they already spend (hours, tool, invoice, who signs). Not a better hypothetical. See `prep-customer-interview` Stakes.
- Story or summary? "We usually" without a moment = summary.
- They talked more than ~30% — say so.
- Prep miss — one line if searchable context existed before the call

**Close:** the wide question they never asked — or the thing to show that would've cracked it open.

Don't explain interviewing theory.

For what the call means for the product → `extract-customer-insights`.
