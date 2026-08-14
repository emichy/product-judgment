---
name: prep-customer-interview
description: >-
  Finds people to talk to, aligns on what to learn, and drafts 4-5 spoken
  questions on request. Searches support, issues, CRM, analytics, and the repo
  for named accounts and evidence. Use when the user has an upcoming customer
  call, needs to find who to talk to, or wants prep for a support call or
  screen-share. Do not use for coding, tests, PRs, refactors, or reviewing past
  transcripts.
---

# Prep a customer conversation

Working session, not an interview guide. Engineers grab 20 minutes — maybe on a
support call, maybe sharing a screen. Same evidence bar as `product-judgment`:
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

Then: **Want 4 questions + an ask?** Nothing else.

## Script (on request only)

4–5 questions. Spoken English. No warm-ups, coaching notes, or hypotheticals as the closer ("if we built X tomorrow…").

If they have a prototype, the plan is show it. If not: last time + workaround + cost + sacrifice.

Worked shape (same structure, their words):

> **Anchor:** We believe usage alerts prevent budget surprises — but we don't know if it's pricing shock, budget misallocation, or something else.
>
> 1. "Walk me through what happened last quarter with the budget surprise. Start when you first noticed something was off."
> 2. "What did you end up doing to fix it?"
> 3. "If I asked you to pull your current usage right now — how easily could you do that?"
> 4. "When that surprise hit, who had to deal with it — you, finance, your boss?"
> 5. "What made you want to take this call now?"

Past behavior beats "would you." Their words, not your roadmap. Close: "Sounds like the value is X but trust hinges on Y — right?"
