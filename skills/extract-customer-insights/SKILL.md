---
name: extract-customer-insights
description: >-
  Extracts what a customer conversation revealed — current behavior, workarounds,
  quoted proof — then triangulates against tickets, CRM, issues, or the
  repo. Use when the user wants insights from a call, what it means, whether
  signal is a pattern, or what ticket to file. "Extract some insights." /
  "What did we learn?" / "What does this mean?" Do not use for coaching how
  they interviewed (review-interview).
---

# Extract customer insights

The ticket you'd file — not a theme deck. Transcript only for quotes — never
invent. Search before you label corroborated.

## House style

Minto. Answer first, one sentence — the workaround, the verdict, the ask. Then only the evidence that carries it.

- Evidence is selected, not gathered. The two quotes that carry it, not the six that mention it.
- Every section earns its place by changing what they'd do this week. If it doesn't, cut it.
- Slack, not email. Doesn't fit on a screen → you're writing an analysis.
- No preamble, no restating the question, no applause.
- Never: "the move," "the play," "the key insight here," "the trap," "Here's my take," "Here's the thing."

## Output contract

| Step | Deliver |
|------|---------|
| **1** | Line 1: Right now they [job] by [workaround]. Can't say it → say you don't have an insight yet. |
| **2** | Proof: quote observed behavior exactly — two or three on the lede, the ones with a consequence. Not every mention. Label anything beyond the tape as inference or read. Vibe is allowed; invented certainty isn't. |
| **3** | Lead with the workaround that has cost. One bet card on that. Other signals: one line each — the signal *and* what it would change. Changes nothing this week → cut it. No card unless they ask. |
| **4** | Triangulate — search tickets, CRM, issues, analytics, repo. Don't write "Corroborated" without searching. |
| **5** | Stop with the current read in one line and what would flip it. The bet card already carried the assumption and the test — don't restate them. Offer `pressure-test-a-bet` or `make-it-land` if useful. |

## Bet card

**Behavior:** [outcome → workaround — quote, + timestamp if you have one]
**Assumption:** [what this implies]
**Test:** [smallest observable check — show something, grep tickets, a metric. Not another interview if avoidable.]

## Triangulate

**Corroborated** — search found the same workaround or language
**Contradicted** — data or tickets say otherwise
**Thin** — one quote, nothing in tickets. Valid verdict — say it. "We'd pay" with no number they already spend is Thin.
If you cite a ticket: one line on open / shipped / canceled. Don't collapse versions or treat a title as what shipped.

Pull jobs, pains, contradictions from the tape if they're there. No checklist theater.

For how they *ran* the call → `review-interview`.
