# 05 · Distribution: the product doesn't sell itself

Citation IDs are in `SOURCES.md`. **This chapter rests mostly on one source: Blake Masters' notes of the 2012
class on distribution [CS183-09].** They are labelled on every quote and are not a transcript. His own later
words on distribution are thin; the few that exist ([AMA14], [YCL5], [HAM16]) are used where they fit. In
CS183-10 and CS183-15, guests were present; only lines the notes attribute to Thiel are used as his.

The notes call distribution "the single topic whose importance people understand least." [CS183-09, from Blake
Masters' class notes]

## The best product doesn't always win

The class opened by attacking the belief that the best product always wins, and the claim that a product sells itself is, per the notes,
"almost never true." [CS183-09, from Blake Masters' class notes] When a successful
company says it does no sales at all, the notes have Thiel suggesting that the claim is itself a sales pitch
[CS183-10].

His own later aside fits the same view of selling as a skill: in Silicon Valley, a suit in a pitch meeting
"makes you look like someone who is bad at sales and worse at tech." [AMA14]

## The math: lifetime value vs acquisition cost

The notes' rule: "you build a great business if CLV > CPA." [CS183-09, from Blake Masters' class notes] CLV
is revenue per customer, times gross margin, times average lifetime. Their example, paraphrased: a $40-a-month
phone plan kept for 24 months is $960 of revenue; at a 40% margin, CLV is $384, so you need to acquire the
customer for less than that [CS183-09].

| Input | Notes example [CS183-09] | Yours |
|---|---|---|
| Revenue per customer per month | $40 | |
| Lifetime (months) | 24 | |
| Gross margin | 40% | |
| **CLV** | **$384** | |
| Maximum you can pay to acquire | under $384 | |

## The sales spectrum

As the value of each sale rises, the notes say, selling becomes more people-intensive [CS183-09]:

| Deal size | Channel | Examples in the notes [CS183-09] |
|---|---|---|
| $1m and up (Palantir: $1m to $100m) | Complex sales, led by the founder | SpaceX, Palantir, Knewton |
| $10k to $100k | Personal sales, a repeatable process | Yammer, ZocDoc |
| Below that, above consumer prices | The missing middle: often no channel works | Small businesses; Intuit reached them |
| A couple of dollars and up | Marketing and advertising | Priceline, Google ads, Zynga |
| Free or near it | Viral | PayPal, Hotmail, Dropbox |

**Complex sales.** Palantir's version in the notes: engineers deployed with customers who double as sellers,
"Just don't call them salespeople." [CS183-09]

**The missing middle.** The notes warn of "a large zone in the middle in which there's actually no good
distribution channel to reach customers." [CS183-09, from Blake Masters' class notes]

**Our illustration, not his figure:** a product priced around a couple of thousand dollars a year often sits in
that zone. It's too cheap to pay for a salesperson's time and too expensive for most people to buy from an ad.
The exact boundaries depend on your sales cycle and margin; work them out with the template.

**Enterprise deal sizes.** In a later class, per the notes, Thiel says customers rarely do a deal 10x your
largest so far, and "Maybe 2x your biggest deal is a more realistic hope." [CS183-15, from Blake Masters' class
notes, Thiel speaking] So start with the smallest customer who is also a good reference [CS183-15].

## Viral: PayPal's 7% a day

From his own AMA: "PayPal was growing at 7%/day at the time of the launch (Oct 99-Apr 2000, from 24 users to 1
million)" [AMA14]. In 2016 he recalled that the first users were simply the company's own staff [HAM16].

How, per the notes: $10 for signing up and $10 per referral, which made each customer cost about $20 [CS183-02].
The notes add that this worked out but "probably isn't" the best way to run a company [CS183-02].

The first high-velocity segment was eBay power sellers [CS183-09], the same group he describes in his own words
in 2014 as about twenty thousand people [YCL5]. Viral, per the notes, has to be in the product: "There is no viral
marketing add-on." [CS183-09, from Blake Masters' class notes]

## One channel, not five

> "Poor distribution—not product—is the number one cause of failure." [CS183-09, from Blake Masters' class
> notes]

The notes say one channel is usually optimal, most businesses get none to work, and trying several without
nailing one is fatal [CS183-09]. Great distribution alone can even give "a terminal monopoly" [CS183-09], with
Intuit as the example.

## Sales is hidden

> "If you don't see any salespeople, you are the salesperson." [CS183-09, from Blake Masters' class notes]

The notes support this with 2012 Oracle pay data: a sales manager earned a bonus roughly thirteen times an
engineer's at the same experience level [CS183-09] (our arithmetic from the notes' figures). Distribution also
covers selling the company to recruits, investors and the press [CS183-09].

Users before revenue can be the right order, in his own words: "The right strategy is often to scale users
before scaling revenues." [AMA14]

---

## How to apply it (our reading)

1. **Compute CLV** from real numbers: revenue per month, gross margin, and lifetime from observed churn.
2. **Compute acquisition cost per channel,** not blended: spend in the last 90 days divided by customers it
   brought in.
3. **Place your yearly price on the spectrum.** Ask whether that channel's cost per sale fits under your CLV.
4. **Pick one channel** with the best CLV-to-cost ratio and a path to scale. Stop or freeze the rest for a
   quarter.
5. **If you sell big deals,** set the next target at no more than about 2x your largest [CS183-15].
6. **If you count on viral,** write the user action that necessarily brings in another user. If there isn't
   one, it isn't viral [CS183-09].

**Worked numbers (fictional).** A B2B tool charges $180 a month at 75% gross margin, and churn implies about 20
months of lifetime: CLV is $2,700. Paid search brings customers at $1,900 (ratio 1.4). A two-person sales team
costs $260,000 a year and closes 60 customers: $4,333 each (ratio 0.6). Partner referrals cost $700 each (ratio
3.9) but only 5 a month. The price (about $2,160 a year) sits in what the notes call the missing middle. Our
suggestion: freeze the sales team, push referrals to see if they scale, and keep search as the fallback.

**Failure modes (our reading):**
- **CLV from hope.** Lifetime estimated before anyone has churned.
- **Blended CAC.** A cheap channel hides an expensive one.
- **The missing middle, ignored.** A salesperson on a product that can't pay for one.
- **Viral as a feature request.** An invite button on a product nobody needs to share.

**Limits:** almost every rule here is from the 2012 notes, dated 2012, and labelled. The ratio thresholds in the
template and the price illustration are ours.

**Use it now:** `templates/04-distribution-math.md`.

**Checks to run:**
1. What is your CLV, and what does it cost you to acquire a customer today? Show both numbers.
2. Where on the sales spectrum is your price? Is it in the missing middle?
3. Which single channel works best right now? What would you stop doing to focus on it?
4. Is the core use of your product inherently viral, or are you hoping virality can be added later?
