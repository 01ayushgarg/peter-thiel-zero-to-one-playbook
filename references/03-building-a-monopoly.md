# 03 · Building a monopoly

Citation IDs are in `SOURCES.md`. `[CS183-nn]` quotes are **from Blake Masters' class notes** of the 2012
course: near-verbatim, not Thiel's own transcript. `[YCL5]` (2014) is a transcript of Thiel speaking; `[FQA14]`
and `[AMA14]` are his own answers.

## The recipe, in three steps

The 2012 notes give the sequence: find or create a new market, monopolize it, then expand the monopoly over
time [CS183-04]. His own shortest version, 2014: "Start with a small market and dominate that first." [FQA14]
The AMA answer is almost word for word: "Start with focusing on a small market and dominate that market first."
[AMA14]

## Start with a market so small it looks worthless

> "You start with a really small market and you take over the whole market" [YCL5]

Then you expand "in concentric circles" [YCL5]. Going after a giant market on day one is, in his view, a sign
you haven't defined the category correctly [YCL5]. The 2014 Q&A gives the reason, paraphrased: big markets look full of
opportunity, but most of it goes to the others competing with you [FQA14].

**His four stories** (paraphrased from [YCL5]):

| Company | First market | What happened |
|---|---|---|
| Amazon | Books only | Then every other kind of e-commerce |
| eBay | Collectibles like Pez dispensers and Beanie Babies | Then auctions for everything |
| PayPal | eBay power sellers, "about twenty thousand people" [YCL5] (Dec 1999 to Jan 2000) | About a quarter to a third of them within a few months |
| Facebook | About ten thousand people at Harvard | "zero to sixty percent market share in ten days" [YCL5] |

He admits the PayPal team at first thought power sellers were terrible customers to have [YCL5].

**The inversion that fails,** per the notes: starting big and shrinking, as Pets.com, Webvan and Kozmo.com did
[CS183-04]. The 2005 to 2008 cleantech decks, he says, all opened with markets in the trillions, leaving the
company "a minnow in a vast ocean" [YCL5].

**Too small is also a failure.** PayPal's first idea, beaming money between Palm Pilots, had no competitors and
no real need: "But no one really needed it done, which was bad." [CS183-04, from Blake Masters' class notes]

## The four characteristics

The notes name them: brand, scale cost advantages, network effects and proprietary technology [CS183-04]. The
2014 lecture walks through the same four [YCL5].

### 1 · Proprietary technology: 10x on one dimension

> "you want to have a technology that's an order of magnitude better than the next best thing." [YCL5]

He calls this a "somewhat arbitrary rule of thumb" [YCL5]. His examples: Amazon had "over ten times as many
books"; PayPal cleared payments "more than ten times as fast" as checks; Google's search was an order of
magnitude better than rivals [YCL5]. Something totally new counts as an infinite improvement (our paraphrase).
The Q&A version: "a definitively superior solution to a specific problem." [FQA14]

### 2 · Network effects: hard to start

His tricky question: "why is it valuable to the first person who's doing something" [YCL5]. The notes' warning
case is Xanadu, the 1960s hypertext project that needed everyone to adopt it at once [CS183-02].

### 3 · Economies of scale

High fixed cost and low marginal cost make a business monopoly-like, and software is good at this "because the
marginal cost of software is zero." [YCL5]

### 4 · Brand: real, but not enough alone

"I never quite understand how branding works" [YCL5], he says, so he doesn't invest where it's only about the
brand, though he calls it a real source of value.

**Google, scored by him in 2014:** all four once, "maybe three and a half out of four now" [YCL5], with the
technology the weakest.

## Speed of adoption protects a small market

If adoption in a small market is too slow, others have time to enter and compete [YCL5]. **Our reading:** a
small market is only safe if you can take most of it before anyone notices.

## The fifth pattern: vertical integration

He names vertically integrated companies like Ford and Standard Oil as the other way inventors captured value,
because they need many pieces to fit together [YCL5]. On Tesla and SpaceX, he says the impressive part was
integration rather than a single 10x breakthrough, and calls vertical integration "a very under explored modality
of technological progress" [YCL5].

## Palantir, in his words

Palantir started with "a focus on the intelligence community, which is a small submarket" [YCL5], with
technology built around human and computer working together rather than replacing the analyst (our paraphrase).

## Frontiers beat disruption

> "Much better than to disrupt is to find a frontier and go for it." [CS183-04, from Blake Masters' class notes]

**Our reading:** "disrupt" points you at an incumbent, which is a competitor. A frontier has nobody on it yet.
Chapter 12 looks at where frontiers are.

---

## How to apply it (our reading)

1. **Name the first market by count.** A list you could print: 240 carriers, 20,000 power sellers, 10,000
   students. If you can't count it, it isn't small enough.
2. **Set a share target.** Our suggestion: plan to reach more than half of that first market within 12 to 18
   months. His examples moved faster [YCL5].
3. **Pick the one dimension** customers care about most and measure your number against the next best thing.
4. **Score the four characteristics** 0 to 2, today and in ten years (`templates/03-monopoly-scorecard.md`).
5. **Draw the first two concentric circles:** which adjacent market does the first one unlock, and why does
   owning the first make the second easier?
6. **Check for vertical integration:** which pieces would you have to own for the product to work at all?

**Worked numbers (fictional).** A startup sells inspection software to 1,800 elevator-maintenance firms. On the
metric customers care about (hours to produce a compliant report), it takes 0.5 hours against 6 for the next best
tool: 12x. Network effects: 0 today. Scale: 1. Brand: 0. Score 3 of 8. Circle one: elevator firms. Circle two:
escalator and lift inspectors, who use the same regulator forms. Plan: 900 firms (50%) in 18 months. If it takes
three years, a larger field-service vendor has time to copy the report format.

**Failure modes (our reading):**
- **A niche with no urgency.** Small, empty and unwanted, like the Palm Pilot idea [CS183-04].
- **10x on the wrong metric.** Pick the one customers pay for, not the one you're proudest of.
- **Network effects with no first-user value.** The Xanadu problem [CS183-02].
- **Brand as the plan.** He doesn't fund it alone [YCL5]; neither should you rely on it.

**Limits:** the 10x rule is his own rule of thumb, not a law [YCL5]. The four characteristics are a checklist,
not a score he publishes; the 0 to 2 scale is ours.

**Use it now:** `templates/03-monopoly-scorecard.md`, after `templates/02-market-reality-check.md`.

**Checks to run:**
1. Who is your first market, by name and count? Can you reach more than half of them within a year?
2. On which one dimension are you 10x better than the next best thing? Measured how?
3. Why would the very first user join before anyone else has?
4. Which of the four (tech, network, scale, brand) will you have in five years that you don't have today?
