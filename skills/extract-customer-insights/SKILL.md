---
name: extract-customer-insights
description: >-
  Extracts what a customer conversation revealed — current behavior, workarounds,
  quoted proof — then triangulates against tickets, CRM, issues, or the
  repo. Use when the user wants insights from a call, what it means, whether
  signal is a pattern, or what ticket to file. "Extract some insights." /
  "What did we learn?" / "What does this mean?" / "What do we do with this
  call?" Do not use for coaching how they interviewed (review-interview).
---

# Extract customer insights

The ticket you'd file — not a theme deck. Transcript only for quotes — never
invent. Search before you label corroborated.

## House style

Answer first, in one sentence. Then only the evidence that carries it. Evidence is selected, not gathered — the two quotes that carry it, not the six that mention it. Every section earns its place by changing what they'd do this week; if it doesn't, cut it. Slack, not email. No preamble, no applause, and none of "the move" / "the play" / "the key insight here" / "Here's my take."

## Output contract

| Step | Deliver |
|------|---------|
| **1** | Line 1: Right now they [job] by [workaround] — whichever workaround carries the cost, not the one they came to test. Can't say it → say you don't have an insight yet. |
| **2** | Proof: quote observed behavior exactly — two or three on the lede, the ones with a consequence. Not every mention. Label anything beyond the tape as inference or read. Vibe is allowed; invented certainty isn't. |
| **3** | One bet card, on the workaround with the cost. If that isn't what they came to test, say both in a line: "They shrugged at alerts; the cost is month-end in finance." Other signals get one line each. No card unless they ask. |
| **4** | Triangulate — search tickets, CRM, issues, analytics, repo. Don't write "Corroborated" without searching. |
| **5** | Stop with the current read in one line and what would flip it. Don't restate the bet card. Offer `pressure-test-a-bet` or `make-it-land` if useful. |

Anything about how they work keeps its line even when it changes nothing this week. That's the half of the call an engineer can't get from a demo.

## Bet card

**Behavior:** [outcome → workaround — quote, + timestamp if you have one]
**Assumption:** [what this implies]
**Test:** [smallest observable check — show something, grep tickets, a metric. Not another interview if avoidable.]

## Triangulate

**Corroborated** — search found the same workaround or language
**Contradicted** — data or tickets say otherwise
**Thin** — one quote, nothing in tickets. Valid verdict — say it. "We'd pay" with no number they already spend is Thin.
**Across calls** — same workaround, same shrug, same question nobody asked. Two polite yeses is not a pattern; it's the same call twice.
If you cite a ticket: one line on open / shipped / canceled. Don't collapse versions or treat a title as what shipped.

Pull jobs, pains, contradictions from the tape if they're there. No checklist theater.

For how they *ran* the call → `review-interview`.
