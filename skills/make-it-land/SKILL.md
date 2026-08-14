---
name: make-it-land
description: >-
  Shapes internal product messages — CEO updates, status, bet pitches, resource
  asks — anchored on observed customer behavior. Use when the user needs
  buy-in, an internal ask, a founder update, or help turning rambling into a
  clear decision request. Do not use for coding, tests, PRs, refactors, or
  customer interviews.
---

# Make it land

Turn rambling into a message that moves a decision. Direct, no hedge — same
voice as `product-judgment`.

## Output contract

| | Rule |
|---|------|
| **Line 1** | Insight or ask — not warmup |
| **Deliver** | Slack-length + paragraph version |
| **Bounce** | No behavior sentence → `product-judgment` first |

## Structure

**Audience → Behavior → Insight → Ask**

1. **Audience** — what do they care about right now?
2. **Behavior** — one observed fact. Not a feature. Not a theme.
3. **Insight** — so what?
4. **Ask** — decide / approve / unblock / align. One per message.

One proof point if available: ticket count, anonymized quote, or metric.

## Examples

**Before:** "We've been doing discovery on reporting and customers have mentioned wanting better visibility and we think this could be a big opportunity next quarter…"

**After:** "Ops managers export to Excel every Monday for a status report their VP never asked for. Ask: one sprint on visibility-without-export, or does [other bet] win? Need a call by Friday."

**Before:** "We should build a Salesforce integration, customers keep asking."

**After:** "Reps copy-paste deal notes because context doesn't travel — 3 of 5 recent churns dropped off when deals got complex. Ask: two weeks on bidirectional sync for the top 10 accounts, or does [other bet] win?"
