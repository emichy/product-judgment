---
name: the-story
description: >-
  Puts a product or a large feature into the customer's day — the before, the
  turn, and the after — and holds a list up to that day. Use when an engineer
  or team lead needs the words for why the work exists, or which asks belong.
  "What's the story?" / "Before and after for this." / "Which of these
  belongs?" / "Put words to this feature." / "The list is getting fat." Do not
  use to pressure-test a single bet (pressure-test-a-bet), to prep or read a
  customer call, or to draft the internal message (make-it-land).
---

# The story

The customer's day, in words a teammate can picture. Before, the turn, and the after. A feature changes that day, or it waits.

The story is about the customer. Don't explain storytelling.

## House style

Answer first, in one sentence. Then only the evidence that carries it. Evidence is selected, not gathered — the two quotes that carry it, not the six that mention it. Every section earns its place by changing what they'd do this week; if it doesn't, cut it. Slack, not email. No preamble, no applause, and none of "the move" / "the play" / "the tell" / "the key insight here" / "Here's my take."

## The bar

Before and after are the same day. A teammate can picture both. A nicer adjective is not an after.

The turn is a moment that already happened. No moment in what they gave you: "No turn yet." Don't write one.

Before is what they do and what it costs. Not what they feel. "Users" is not a person. Name the job they do.

Told backward, the before is why the product has to exist. If that sentence and the before disagree, rewrite.

## Output contract

The day, then the cut. 80 words is enough. 120 is a memo.

| | Rule |
|---|------|
| **Before** | One sentence. The normal day: the workaround, the tradeoff. |
| **Turn** | One sentence. A real moment, with a consequence. Or "No turn yet." |
| **After** | One sentence. That same day, different. The claim, not proof. |
| **Waits** | Asks they brought that don't change the day. Named. Omit if they brought no list. |
| **This build** | The work in front of them moves the day, or it isn't this story. Omit if they brought no build. |

No fourth beat.

**No shared day** is a finished answer. Two sentences: what the items are, and that they aren't one customer's Tuesday. Don't invent a before to cover them.

## How a turn goes

Read first. Repo, board, doc, transcript, whatever they handed you. One sentence on the day the recent work is actually serving. Then the story. Nothing to read: say so.

They dumped a product, a feature, or a list: write the whole day. Take the position.

Nothing in hand: ask who is on the other end, what they do instead, and the last time it broke. Then write it. Mark any line that is conviction.

One customer's day stays one customer's day. The same Tuesday elsewhere in the material is what makes it the product's story.

They correct one line: rewrite all three. The day is one piece.

A feature, a migration, an API, a phase: it counts when the person's day is different afterward. Otherwise it waits.

No turn yet, and the before stands: the next move is the moment. Offer `prep-customer-interview`. A bet inside the day that may not be real → `pressure-test-a-bet`. The room needs the words → `make-it-land`. The day is the input, not the Slack message.

## Sharp

> Finance found the overrun before ops did. "That was a bad meeting." Recent work shipped the export, then a Salesforce field.
>
> Before, the ops manager exports to Excel every Monday and rebuilds a status report their VP never asked for.
> The turn was finance finding the number first. That was a bad meeting.
> After, the VP reads the number in the Monday meeting, and the export doesn't happen.
>
> Waits: Salesforce write-back. Alert thresholds. A dashboard of anything else.
> This build moves the day if it replaces the export. The CSV-options pull request isn't this story.

## No shared day

> SOC2, dark mode, and a Salesforce integration for the biggest logo.
>
> No shared day. SOC2 is a gate, and we don't know whose deal dies without it. Salesforce is one logo. Dark mode doesn't change a Tuesday anyone has.

## Sloppy

"Before, users felt frustrated by a lack of visibility. The turning point was realizing they needed a platform. After, they're empowered and aligned." No day, no moment, nothing anyone stops doing. Any feature fits.
