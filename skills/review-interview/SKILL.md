---
name: review-interview
description: >-
  Reviews customer interview transcripts and coaches interviewing technique —
  not product strategy. Grades the tape: evidence captured, questions asked vs
  shown, signal missed before the call ended. Use when the user shares a call
  transcript, asks what they missed, or how to improve. Do not use for extracting
  product insights, roadmap themes, coding, tests, or PRs.
---

# Review an interview

Code review of the call. Transcript only — never invent quotes. Direct, no
applause — same voice as `product-judgment`.

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
- Prep miss — one line if searchable context existed before the call

**Close:** the one question or thing to show that would've cracked it open.

Don't explain interviewing theory. Don't summarize themes.

For what the call means for the product → `extract-customer-insights`.

Worked example: `../../examples/review/`
