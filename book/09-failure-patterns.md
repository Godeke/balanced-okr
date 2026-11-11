# Chapter 9 — Failure Patterns and Case Studies

The following are **illustrative scenarios**, not reports of measured results from a named organization. They show how to diagnose a goal system before it rewards the wrong outcome.

## Case 1: acquisition without retention

A sales team increases issued policies. A later cohort review reveals higher early cancellations and weak renewals. The failure was not necessarily the sales team's effort; the scorecard omitted suitability and sustainability.

**Balanced redesign:** Track qualified conversion and economic contribution; monitor early cancellations and cohort renewal quality as guardrails. Segment by lead source and product as diagnostics. Keep long-term follow-up open after the quarterly KR closes.

## Case 2: phone calls as a universal rule

A manager assumes more agent calls improve conversion. The metric becomes calls per representative. Employees increase calls on simple, low-value accounts even though incremental conversion is uncertain.

**Balanced redesign:** Run a discovery OKR comparing outreach approaches by account segment, with an agreed outcome and cost measure. Use call count as a diagnostic, not the success criterion. If evidence is weak, avoid a blanket mandate.

## Case 3: fast deployments, unstable service

Engineering increases deployment frequency while production incidents rise. The local throughput metric improves; customer experience worsens.

**Balanced redesign:** Measure lead time and delivery value while reviewing change failure, recovery, and rework. DORA's current five-metric framework explicitly covers both throughput and instability [R5]. Google's SRE error-budget practice is an example of making the reliability/innovation tradeoff operational [R6].

## Case 4: underwriting speed without quality

A process team reduces average quote turnaround time by routing complex cases elsewhere or postponing difficult reviews. The average improves, but rework and escalations rise.

**Balanced redesign:** Define turnaround by case class and include the complete customer journey. Monitor corrections, escalations, and handoff costs. Use case complexity as a diagnostic to avoid rewarding cherry-picking.

## Case 5: support tickets closed

A service center is judged by tickets closed per day. Agents close cases early, increasing repeat contacts and customer frustration.

**Balanced redesign:** Focus on durable resolution and customer effort. Use repeat contact and reopening as guardrails. Examine contact type and severity before interpreting average handling time.

## Case 6: shared development becomes a hidden bottleneck

Several departments commit to software-dependent objectives. None reserves capacity with the engineering team. All report that the project is blocked.

**Balanced redesign:** Add explicit contributor agreements and portfolio-level capacity review before approval. Track waiting time and scope changes as diagnostics, not as excuses.

## Case 7: too many guardrails

A leadership team responds to every concern by adding another hard threshold. The OKR becomes impossible to interpret and every decision requires committee review.

**Balanced redesign:** Prioritize material risks. Separate hard obligations, decision triggers, and diagnostics. Remove low-value measures. Balance is about better decisions, not maximum instrumentation.

## Case 8: green dashboards, stale assumptions

A metric remains unchanged for years. Teams learn its quirks, reporting becomes predictable, and the measure stops discriminating between useful and superficial improvements.

**Balanced redesign:** Require periodic evidence that the measure still reflects the intended outcome. Retire or redesign it when the relationship weakens.

## What the cases share

The common mistake is treating a partial observation as a complete definition of success. Balanced OKRs does not eliminate tradeoffs or uncertainty. It makes the important ones discussable and connects them to explicit decisions.

**Practice exercise:** Choose one case and identify the earliest moment when a guardrail or diagnostic would have changed management's decision.

[Previous](08-adoption-playbook.md) · [Next](10-limits-and-criticisms.md)
