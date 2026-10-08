# Peter Thiel's Zero to One Playbook

**An unofficial, fully sourced playbook and AI skill that runs Peter Thiel's strategy questions (the contrarian
question, competition vs monopoly, the last mover, distribution, the founding) on your startup. Built from his
own recorded words and clearly labelled notes of his Stanford class.**

Peter Thiel co-founded PayPal and Palantir, made the first outside investment in Facebook, and started the
venture firm Founders Fund. In 2012 he taught CS183: Startup at Stanford, and student Blake Masters published
near-verbatim notes of every class, which grew into the 2014 book *Zero to One*. This repo turns those notes,
his 2014 Stanford lecture, his WSJ essay, his Reddit AMA, his interviews, a 2012 debate and a 2016 commencement
speech into a method you can run on your own company this week.

> "All happy companies are different: Each one earns a monopoly by solving a unique problem. All failed
> companies are the same: They failed to escape competition."
> Peter Thiel, "Competition Is for Losers", The Wall Street Journal (2014) [WSJ14]

> ⚠️ **Unofficial.** Not written, reviewed or endorsed by Peter Thiel, Blake Masters, Founders Fund or any of his
> companies. It's a structured guide in our own words, with short credited quotes and a link to every source.
> Quotes from the class notes are labelled as notes, not as his verbatim words. It covers startups, business and
> technology only: no politics.

---

## What's inside

### The playbook

| # | Chapter | What you'll learn |
|---|---|---|
| 00 | [Who he is, for this playbook](references/00-who-is-peter-thiel.md) | Scope, the two kinds of source, and his own caveats |
| 01 | [Zero to one, and secrets](references/01-zero-to-one-and-secrets.md) | 0 to 1 vs 1 to n · the contrarian question · conventions, secrets, mysteries · who to tell |
| 02 | [Competition is for losers](references/02-competition-is-for-losers.md) | Create X, capture Y% · airlines vs Google · the lies about markets: union vs intersection · Castro Street |
| 03 | [Building a monopoly](references/03-building-a-monopoly.md) | Start small and dominate · concentric circles · 10x tech · network effects · scale · brand · vertical integration |
| 04 | [Last mover and durability](references/04-last-mover-and-durability.md) | Value far in the future · the PayPal DCF (2001) · growth vs durability · study the endgame |
| 05 | [Distribution](references/05-distribution.md) | CLV vs acquisition cost · the sales spectrum · the missing middle · viral · one channel |
| 06 | [The founding](references/06-the-founding.md) | Thiel's law · cofounders · a three-person board · equity and vesting · the $150k CEO rule |
| 07 | [The power law](references/07-the-power-law.md) | VC math · one company returns the fund · one revenue source · applying it to your own choices |
| 08 | [Definite optimism and planning](references/08-definite-optimism-and-planning.md) | You are not a lottery ticket · the four quadrants · plans vs iteration · his lean startup skepticism |
| 09 | [Mimesis and thinking for yourself](references/09-mimesis-and-thinking-for-yourself.md) | Ape and imitate · competition as validation · the Kissinger line · the law-firm story · rivals become alike |
| 10 | [Founders and teams](references/10-founders-and-teams.md) | Founder as victim, founder as god · startups as monarchies · culture · hiring |
| 11 | [The questions](references/11-the-questions.md) | Every question he asks, in one bank, each sourced · the 2012 cleantech list |
| 12 | [Stagnation, atoms and frontiers](references/12-stagnation-atoms-and-frontiers.md) | Bits vs atoms · big tech as a stagnation signal (the Schmidt debate) · cleantech · where the frontiers are |
| 13 | [Tracks, credentials and the Fellowship](references/13-tracks-credentials-and-the-fellowship.md) | The track and the law firm · college and credentials · the Thiel Fellowship · inexperience as an edge |

### Templates

| Template | Use it to |
|---|---|
| [01 Secret and contrarian truth](templates/01-secret-and-contrarian-truth.md) | Write your unpopular truth and check it's a secret, not a convention or a trend |
| [02 Market reality check](templates/02-market-reality-check.md) | Run the intersection and union tests, size the real market and your share |
| [03 Monopoly scorecard](templates/03-monopoly-scorecard.md) | Score tech, network effects, scale and brand, today and in ten years |
| [04 Distribution math](templates/04-distribution-math.md) | Compare lifetime value with acquisition cost and find your place on the sales spectrum |
| [05 Founding checklist](templates/05-founding-checklist.md) | Check cofounders, equity, vesting, board and cash pay before they're hard to fix |
| [06 Ten-year test](templates/06-ten-year-test.md) | Run a last-mover analysis: where your value comes from and why you'll still lead |
| [07 Frontier scan](templates/07-frontier-scan.md) | Compare fields on bits vs atoms, last big change, rivals and blockers |
| [08 Track audit](templates/08-track-audit.md) | Check whether your last five choices were decisions or the next competition |
| [09 Definite plan](templates/09-definite-plan.md) | Write a one-page plan with an end state, three steps and one dominant line |

### Worked example

[A full session, start to finish](examples/01-worked-session.md): a fictional cold-chain freight startup with
invented numbers, run through the whole skill. Its 10x was hiding in the wrong metric, and its founding had five
flags.

---

## How to use this

### 1. Run it as an AI skill (10 minutes)

**Install** into your agent's skills folder. For Claude Code:

```bash
git clone https://github.com/01ayushgarg/peter-thiel-zero-to-one-playbook \
  ~/.claude/skills/peter-thiel-zero-to-one-playbook
```

If your agent doesn't read skill folders, paste `SKILL.md` into the chat and attach the chapters it asks for.

**Then ask for a strategy session.** Copy and fill in:

```text
Run a Peter Thiel-style strategy session on my startup.

What we're building (one sentence):
What we believe that most people in our field don't:
Our first customers (who, and how many exist):
Who else serves them today:
How much better we are than the next best thing, on what:
Price, gross margin, customer lifetime, cost to acquire a customer:
Founders (how we met, how long together), equity split, board, CEO salary:
Where the company is in 10 years:
```

**You get back:** your secret in one sentence (or a flag that you don't have one yet), the actual market vs the
pitch market, a monopoly scorecard for today and ten years out, a rough last-mover analysis, your distribution
math and the one channel to focus on, any founding flags, three actions for this quarter, and the one question
you still need to answer. Every point cites the lecture, essay, interview or class note it comes from.

**Other things you can ask:**
- *"Is this a secret, or just a trend?"*
- *"Is my market real, or a fictional intersection?"*
- *"Score my company on the four monopoly characteristics."*
- *"Will we still be the leading company in 20 years? Why or why not?"*
- *"Is our CLV high enough for the channel we're using?"*
- *"Check our cofounder setup, board and equity before we raise."*
- *"Am I competing because it's the right fight, or because everyone else is?"*

### 2. Use the templates (30 minutes, no AI)

1. [Secret and contrarian truth](templates/01-secret-and-contrarian-truth.md) before you commit to an idea.
2. [Market reality check](templates/02-market-reality-check.md) before you write the pitch.
3. [Monopoly scorecard](templates/03-monopoly-scorecard.md) once a quarter.
4. [Distribution math](templates/04-distribution-math.md) before you spend on a channel.
5. [Founding checklist](templates/05-founding-checklist.md) before you incorporate or raise.
6. [Ten-year test](templates/06-ten-year-test.md) once a year, or when growth is the only number anyone talks
   about.
7. [Frontier scan](templates/07-frontier-scan.md) when you're choosing what to work on.
8. [Track audit](templates/08-track-audit.md) before a big career or company choice.
9. [Definite plan](templates/09-definite-plan.md) once a year, or when the roadmap is only experiments.

### 3. Read it

Start with chapter 01 if you're looking for an idea (then 12 and 13), 02 and 03 if you have one and want to test
it, 05 if growth has stalled, 06 if you're setting up the company or raising, and 09 if you suspect you're in the
wrong fight. Every chapter ends with a short method in our own words: steps, a worked example, failure modes and
limits, all labelled as our reading.

**His own caveat:** "If I give you some general answer, and everybody could follow it, then if everybody followed
that answer, it would be the wrong thing to do." [CWT15] Use the questions, not a formula.

---

## How it stays honest

- **His own words first:** the 2014 lecture, the WSJ essay, NPR and WBUR interviews, Conversations with Tyler,
  a 2014 Q&A, the 2012 Schmidt debate, the 2016 Hamilton speech, two essays and his Reddit answers. No
  biographies, no listicles of Thiel's rules.
- **Notes are the weak point, and we say so:** chapters 05, 06, 07 and 10 still rest mainly on the 2012 class
  notes, because his later first-party words on those topics are thin. Each of those chapters says so at the
  top.
- **Class notes labelled every time:** the 2012 CS183 notes are Blake Masters' write-up, not a transcript. Every
  quote from them says so.
- **Guests aren't Thiel:** Levchin, Hoffman, Andreessen, Graham and other guests are named when their views
  appear. Class 8 was given by Bruce Gibney and is labelled as his.
- **The book isn't a source:** *Zero to One* isn't quoted except for lines in its WSJ excerpt. Its list of
  questions isn't reproduced.
- **Founders Fund's manifesto isn't his:** the archived page is bylined "By Bruce Gibney" [FF11, see
  `SOURCES.md`], so it isn't quoted.
- **How quotes were checked:** we saved plain-text copies of every source and ran a script confirming each
  quote is an exact substring of the source it cites (allowing only quote-mark, dash and whitespace
  differences, with three dots marking trims), and that none is over 60 words. Those text copies are the
  publishers' copyright and aren't shipped, so the check can't be rerun from this repo; every quote has a
  source ID and a link so you can check it by hand.
- **Short quotes, more paraphrase:** no quote is over 60 words, and no single short work is quoted at more than
  about a tenth of its length. Longer passages are paraphrased and cited.
- **Dated numbers stay dated:** 2012 class figures, as of May 2014 for Google, PayPal in March 2001. Rules from
  the 2012 notes ($150k CEO pay, three-person board, vesting) say when they apply.
- **No politics:** where a source turns political (parts of the debate, the radio interview, the op-ed), those
  passages are left out.
- **Our own reading is marked**, never presented as his words.

## Sources

The full list, with dates and links, is in [`SOURCES.md`](SOURCES.md):

How to Start a Startup, Lecture 5: Competition is for Losers (Stanford CS183B, 2014) · "Competition Is for
Losers", The Wall Street Journal (2014) · NPR Weekend Edition (2014) · On Point, WBUR (2014, partial
transcript) · Q&A with Entrepreneur, via Fortune (2014) · Reddit AMA (2014) · Conversations with Tyler (2015,
and the Girard passages of 2024) · Fortune Brainstorm Tech debate with Eric Schmidt (2012) · "The End of the
Future", National Review (2011) · "The New Atomic Age We Need", The New York Times (2015, technology lines
only) · Hamilton College commencement (2016) · Blake Masters' notes of CS183: Startup, classes 1 to 19
(Stanford, 2012). 12 first-party sources plus 19 class-note posts.

## License

- **Our text** (chapters, skill, templates, structure): [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
- **Quotes** remain Peter Thiel's words, Blake Masters' notes and their publishers'. They're short, credited
  excerpts for commentary and are **not** covered by this license.

See [`LICENSE`](LICENSE).

## Corrections

Spot a misquote, a mislabelled speaker or a broken link? Open an issue with the source ID and the passage.
