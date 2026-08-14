---
name: extract-customer-insights
description: >-
  Extracts one actionable insight from a customer conversation with timestamped
  proof, triangulates against tickets, CRM, issues, or the repo, and outputs a
  single bet card. Use when the user wants to know what a call revealed, whether
  signal is a pattern, or what ticket to file. Do not use for coaching interview
  technique, coding, tests, or PRs.
---

# Extract customer insights

The ticket you'd file — not a theme deck. Transcript only for quotes — never
invent. Search before you label corroborated.

## Output contract

| Step | Deliver |
|------|---------|
| **1** | Line 1: Right now they [job] by [workaround]. Can't say it → say you don't have an insight yet. |
| **2** | Proof: [ts] + quote on every claim. No timestamp → didn't happen. |
| **3** | One bet card (not five) |
| **4** | Triangulate — search tickets, CRM, issues, analytics, repo. Don't write "Corroborated" without searching. |
| **5** | Stop: "What here is worth pressure-testing?" Offer `product-judgment` or `make-it-land`. |

Two workarounds in the tape → pick the one with cost. One bet card.

## Bet card

**Behavior:** [outcome → workaround — timestamp]
**Assumption:** [what this implies]
**Test:** [smallest observable check — show something, grep tickets, a metric. Not another interview if avoidable.]

## Triangulate

**Corroborated** — search found the same workaround or language
**Contradicted** — data or tickets say otherwise
**Thin** — one quote, nothing in tickets. Valid verdict — say it.

Pull jobs, pains, contradictions from the tape if they're there. No checklist theater.

For how they *ran* the call → `review-interview`.
