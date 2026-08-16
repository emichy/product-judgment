---
name: prep-customer-interview
description: >-
  Turns a customer conversation into one anchor sentence and 4-5 spoken
  questions — and finds two or three people likely to react strongly when
  nobody's named. Use when the user has a call scheduled, wants prep for a
  support call or screen-share, or needs someone to react to a prototype.
  "Prep me for the Acme call." / "I have a call Thursday." / "Who should I talk
  to?" / "I want to talk to customers about this." Do not use for past
  transcripts (extract-customer-insights for what it means, review-interview for
  how they interviewed) or for pressure-testing the bet (pressure-test-a-bet).
---

# Prep a customer conversation

Working session, not an interview guide. Engineers grab 20 minutes — maybe on a
support call, maybe sharing a screen. Same evidence bar as `pressure-test-a-bet`:
current behavior, not hypotheticals.

The trigger is a question, not a launch. "I'll talk to customers when I have
something to show" is how an engineer ends up with one call a quarter, every one
of them a demo. Never tell someone to wait until they have something.

## House style

Minto: answer first in one sentence, then only the evidence that carries it. Evidence is selected, not gathered — the two quotes that carry it, not the six that mention it. Every section earns its place by changing what they'd do this week; if it doesn't, cut it. Slack, not email. No preamble, no applause, and none of "the move" / "the play" / "the key insight here" / "Here's my take."

**Always deliver an anchor and questions.** Missing account, empty search, unclear what kind of call — write them anyway with a placeholder in the blank, and ask at the end. Never open with what you need from them, and never as a form or a menu. Nothing is too thin to start from.

## The anchor

One sentence — the thing that, if wrong, changes what you'd build. Not a list of "learning goals."

No bet yet is still a call. The anchor becomes what you don't understand about how they work, and the whole thing runs generative. Don't manufacture a bet to justify the conversation.

This call is not to count how many people have the problem. Tickets do that. This call is why it hurts and whether they'd change.

## The questions

4–5 on the anchor, plus one that has nothing to do with it. The anchor questions can only confirm or kill what they already suspected; the off-anchor one is where the surprise comes from. Spoken English. No warm-ups, coaching notes, or hypotheticals as the closer ("if we built X tomorrow…").

If they have a prototype, the plan is show it. If not: last time + workaround + cost + sacrifice. Mix in **one** Stakes question — don't make a money interview.

Worked shape (same structure, their words):

> **Anchor:** We believe usage alerts prevent budget surprises — but we don't know if it's pricing shock, budget misallocation, or something else.
>
> 1. "Walk me through what happened last quarter with the budget surprise. Start when you first noticed something was off."
> 2. "What did you end up doing to fix it?"
> 3. "If I asked you to pull your current usage right now — how easily could you do that?"
> 4. "When that surprise hit, who had to deal with it — you, finance, your boss?"
> 5. "What made you want to take this call now?"
> 6. "Nothing to do with alerts — what's the most annoying part of running this account month to month?"
>
> **Listen for:** Who actually ate the surprise — them, or finance. Whether the workaround is manual or nothing at all. If they go vague on the moment, the pain didn't stick.

Close every script with **Listen for** — what a real answer sounds like versus a polite one. Not learning goals, not coaching notes.

Past behavior beats "would you." Their words, not your roadmap. Close: "Sounds like the value is X but trust hinges on Y — right?"

Early-stage bets may begin with founder or customer pull before a pattern exists. Don't launder that into proof — use the call to sharpen it.

**Skeleton keys** (pick, don't print the list):
- "Walk me through the last time." No specific moment = weaker evidence, not necessarily no problem.
- "What did you end up doing?" Workaround = spec.
- "So what happens if you just… don't?"
- "What would actually break if we disappeared tomorrow?"

**They shrug at the feature — that's the answer, not a failed call.** Stop testing it, don't sell harder. Spend the rest of the time on their world: "Fair enough — so what *is* the annoying part of [their workflow] right now?" You booked 20 minutes to learn something and you still have 15 of them.

## Stakes (never "would you pay")

The workaround *is* the budget. Mix in 1–2. Watching them skip a step beats asking if they'd pay.

- "What are you paying for this today? Not hypothetically — the spreadsheet, the contractor, the other product."
- "Walk me through the last time this blew up. What did it cost — hours, a tool, an invoice, a person?"
- "What did you cut last time you had to make room for this?"
- "Who had to sign off the last time you spent money on it?"

## Who'll react

They need reactions to a specific thing, not a representative sample. Three to five people with enough at stake to react either way.

**Start from who they already have.** One or two names is a seed, not a shortfall. Name what makes those two right — built the workaround, churned over it, biggest list, filed the ticket — then find others on that line. Extending a line beats searching a category.

Where the line runs: same ticket theme in support (Intercom, Zendesk), `customer:` tags and comments in GitHub / Linear / Jira, same churn or closed-lost reason in CRM, same usage shape in analytics (exports, CSV downloads, empty states), the repo (PRs, issue text, TODO/FIXME naming a customer), and mail / calendar / Slack — they may have already talked to someone. Canceled tickets and prior attempts count: already tried ≠ don't build.

**Spread the reactions.** Someone who'll want it, someone who'll pick it apart, someone who left. Not your biggest fan, not five random logos, one power user max — label them as such. Five of the same person is one data point.

Three rows, one piece of recent evidence each, then stop. This is a sweep, not a research project.

| who | evidence | reach | draft |
|-----|----------|-------|-------|

Draft the ask — short, engineer-to-human:

"You mentioned exporting to Excel every Monday in [ticket]. Got 20 minutes this week? I want to see how you do it — I've got a rough version to react to."

**Nothing in the tools → say so.** Ask for a ticket export, a CRM list, or three names they already know. **Never invent accounts.** Never auto-send — always draft.
