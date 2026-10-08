# Worked example: a strategy session on "Coldmark"

> **Fictional.** Coldmark, its founders, its customers and every number below are invented to show how the skill
> works. Nothing here is a claim about any real company. Quotes from Thiel and from Blake Masters' class notes
> are real and cited.

## What the founder sent

```text
Run a Peter Thiel-style strategy session on my startup.

What we're building: Coldmark uses the temperature and door sensors already in refrigerated
trailers to prove how long a truck waited at a shipper's dock, then files the detention
invoice automatically.
Pitch: AI-powered detention recovery for refrigerated fleets (20 to 200 trucks) in the US Southeast.
First customers: 11 produce-hauling carriers in Georgia and Florida.
Who else serves them: freight audit firms, TMS add-ons, carriers doing it by hand.
Better than the alternative by: disputes won 81% with sensor evidence vs 22% with driver logs.
Price: 15% of detention recovered. Average customer pays $1,550/month. Gross margin 80%.
Cost to acquire: about $9,000 per customer (founder sales plus two trade shows).
Founders: me (CEO, 6 years as a dispatcher at a reefer carrier), CTO (met 4 months ago at a
hackathon), and an industry advisor with 15% who works on it one day a week.
Equity 50 / 35 / 15. Raising a seed: two investors want board seats, plus one independent.
My salary after the seed: $190k.
In 10 years: the system of record for dock time in cold-chain freight.
```

## What the skill returned

### Step 2 · The contrarian question

**Their answer:** *most carriers think detention pay is lost because shippers refuse to pay. The truth is it's
lost because carriers can't prove the wait, and the proof is already sitting in the trailer.*

**Verdict: a secret, about people and nature.** True (their dispute data), important (see X below), and the
industry treats unpaid detention as a cost of doing business. The human side: shippers have no reason to say
their docks are slow. The notes' test fits: "What secrets is nature not telling you? What secrets are people not
telling you?" [CS183-11, from Blake Masters' class notes]

**Mimesis check (our reading, on the fictional facts):** they didn't pick it because it's fashionable. In this
invented scenario, freight tech was out of fashion with their investors when they started. →
`references/09-mimesis-and-thinking-for-yourself.md`

### Step 3 · The market reality check

**The intersection test:**

| Drop | Market | Who else serves it | Size |
|---|---|---|---|
| Pitch | Reefer fleets, 20 to 200 trucks, Southeast, detention recovery | Nobody directly | 240 fleets |
| Drop Southeast | Same, whole US | 2 small startups | 3,100 fleets |
| Drop reefer | All mid-size fleets | Freight audit firms, factoring companies | 28,000 fleets |
| Drop detention | Freight billing and audit | Large, crowded | Crowded |

His question: "what is the actual market? So not what's the narrative of the market" [YCL5]. **Our reading:**
the real market is unrecovered detention pay for carriers whose trailers already log door and temperature data.
That's narrower than freight audit, and it's real: reefer trailers log the data, dry vans mostly don't. The
Southeast qualifier is just sequencing, not the market.

**First market to own:** the 240 produce carriers in Georgia and Florida. Share today: 11 of 240 (4.6%). The
model is PayPal's eBay power sellers, "about twenty thousand people" [YCL5], small enough to take quickly.

**X and Y:** an average customer (about 40 trucks) loses about $207k a year in unbilled detention, and
Coldmark recovers about 60% of it ($124k). At 15%, Coldmark keeps about $18,600. X is large and Y is a clear share. The risk is Y
falling if a rival offers 10%: X and Y are "completely independent variables" [YCL5].

### Step 4 · Monopoly scorecard

| | Today | In 10 years | Why |
|---|---|---|---|
| Proprietary tech | 1 | 1 | 81% vs 22% dispute win rate is 3.7x, not 10x. Time to file: 2 minutes vs 45, which is 22x |
| Network effects | 0 | 2 | Every customer adds dock-wait data on shippers. A shipper-level wait index gets "more robust" with scale [YCL5] |
| Scale | 1 | 2 | Marginal cost per extra fleet is near zero |
| Brand | 0 | 1 | Nobody in the industry knows the name yet |
| **Total** | **2/8** | **6/8** | |

**The 10x question:** "you want to have a technology that's an order of magnitude better than the next best
thing" [YCL5]. The dimension that clears it is time to file, not win rate. **Our reading:** lead with filing
time in the pitch; it's the 10x.

**First-user test:** network effects are "often very hard to get started" [YCL5]. Coldmark's first customer gets
full value on day one (their own recovered pay), so the network is a bonus, not a precondition. Good.

### Step 5 · Last mover

Rough DCF (invented): growing 120% a year now, slowing to 25% after year 5, discount rate 30%. About 70% of value
comes after year 10. That's the same shape as PayPal in 2001, when "about three quarters of the value of the
business as of 2001 came from cash flows in years 2011 and beyond." [YCL5]

**Why they could be the last mover:** the shipper dock-wait dataset. After three years it's the record shippers
and carriers both cite. **Biggest threat:** a telematics provider that already sits in the trailer bundling a
basic version for free. **Our reading:** the defence is the shipper data and the dispute history, not the
sensor reading, which is a commodity.

"why will this still be the leading company in ten, fifteen, twenty years from now" [YCL5]. Their answer, after
the session: because every detention dispute in cold-chain freight will be settled against their data.

### Step 6 · Distribution

| | Value |
|---|---|
| Revenue per customer per month | $1,550 |
| Gross margin | 80% |
| Lifetime (months, assumed; see caveat) | 40 |
| **CLV** | **$49,600** |
| Cost to acquire | $9,000 |
| CLV ÷ cost | 5.5 |

"you build a great business if CLV > CPA" [CS183-09, from Blake Masters' class notes]. Healthy on paper.

**Caveat (our reading):** with 11 customers, the oldest a year or so old, a 40-month lifetime can't be measured;
it's an assumption from about 2.5% monthly churn in a short window. One lost customer would move it a lot. At a
20-month lifetime, CLV is $24,800 and the ratio is 2.8, still above 1 but no longer comfortable. Treat CLV as a
range until there are at least two years of cohorts.

**Spectrum position:** about $18,600 a year, the low end of personal sales ($10k to $100k in the notes
[CS183-09]). Above that sits complex sales; below it, the missing middle. **Trade shows are the wrong channel**
at this price: half the $9,000 came from two shows that produced 3 of the 11 customers.

**The one channel:** freight factoring companies. They already buy carriers' invoices and want detention paid. One
factoring partner can introduce dozens of fleets. "It is very likely that one channel is optimal." [CS183-09,
from Blake Masters' class notes] Founder-led sales continues for the first market only.

### Step 7 · The founding

| Check | Finding | Flag |
|---|---|---|
| Cofounder prehistory | CEO and CTO met 4 months ago | **Yes.** "How did you meet, how long have you been working together" [CWT15] |
| Full-time | Advisor-founder works one day a week | **Yes.** The notes record that Thiel passed on YouTube in 2005 because the founders were part-time [CS183-06] |
| Equity | 50 / 35 / 15 | **Yes.** "if you don't want to split shares evenly then perhaps you should not be co-founders" [AMA14] |
| Board after seed | 2 founders + 2 investors + 1 independent = 5 | **Yes.** The notes: "The ideal board is probably three people: one VC and two founders." [CS183-06] |
| CEO pay | $190k | **Yes.** Founders Fund's 2012 rule in the notes: no CEO over $150k [CS183-06] |

**Our reading:** the advisor is an advisor, not a founder. Convert the 15% to an advisor grant with vesting. CEO
and CTO should agree a vesting schedule now, with no credit for the 4 months, and an even or close-to-even split
if both are full-time and essential.

### The session notes

```markdown
# Strategy session: Coldmark

**The secret:** carriers lose detention pay because they can't prove the wait, and the proof is already in
the trailer. · **Verdict:** secret

## The market, honestly
- Pitch market: reefer fleets 20 to 200 trucks, Southeast · Actual market: unrecovered detention for
  sensor-equipped fleets · First market to own: GA/FL produce carriers (240, share now 4.6%)
- X: ~$207k lost per average (40-truck) fleet per year · Y: ~$18,600 (15% of the ~$124k recovered)

## Monopoly scorecard
| | Tech | Network | Scale | Brand | Total |
| Today | 1 | 0 | 1 | 0 | 2/8 |
| In 10 years | 1 | 2 | 2 | 1 | 6/8 |

## Last mover
- ~70% of value after year 10 · Last mover via the shipper dock-wait dataset · Threat: telematics bundling

## Distribution
- CLV $49,600 (assumed 40-month lifetime; $24,800 at 20 months) vs cost $9,000 · Personal sales, low end · The
  one channel: factoring partners

## Founding
- Flags: 4-month cofounder history, part-time founder at 15%, uneven split, 5-person board, $190k CEO salary

## This quarter
1. Restructure the cap table: advisor grant, vesting for both founders. Owner: CEO.
2. Sign one factoring partner and drop trade shows. Owner: CEO.
3. Ship the shipper dock-wait index to all 11 customers. Owner: CTO.

**The question to answer next:** why won't a telematics provider bundle this for free?

## Where to be careful
- Board size, CEO pay and vesting rules come from 2012 class notes, not his own words, and are dated 2012. They
  were Founders Fund heuristics for US venture-backed startups; the $150k figure is in 2012 dollars. Treat them
  as strong defaults, not fixed rules.
- The DCF inputs are guesses. The point is the shape (most value after year 10), not the number.
- The 40-month lifetime is an assumption from 11 young customers, not a measurement.
```

## The result (invented)

Over the next quarter, Coldmark moved the advisor to a vesting advisor grant, kept the board at three for the
seed, and set the CEO salary at $140k. One factoring partner introduced 34 fleets; 19 signed. Share of the first
market went from 4.6% to 12.5%. The telematics question is still open, and it's the first item at the next
session.
