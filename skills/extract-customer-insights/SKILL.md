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
| **5** | One sentence read, one sentence flip. Don't restate the bet card. Two bets means you picked a second card they didn't ask for. Offer `pressure-test-a-bet` or `make-it-land` if useful. |

Anything about how they work keeps its line even when it changes nothing this week. That's the half of the call an engineer can't get from a demo.

## Bet card

**Behavior:** one line — outcome → workaround — quote. Not a paragraph, and not the leap.
**Assumption:** [what this implies — the leap goes here]
**Test:** [smallest observable check — show something, grep tickets, a metric. Not another interview if avoidable.]

*Sloppy:* Line 1 with a read baked in, a proof essay, a paragraph of Behavior, five other-signal briefs, a three-part closing recommendation.

*Sharp:*

> Right now they personalize the embed with a Salesforce → category-ID lookup table, one row per entitlement combo — and the combinatorics are why it still isn't shipped.
>
> "We'll have a lookup table… this is what we say in Salesforce, here are the category IDs." / "Categories I would never send over. Like reporting." Eighteen months, second-or-third priority, no data model.
>
> **Behavior:** personalize per account → hand-built lookup table — "one row per entitlement combo"
> **Assumption:** categories are an authoring taxonomy conscripted as entitlements
> **Test:** the Salesforce payload, already asked for on the call
>
> Two embeds is a real install cost. Unread on the popup — six accounts, open. They shrug at copy-to-project themselves.
>
> Mapping: Thin. Unread: Corroborated. Portfolio: Inference.
>
> Read: don't design the lookup until the Salesforce shape is in hand. Flips if that export is already a flat category list.

## Triangulate

**Corroborated** — search found the same workaround or language
**Contradicted** — data or tickets say otherwise
**Thin** — one quote, nothing in tickets. Valid verdict — say it. "We'd pay" with no number they already spend is Thin.
**Across calls** — same workaround, same shrug, same question nobody asked. Two polite yeses is not a pattern; it's the same call twice.
If you cite a ticket: one line on open / shipped / canceled. Don't collapse versions or treat a title as what shipped.

Pull jobs, pains, contradictions from the tape if they're there. No checklist theater.

For how they *ran* the call → `review-interview`.
