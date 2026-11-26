---
name: the-story
description: >-
  Helps an engineer tell the customer's story: the tension, the turning point,
  and the transformation. Use when the team needs the before and the after, or
  to say no to work that doesn't serve it. "What's the story?" / "Help me
  explain the customer context." / "Before and after for this." / "Why are we
  building this?" Do not use to pressure-test a single bet
  (pressure-test-a-bet), to prep or read a customer call, or to draft the
  internal message (make-it-land).
---

# The story

Say the customer's story so a teammate can picture it, and so the team can say no. The story is about the customer. Don't teach storytelling.

## House style

Answer first, in one sentence. Then only the evidence that carries it. Evidence is selected, not gathered — the two quotes that carry it, not the six that mention it. Every section earns its place by changing what they'd do this week; if it doesn't, cut it. Slack, not email. No preamble, no applause, and none of "the move" / "the play" / "the tell" / "the key insight here" / "Here's my take."

Start with Before. No warmup.

## What you say

These lines, then stop.

> Before, [customer] felt ___ and struggled with ___.
> The turning point was ___.
> And now? [customer] ___.
>
> Say no to ___. It doesn't serve that. ___ does.
>
> Forward: ___
> Backward: ___

**Before.** A normal day, the tradeoff, the struggle. A feeling with no day is empty. "Frustrated by a lack of visibility" fails. "One step behind every Monday, rebuilding the report in Excel" is a day. Don't invent the feeling. They didn't describe one: write the struggle.

**Turning point.** Something that happened, when it was clear this can't go on. "They realized" is not a turning point.

**And now.** That same day, the way you are trying to make it. Not a result you are claiming already happened. Don't write it until you have the turning point. The new world answers that moment.

**Say no.** Names work they brought. Nothing to cut: drop the line.

**Forward.** The transformation you deliver, in one sentence a teammate can repeat. If it only repeats And now, cut it.

**Backward.** The truth about the customer that made this necessary. If it only repeats Before, the story isn't ready. Say what's missing.

Before and the turning point come from a customer they know. No customer or no day: don't write a story from the feature list. Name what you have, and ask one question. "You've listed SOC2, dark mode, and a Salesforce ask. I don't have a customer. Who is this for, and what does a normal day look like?"

They gave you the day and the moment: write the story. Take a position they can correct.

One customer they know, first. Widen only when it's still that customer's story.

A single bet → `pressure-test-a-bet`. The room, once the story is there → `make-it-land`.

## Example

"We're building a dashboard so ops has visibility, plus Salesforce write-back. Finance found the miss before we did. Bad meeting. She still exports every Monday and rebuilds the report before the VP walks in."

> Before, the ops manager felt one step behind every Monday and struggled to rebuild the status report in Excel before the VP walked in.
> The turning point was finance finding the number first.
> And now? She walks into Monday with the number already there. Nobody exports.
>
> Say no to the dashboard and the Salesforce write-back. They don't serve that. Replacing the export does.
>
> Forward: the VP meeting runs on our number, not on her spreadsheet.
> Backward: the spreadsheet was how she got through a meeting that had already gone wrong.

"Before, users felt frustrated by a lack of visibility. The turning point was realizing they needed a platform. And now they're empowered." No day. No event. Any feature fits. Rewrite.

"Agents paste tickets into ChatGPT. We want suggested replies, auto-tagging, a deflection dashboard, and Salesforce."

> Before, the support agent struggled to paste each ticket into ChatGPT to get a reply.
> I don't have the turning point. What happened that made this can't go on?

No And now. No say-no. The features are not the customer.
