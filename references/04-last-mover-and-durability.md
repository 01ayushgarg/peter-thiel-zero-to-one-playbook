# 04 · Last mover: durability beats growth

Citation IDs are in `SOURCES.md`. `[YCL5]` and `[FS12]` are Thiel's own words. `[CS183-nn]` quotes are **from
Blake Masters' class notes**, not a transcript.

A monopoly for a moment isn't enough; the critical thing, he says, is to have one that lasts [YCL5].

## First mover vs last mover

> "the better framing is you want to be the last mover." [YCL5]

His examples [YCL5]: Microsoft was the last operating system for decades, Google the last search engine, and
Facebook would be valuable if it turned out to be the last social network. The 2012 notes have the same idea: "You
have to be durable." [CS183-03, from Blake Masters' class notes]

Asked whether last mover implies there was competition first, he answers that the winners were first on the
dimension that mattered: Google with its automated ranking, Facebook as "the first one to get real identity"
[YCL5].

## Most of the value is far in the future

When growth is well above the discount rate, a discounted cash flow puts "most of the value" "far in the future"
[YCL5].

### The PayPal DCF, March 2001

His own exercise, paraphrased: PayPal was about 27 months old, growing 100% a year, with future cash flows
discounted at 30%. The result: "about three quarters of the value of the business as of 2001 came from cash flows
in years 2011 and beyond." [YCL5]

| Input (PayPal, March 2001) | Value [YCL5] |
|---|---|
| Months in business | about 27 |
| Growth rate | 100% a year |
| Discount rate | 30% |
| Share of value from 2011 and later | about three quarters |

The 2012 notes add a follow-up: the discount rate turned out lower and growth was still 15%, so most of the value
now looked like it would come around 2020 [CS183-03]. For 2014's startups he puts the share from 2024 onward at
three quarters to 85% [YCL5].

## We overvalue growth and undervalue durability

> "one of the things that we always over value in Silicon Valley is growth rates and we undervalue durability."
> [YCL5]

His reason, paraphrased: growth can be measured precisely now, while whether the company exists in a decade is
qualitative, yet it dominates the value [YCL5].

## Each monopoly trait has a time dimension

"So there's a time dimension to all these characteristics." [YCL5] Network effects strengthen as the network
grows. Proprietary technology can be overtaken: 1980s disk-drive makers led the world and were replaced within a
couple of years (our paraphrase [YCL5]). So you need to explain why yours is "the last breakthrough or at least
the last breakthrough for a long time" [YCL5], or how you'll keep improving faster than anyone can catch up.

**A durable incumbent, seen from outside.** In the 2012 Fortune debate he described Google's investment case as
"a bet that there will be no one else who will come up with a better search technology." [FS12] **Our reading:**
that's the last-mover bet stated plainly. Chapter 12 covers the other side of his argument: a company that stops
finding new things to do with its cash.

## Timing: make the last great development

The notes' version: enter the field when you can make the last great development, "after which the drawbridge
goes up and you have permanent capture." [CS183-04, from Blake Masters' class notes] And if nothing has happened
in an industry for a long time, a dramatic improvement is less likely to be repeated against you [CS183-04].

## Study the endgame

In chess, he notes, white's first-move edge is small; you want to be the last mover who wins [YCL5]. He quotes
Capablanca, "You must begin by studying the end game." [YCL5], and asks:

> "why will this still be the leading company in ten, fifteen, twenty years from now" [YCL5]

---

## How to apply it (our reading)

**A rough last-mover analysis.** The method is ours; the DCF framing is his [YCL5].

1. **Build a three-stage DCF:** profit next year, growth for years 1 to 5, years 6 to 10, and after 10, plus a
   discount rate.
2. **Compute the share of value after year 10.** If it's over 50%, durability matters more than this year's
   growth.
3. **For each advantage, say whether it strengthens or decays** with time.
4. **Name the next breakthrough after yours,** who could make it, and why they won't (or what you'll do).
5. **Write the endgame:** the market in 10 to 20 years, how many serious players, and why you're the last one.
6. **Pick one durability metric** to track next to growth (for example, three-year retention or share of the
   category).

**Worked numbers (fictional, rounded).** Profit next year $1m. Growth 80% a year for five years, 30% for years 6
to 10, then 10% forever. Discount rate 20%. Years 1 to 10 are worth about $38m in today's money; everything after
year 10 is worth about $69m, so roughly 65% of value comes after year 10. Cut the post-year-10 growth to 0% (a
rival catches up) and total value falls by about a third, with nothing in this year's numbers changing. That's
his point: the number you can't measure yet carries most of the value.

**Failure modes (our reading):**
- **Treating the DCF as a forecast.** It's a way to see what you're betting on, not a valuation.
- **Durability claimed, not shown.** "Network effects" with no mechanism that gets stronger as you grow.
- **Being first, not last.** First to market, then overtaken by the one who got the key dimension right.
- **Growth theatre.** Tracking growth because it's easiest to measure [YCL5].

**Limits:** the PayPal inputs are his rough figures from memory in 2014, and the notes give a different
follow-up. The worked DCF above is invented and rounded.

**Use it now:** `templates/06-ten-year-test.md`.

**Checks to run:**
1. What share of your value, on an honest DCF, comes after year 10? What would have to be true for those cash
   flows to exist?
2. Which of your advantages get stronger with time, and which decay?
3. Who could make the next breakthrough after yours? Why wouldn't they?
4. Are you tracking growth because it matters most, or because it's easiest to measure?
