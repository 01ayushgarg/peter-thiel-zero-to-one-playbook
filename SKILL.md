---
name: peter-thiel-zero-to-one-playbook
description: Run a Peter Thiel-style strategy session on a startup or idea (the contrarian question, the market reality check, the monopoly scorecard, last mover durability, distribution math and the founding), using only his own lectures, essays and interviews plus Blake Masters' labelled notes of his 2012 Stanford class, with every point cited. Use when someone wants to test whether an idea is a real secret, size a market honestly, find out if they're in a competitive trap, judge whether a company can become a durable monopoly, check CLV against acquisition cost, set up cofounders, equity and board, or asks "what would Peter Thiel say". Triggers on "zero to one", "competition is for losers", "contrarian question", "what important truth", "what valuable company is nobody building", "secrets", "monopoly", "last mover", "10x better", "network effects", "power law", "definite optimism", "Thiel's law", "is my market too small", "is my market too big", "what would Thiel do".
---

# Peter Thiel's Zero to One Playbook

An unofficial, sourced method for pressure-testing a startup the way Peter Thiel describes thinking about
companies: find a secret, own a small market, make it last, and get the founding right. Built from his own
recorded words and Blake Masters' notes of his 2012 Stanford class. Who he is, for this playbook:
`references/00-who-is-peter-thiel.md`.

> "I sort of have a single idée fixe that I'm completely obsessed with on the business side which is that if
> you're starting a company, if you're the founder, entrepreneur, starting a company you always want to aim for
> monopoly and you want to always avoid competition." [YCL5]

## Ground rules for the agent

- Every point cites a source ID (e.g. `[YCL5]`, `[WSJ14]`, `[CS183-09]`, see `SOURCES.md`). **Never put words
  in his mouth.** If the playbook doesn't cover something, say so.
- **Two kinds of source.** `[YCL5]`, `[WSJ14]`, `[NPR14]`, `[CWT15]`, `[AMA14]`, `[NR11]`, `[CWT24]` are his own
  words. `[CS183-nn]` are Blake Masters' near-verbatim notes, not a transcript. Always label them as from Blake
  Masters' class notes when quoting them.
- **Guests aren't Thiel.** Some classes had guests (Levchin, Cohen, Botha, Graham, Andreessen, Hoffman and
  others). CS183-08 was given by Bruce Gibney. Never present their views as his.
- **Zero to One (the book) is not a source.** Only lines from its published WSJ excerpt [WSJ14] are quoted.
- Quote briefly and exactly. Paraphrases and applications to the founder's company are labelled as our reading.
- Dated numbers stay dated: in 2012, as of May 2014, PayPal in March 2001.
- **Not covered:** his politics. Decline to use this skill for political questions.
- He warns against formulas: "If I give you some general answer, and everybody could follow it, then if everybody
  followed that answer, it would be the wrong thing to do." [CWT15] Use the questions to sharpen the founder's
  thinking, not to hand them a template answer. If the honest conclusion is that this may not be a good business
  to start, say so.

---

## Step 1: Get the facts (ask only what you can't see)

1. What are you building, in one sentence? What's new about it: zero to one, or one to n? [CWT15]
2. Who is the first customer group, by name and count? [YCL5]
3. Who else serves them today, including indirect substitutes? [WSJ14]
4. On the one dimension customers care about most, how much better are you than the next best thing? [YCL5]
5. Price, gross margin, customer lifetime and cost to acquire a customer. [CS183-09]
6. Founders: how did you meet, how long have you worked together, how is equity split, who's on the board,
   what does the CEO earn? [CWT15, CS183-06]
7. Where do you want the company to be in 10 years? [YCL5]

## Step 2: The contrarian question

Ask both versions and push for a specific answer [NPR14, WSJ14]:
- "tell me something that is true that very few people agree with you on" [NPR14]
- "What valuable company is nobody building?" [WSJ14]

Then classify the answer (`references/01-zero-to-one-and-secrets.md`): a convention (everyone agrees), a
secret (true, important, unpopular, findable) or a trend (a big wave everyone sees [AMA14]). Run the mimesis
check (`references/09-mimesis-and-thinking-for-yourself.md`): is it attractive because others are doing it?

## Step 3: The market reality check

- Ask his question: "what is the actual market? So not what's the narrative of the market" [YCL5]
- Run the **intersection test**: drop the pitch's qualifiers one by one. Is the small market real, or is it a
  slice of a big competitive one? [YCL5, WSJ14]
- Is the first market small enough to dominate quickly, and can it expand in concentric circles? [YCL5]
- Separate X (value created) from Y (share captured). [YCL5]
→ `references/02-competition-is-for-losers.md`, `templates/02-market-reality-check.md`

## Step 4: The monopoly scorecard

Score proprietary technology (10x on one dimension), network effects, economies of scale and brand, today and in
ten years [YCL5, CS183-04]. Note vertical integration if relevant [YCL5]. Ask why the product is valuable to the
very first user [YCL5]. → `references/03-building-a-monopoly.md`, `templates/03-monopoly-scorecard.md`

## Step 5: Last mover

Ask "why will this still be the leading company in ten, fifteen, twenty years from now" [YCL5]. Estimate what
share of value comes after year ten (his PayPal answer in March 2001: about three quarters [YCL5]). Name what
could overtake each advantage. → `references/04-last-mover-and-durability.md`, `templates/06-ten-year-test.md`

## Step 6: Distribution

Compute CLV vs acquisition cost [CS183-09]. Place the price on the sales spectrum and flag the missing middle
[CS183-09]. Push for **one** channel that works [CS183-09]. → `references/05-distribution.md`,
`templates/04-distribution-math.md`

## Step 7: The founding

Check cofounder history and alignment, equity split, vesting, board size and CEO cash pay against the 2012 class
rules [CS183-06] and his own answers [AMA14, CWT15]. → `references/06-the-founding.md`,
`references/10-founders-and-teams.md`, `templates/05-founding-checklist.md`

Use `references/07-the-power-law.md` and `references/08-definite-optimism-and-planning.md` when the founder is
spreading effort across many markets, channels or revenue lines, or has no plan beyond iterating.
`references/11-the-questions.md` is the full question bank.

## Step 8: Deliver the strategy session notes

```markdown
# Strategy session: [company]

**The secret:** [one sentence: most people believe X, the truth is Y] · **Verdict:** secret / convention / trend

## The market, honestly
- Pitch market: ___ · Actual market: ___ · First market to own: ___ (size ___, share now ___%)
- X (value created): ___ · Y (share captured): ___

## Monopoly scorecard
| | Tech (10x?) | Network | Scale | Brand | Total |
| Today | | | | | /8 |
| In 10 years | | | | | /8 |

## Last mover
- Share of value after year 10 (rough): ___% · Why we'd be the last mover: ___ · Biggest threat: ___

## Distribution
- CLV $___ vs acquisition cost $___ · Spectrum position: ___ · The one channel: ___

## Founding
- Flags: [cofounder history, equity, board, CEO pay, part-time, consultants]

## This quarter
1. [Action] · owner · [source]
2. ...
3. ...

**The question to answer next:** [the one from the bank they couldn't answer]

## Where to be careful
- [Which points rely on 2012 class notes rather than his own words; which numbers are dated; where his view is
  contested, e.g. lean startup]
```

Rules for the notes:
- **At most three actions**, each with an owner.
- **Name the secret in one sentence.** If you can't, that is the first action.
- **Mark every application** to the founder's company as our reading, and keep the class-notes label on every
  CS183 quote.

Templates for the founder: `templates/01-secret-and-contrarian-truth.md`, `templates/02-market-reality-check.md`,
`templates/03-monopoly-scorecard.md`, `templates/04-distribution-math.md`, `templates/05-founding-checklist.md`,
`templates/06-ten-year-test.md`. A full example: `examples/01-worked-session.md`.
