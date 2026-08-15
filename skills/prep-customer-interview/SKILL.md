---
name: prep-customer-interview
description: >-
  Finds named people to talk to from support, issues, CRM, analytics, or the
  repo, then aligns on one thing to learn and drafts 4-5 spoken questions on
  request. Use when the user needs who to talk to, has a call coming up, or
  wants prep for a support call or screen-share. "Who should I talk to?" /
  "Prep me for the Acme call." / "Which customers or prospects should I talk
  to?" Do not use for past transcripts (extract-customer-insights for what it
  means, review-interview for how they interviewed) or for pressure-testing
  the bet (pressure-test-a-bet).
---

# Prep a customer conversation

Working session, not an interview guide. Engineers grab 20 minutes — maybe on a
support call, maybe sharing a screen. Same evidence bar as `pressure-test-a-bet`:
current behavior, not hypotheticals.

Three phases. Skip any that's already done.

| Phase | Job | Stop |
|-------|-----|------|
| **Find** | Named people, with evidence | 3 names, not a persona |
| **Align** | One anchor sentence | "Want 4 questions + an ask?" |
| **Script** | 4–5 questions, spoken English | On request only |

## Find (default)

If they already have a name on the calendar, say so and skip to Align.

**No named people in tools or the repo → say so.** Ask for a ticket export, a CRM list, or three names they already know. **Never invent accounts.**

Before any questions, search what's available:

- Support / Intercom / Zendesk — last 30 days, this theme, named accounts
- GitHub / Linear / Jira — customer comments, `customer:` tags, the issue this bet maps to
- CRM — churn, closed-lost, expansion stalled, who filed the request
- Analytics if connected — exports, CSV downloads, empty-state workarounds
- Repo — PRs, issue text, TODO/FIXME naming a customer
- Mail / calendar / Slack if connected — they may have already talked to someone
- Canceled tickets, old projects, prior attempts. Already tried ≠ don't build. Why did it die, what's changed, what new data or angle do we have?

**Filter:** hit the problem recently, still doing the workaround, not your biggest fan, not five random logos. Prefer: support-heavy, churned, lost the deal, built the spreadsheet. One power user max — label as such.

**Output — table, then stop:**

| who | evidence | reach | draft |
|-----|----------|-------|-------|

Three rows. Draft the ask — short, engineer-to-human:

"You mentioned exporting to Excel every Monday in [ticket]. Got 20 minutes this week? I want to see how you do it — I've got a rough version to react to."

Never auto-send. Always draft.

Then: **Want 4 questions + an ask for #1?**

## Align

One sentence — the thing that, if wrong, changes what you'd build. Not a list of "learning goals."

This call is not to count how many people have the problem. Tickets do that. This call is why it hurts and whether they'd change.

Then: **Want 4 questions + an ask?** Nothing else.

## Script (on request only)

4–5 questions. Spoken English. No warm-ups, coaching notes, or hypotheticals as the closer ("if we built X tomorrow…").

If they have a prototype, the plan is show it. If not: last time + workaround + cost + sacrifice. Mix in **one** Stakes question — don't make a money interview.

Worked shape (same structure, their words):

> **Anchor:** We believe usage alerts prevent budget surprises — but we don't know if it's pricing shock, budget misallocation, or something else.
>
> 1. "Walk me through what happened last quarter with the budget surprise. Start when you first noticed something was off."
> 2. "What did you end up doing to fix it?"
> 3. "If I asked you to pull your current usage right now — how easily could you do that?"
> 4. "When that surprise hit, who had to deal with it — you, finance, your boss?"
> 5. "What made you want to take this call now?"

Past behavior beats "would you." Their words, not your roadmap. Close: "Sounds like the value is X but trust hinges on Y — right?"

Sound like a person: "walk me through your workflow" → "What tools are in the mix right now?" / "primary pain points" → "What's the most annoying part?"

Early-stage bets may begin with founder or customer pull before a pattern exists. Don't launder that into proof — use the call to sharpen it.

**Skeleton keys** (pick, don't print the list):
- "Walk me through the last time." No specific moment = weaker evidence, not necessarily no problem.
- "What did you end up doing?" Workaround = spec.
- "What happened right before that?" Then one step earlier.
- "So what happens if you just… don't?"
- "What would actually break if we disappeared tomorrow?"
- "When did this start?" When gets a story. Why gets a thesis.

Vague answer → move on. Detail or frustration → "Say more."

## Stakes (never "would you pay")

The workaround *is* the budget. Mix in 1–2. Watching them skip a step beats asking if they'd pay.

- "Walk me through the last time this blew up. What did it cost — hours, a tool, an invoice, a person?"
- "What are you paying for this today? Not hypothetically — the spreadsheet, the contractor, the other product."
- "If I asked you to pull that up right now, could you?"
- "What did you cut last time you had to make room for this?"
- "Who had to sign off the last time you spent money on it?"
- "The Monday Excel file — whose time is that, and what don't they do instead?"
