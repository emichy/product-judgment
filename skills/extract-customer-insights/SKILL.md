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

What the call revealed — not a theme deck. Transcript only for quotes — never
invent. Search before you label corroborated.

## House style

Answer first, in one sentence. Then only the evidence that carries it. Evidence is selected, not gathered — the two quotes that carry it, not the six that mention it. Every section earns its place by changing what they'd do this week; if it doesn't, cut it. Slack, not email. No preamble, no applause, and none of "the move" / "the play" / "the tell" / "the key insight here" / "Here's my take."

120 words of your own prose is long. 180 is an analysis — cut until it isn't. Quotes don't count.

Search findings live in Triangulate. Never in Proof, never in Other signals.

## Output contract

| Step | Deliver |
|------|---------|
| **1** | Line 1: Right now they [job] by [workaround] — whichever workaround carries the cost, not the one they came to test. Observed only; a read like "they know it breaks" is Assumption or a quote, not Line 1. Can't say it → say you don't have an insight yet. |
| **2** | Proof: two or three quotes on the lede, the ones with a consequence. Then one sentence of label, max. No paragraph after the quotes. Label anything beyond the tape as inference or read. Vibe is allowed; invented certainty isn't. |
| **3** | One bet card, on the workaround with the cost. If that isn't what they came to test, say both in a line: "They shrugged at alerts; the cost is month-end in finance." Other signals: at most three, one sentence each. No account lists, no filing briefs, no second bet. |
| **4** | Triangulate — search tickets, CRM, issues, analytics, repo. Don't write "Corroborated" without searching. |
| **5** | One sentence read, one sentence flip. Don't restate the bet card. Offer `pressure-test-a-bet` or `make-it-land` if useful. |

Anything about how they work keeps its line even when it changes nothing this week.

## Bet card

**Behavior:** one line — outcome → workaround — quote. Not a paragraph, and not the leap.
**Assumption:** [what this implies — the leap goes here]
**Test:** [smallest observable check — show something, grep tickets, a metric. Not another interview if avoidable.]

*Sloppy:* Line 1 with a read baked in, a proof essay, a paragraph of Behavior, five other-signal briefs, a three-part closing recommendation.

*Sharp:*

> Right now they catch budget overruns by exporting usage every Monday and eyeballing the diff — the month nobody ran it is why finance owns the number now.
>
> "I pull the CSV Monday mornings and compare it to last week." / "Finance found it before we did. That was a bad meeting." Eighteen months of Mondays, still nobody's automated it.
>
> **Behavior:** catch overruns → manual Monday export and diff — "I pull the CSV Monday mornings"
> **Assumption:** the job is early warning, not reporting
> **Test:** the export itself — one person, one file, we can watch it without asking
>
> Two people run that diff, not one. The threshold they asked us to alert on, nobody could name. They shrug at the dashboard idea themselves.
>
> Monday diff: Corroborated. Threshold: Thin. Finance ownership: Inference.
>
> Read: build the warning, not the dashboard. Flips if the Monday export turns out to be a compliance artifact they'd keep either way.

## Triangulate

**Corroborated** — search found the same workaround or language
**Contradicted** — data or tickets say otherwise
**Thin** — one quote, nothing in tickets. Valid verdict — say it. "We'd pay" with no number they already spend is Thin.
**Across calls** — same workaround, same shrug, same question nobody asked. Two polite yeses is not a pattern; it's the same call twice.
If you cite a ticket: one line on open / shipped / canceled. Don't collapse versions or treat a title as what shipped.

Pull jobs, pains, contradictions from the tape if they're there. No checklist theater.

For how they *ran* the call → `review-interview`.
