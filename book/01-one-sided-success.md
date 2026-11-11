# Chapter 1 — The Problem with One-Sided Success

> **An OKR can be perfectly measured, fully achieved, and still represent a business failure.**

## A measurement is a view, not the whole system

Objectives and Key Results are attractive because they translate intentions into observable changes. Instead of asking whether a team worked hard, they ask whether something important actually changed.

But even an outcome metric captures only part of reality. A sales organization might measure new business written; a development organization might measure how quickly changes reach production. Both could improve dramatically while customers, reliability, profitability, or future performance deteriorate.

This is not necessarily the result of dishonesty. A team can faithfully pursue its assigned goal and still cause damage elsewhere. The system of goals may be defective even when everyone's behavior is understandable.

Balanced OKRs begins with a simple correction: **measure the desired improvement, identify what must not deteriorate, and retain enough diagnostic information to explain the result.**

## Example: the hidden cost of new business

Imagine a sales initiative that improves new-policy volume this quarter. The scorecard is green, the team is congratulated, and the campaign expands.

A year later, the acquisition cohort renews at a lower rate, produces more complaints, and yields weaker contribution margin. The original quarterly result was real, but it was not a complete measure of success.

A balanced formulation asks:

- Did we attract customers whose needs are served by the product?
- Does additional volume produce economically sustainable business?
- Are cancellation and renewal outcomes healthy for comparable cohorts?
- Which lead sources or sales practices appear associated with the difference?

The objective still aims for growth. Balance does **not** mean giving every possible metric equal weight or reducing ambition until no tradeoff exists. It means making material adverse tradeoffs visible and deciding which are unacceptable.

## Example: the hidden cost of velocity

Now imagine a software organization rewarded for deployment frequency and shorter lead times. Teams reduce batch sizes and automate releases. That can be genuine progress.

But if the organization also starts deferring tests, shipping changes without adequate observability, or tolerating more frequent production incidents, velocity is no longer the whole story.

A guardrail for change failure rate or recovery time helps distinguish better delivery capability from faster production of instability. A diagnostic view of incident causes can show whether the problem lies in process, architecture, testing, or change composition.

The important design choice is that a severe reliability regression cannot be **offset** by an exceptionally strong velocity number.

## Three ways a metric can fail

### 1. People game the measure

When an activity count becomes a target, people may maximize it rather than its intended purpose: more calls, more tickets closed, more deploys. Gaming can be intentional or an ordinary adaptation to management expectations.

### 2. Teams optimize locally

One department improves its results by shifting costs, risk, or work to another. Sales can increase throughput while underwriting absorbs rework. Product teams can demand more features while shared platform teams incur an unsustainable dependency load.

The local result can be genuine. The organizational result can still be negative.

### 3. The measure stops meaning what it used to

A useful leading indicator can decay when product, market, or organizational behavior changes. A recurring OKR can survive long after the causal relationship that justified it has weakened.

This third failure mode matters because merely policing manipulation will not solve it. The organization must periodically **revalidate the measurement itself**.

## Why extra key results are not always the answer

A tempting solution is to keep adding metrics until the scorecard appears complete. But more key results can make goals harder to interpret and easier to negotiate away.

Balanced OKRs therefore distinguishes three primary roles:

1. **Objective:** the meaningful change sought.
2. **Key Results:** measurable evidence that the desired change occurred.
3. **Guardrails:** constraints on unacceptable damage elsewhere.

Diagnostics are optional supporting analyses for evaluating guardrails, not a separate score or fourth component.

A guardrail is not just another score that can be averaged with other scores. Supporting diagnostic analysis is not another target to maximize. Keeping these roles distinct reduces the temptation to make every measurement into a contest.

## Guardrails require judgment

Not every tradeoff is avoidable, and no metric is perfect. Organizations must choose meaningful guardrails, baseline them appropriately, determine tolerances, and specify how to handle missing data.

A guardrail should focus on **material harm**, not every small fluctuation. Statistical noise, differences between customer cohorts, and changing conditions all complicate interpretation. When a threshold is breached, the appropriate response is review and diagnosis, not an automatic accusation of failure or misconduct.

Some boundaries—such as legal compliance or critical safety requirements—are obligations regardless of OKR design. Labeling them as guardrails may make them visible in the review, but does not make them negotiable.

## Behavior changes even without bonuses

Separating OKR scoring from compensation reduces direct incentives to sandbag or manipulate metrics. It does not remove the desire for status, advancement, leadership approval, or resources.

Leaders should therefore separate three judgments: whether an outcome occurred, whether the proposed objective was worthwhile, and whether people made sound decisions with the information available. A well-designed experiment that disproves an intervention can be more valuable than an easy target achieved without learning.

## Toward a balanced operating system

A robust goal-setting approach needs more than quarterly numerical results. It needs explicit accountability for dependencies, follow-up on long-term consequences, and permission to revise or retire measurements that stop reflecting the business.

Balanced OKRs is an invitation to ask not only **“Did the number move?”** but also **“Did the business become healthier, and what did we learn?”**

The next chapter will define the three components in detail and explore how to choose a small set of measurements without creating an administrative burden.

---

*Draft chapter. Examples are illustrative rather than claims about a particular organization. The mechanism-design and measurement claims will be supported with references in a later editorial pass.*
