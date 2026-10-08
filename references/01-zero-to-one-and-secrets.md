# 01 · Zero to one, and secrets

Citation IDs are in `SOURCES.md`: `[YCL5]` 2014 Stanford lecture · `[WSJ14]` WSJ essay · `[NPR14]` NPR
interview · `[CWT15]` Conversations with Tyler · `[AMA14]` Reddit AMA · `[FQA14]` 2014 Q&A · `[HAM16]` 2016
commencement speech. These are Thiel's own words. `[CS183-nn]` are **Blake Masters' class notes** from the 2012
course: near-verbatim, not a transcript, and labelled as notes wherever quoted.

## Zero to one vs one to n

> "It's much easier to do horizontal progress, which I describe as globalization, copying things that work
> going from one to n, versus vertical progress, technology, doing new things, going from zero to one." [CWT15]

On radio the same year he gave the examples of a first airplane, a first home computer and the first iPhone
[NPR14]. The 2012 notes add that going from 0 to 1 is "qualitatively different, and almost always harder, than
copying something n times." [CS183-01, from Blake Masters' class notes]

## Every moment happens once

> "every moment in the history of science, technology, business, I believe, happens only once. The next Mark
> Zuckerberg won't start a social network, the next Larry Page won't start a search engine." [CWT15]

In the 2014 lecture he put the consequence bluntly: "If you are copying these people, you are not learning from
them." [YCL5]

**Our reading:** a playbook of what worked for someone else is a playbook for 1 to n. This repo gives you
questions, not answers to copy.

## The contrarian question

The interview question he likes: "tell me something that is true that very few people agree with you on"
[NPR14]. The business version: "What valuable company is nobody building?" [WSJ14] He gives a version for every
role: "the contrarian investor question is what great investments does nobody like" [CWT15].

Why it's hard, paraphrasing his NPR answer: new truths are hard to find, and acting on them takes courage
because it means going against social convention [NPR14]. And people hold back: "Everyone has things they
believe to be true that other people won't agree with you on. But they're not things you want to say." [CWT15]

**His own answer** (2014): "Most people believe that capitalism and competition are synonyms, and I think they
are opposites." [AMA14]

**Where the question comes from.** In the 2012 notes it grows out of three questions (what is valuable, what can
I do, what is nobody else doing), rephrased as "What important truth do very few people agree with you on?" The
shape of a good answer, in the notes: "Most people believe in X. But the truth is !X." [CS183-01, from Blake
Masters' class notes]

## Secrets: easy, hard, impossible

The 2012 *Secrets* class, in Blake Masters' notes, defines them: "Secrets are unpopular or unconventional
truths." [CS183-11]

| Kind of truth | What it is (paraphrasing the notes [CS183-11]) | Worth your time? |
|---|---|---|
| Conventions | Easy truths everyone already knows | No edge |
| Secrets | Hard but findable | Yes |
| Mysteries | Impossible for now | Not as a business |

The notes call the biggest secret of all the fact "that there are many important secrets left." [CS183-11, from
Blake Masters' class notes] They name four drivers of disbelief in secrets: incrementalism, risk aversion,
complacency and egalitarianism [CS183-11].

**Two places to look**, per the notes: "There are secrets of nature and then there are secrets about people."
For the human kind, the notes ask what is explicitly forbidden and what is "implicitly off-limits or taboo"
[CS183-11, from Blake Masters' class notes]. The PayPal example in the notes: banks don't publicise how much fraud
costs them [CS183-11].

## What to do with a secret

> "If you don't tell anyone, you'll keep the secret safe. But no one will work with you." [CS183-11, from
> Blake Masters' class notes]

The notes' rule of timing: "The bigger the secret and the likelier it is that you alone have it, the more time
you have to execute." [CS183-11]

## A counterfactual sense of mission

> "Always having a counterfactual sense of mission is important. If we weren't doing this, nobody else in the
> world would be doing this." [CWT15]

He tied it to doing something new in a 2014 Q&A: defining yourself by a competitor means giving up the chance to
"do something new in the world that won't be done unless you are the one to do it." [FQA14]

## Big trends are not secrets

Asked about virtual reality in 2014: "Massive trend, but I think the valuable 0-1 companies will identify a more
concrete area of focus within this large trend." [AMA14] On AI in 2015: "It feels like a bit of an extreme
consensus that AI is just around the corner" [CWT15].

## Why newcomers find secrets

His PayPal lesson, in his own words: "You needed to be naive enough to think that new things could be done."
[FQA14] In 2016 he added that the more banking experience someone had, the more certain they were PayPal would
fail [HAM16].

---

## How to apply it (our reading)

These steps are ours, built on his question [NPR14, WSJ14] and the notes' secret/convention/mystery split
[CS183-11].

1. **Write ten candidate beliefs** in the notes' shape: most people believe X, but the truth is !X.
2. **Kill the conventions.** For each, ask three people in your field. If two or more agree straight away, it's a
   convention.
3. **Kill the mysteries.** If you can't name an experiment, customer conversation or dataset that could confirm
   it in 90 days, it's a mystery for now.
4. **Rank what's left by X** (chapter 02): if it's true, how much value does it unlock, and for whom?
5. **Run the counterfactual** [CWT15]: if you don't build it, who will, and when? Name them.
6. **Decide who to tell** [CS183-11]: the people you need to execute, and nobody else yet.

**Worked scenario (fictional, invented numbers).** A founder lists ten beliefs about dental clinics. Seven get
instant agreement from clinic owners (conventions). One (*patients will pay for at-home aligner checks*) already
has four funded startups, so it's a trend. One can't be tested yet. The survivor: *most clinics think no-shows
are a patient problem; the truth is they're a scheduling-software problem, because 60% of no-shows booked more
than 30 days out.* Two of three owners disagree, the founder can test it on 3 clinics' booking logs in a month,
and no incumbent has a reason to say it. That's a candidate secret.

**Failure modes (our reading):**
- **Contrarian for its own sake.** The notes warn that doing the opposite of the herd "is just as random and
  useless" when the herd isn't thinking at all [CS183-02, from Blake Masters' class notes]. Disagreement isn't
  evidence.
- **A trend in disguise.** If investors already have a slide for it, it's a convention.
- **A secret with no business.** True and unpopular, but no one pays (chapter 02's X without Y).
- **Telling too many people too early,** or nobody at all.

**Limits:** the secret/mystery split and the timing rule come from the 2012 notes, not his own transcript. He
gives no method for finding secrets; the steps above are ours.

**Use it now:** `templates/01-secret-and-contrarian-truth.md`.

**Checks to run:**
1. Fill in "Most people believe in X. But the truth is !X." [CS183-01] Would most smart people in your field
   disagree with your !X?
2. Is your secret about nature, about people, or both?
3. If you didn't build this, would anyone else in the next five years? Who?
4. Is your idea a trend everyone sees, or a specific, unpopular piece inside it?
