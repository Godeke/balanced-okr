# Chapter 9 — Failure Patterns and Case Studies

Each scenario is hypothetical. Use one to challenge a proposed OKR before the team invests in it.

## Case 1: acquisition without retention

The team issued 1,150 qualified new annual policies in Q1 2027. When the full cohort reached first renewal, 82% renewed against 86% in the comparable prior-year cohort. A four-point decline crossed the agreed two-point tolerance. The commercial director paused expansion and examined pricing, product mix, and sales practices with the people closest to the business. The figures warranted action while the cause was still open. [Follow the cohort through its renewal review.](06-time-horizons.md)

## Case 2: phone calls as a universal rule

A manager proposes calls on every quote. A representative asks whether the extra time buys any improvement on small accounts. In the [outreach pilot](04-causality-and-evidence.md), attempted and completed calls tell the team how much extra outreach took place. The decision turns on additional binds and staff time in each account segment.

## Case 3: fast deployments, unstable service

One software team wants to shorten the time it takes approved changes to reach production for its quoting service. Its KR is to reduce median approval-to-production time from 10 days last quarter to 5 days this quarter. Its Guardrail triggers a review if more than 5% of the service's production changes during the quarter require a rollback or hotfix for an incident. Suppose the median reaches 5 days and 4 of 50 changes need that intervention. The team achieved its speed target. At 8%, the service owner examines the incidents before expanding the rollout. These are illustrative targets.

The distinction between delivery speed and instability also appears in DORA's software delivery measures [R5]. Google's SRE error-budget practice shows how teams can connect reliability evidence to a release decision [R6].

## Case 4: underwriting speed without quality

A process team reduces average quote turnaround time by routing complex cases elsewhere or postponing difficult reviews. The average improves, but rework and escalations rise.

Measure elapsed time across handoffs and include each case from initial request to completed quote. If the Guardrail protects against excess rework, a rise in corrections can trigger review. Break those corrections down by case complexity if that helps the reviewer locate the added burden.

## Case 5: support tickets closed

A service center is judged by tickets closed per day. Agents close cases early, increasing repeat contacts and customer frustration.

Define durable resolution from the customer's perspective. Set a Guardrail for repeat contact about the same unresolved issue. Ask agents to review a sample of reopened tickets if the signal is ambiguous.

## Case 6: shared development becomes a hidden bottleneck

Several departments commit to software-dependent objectives. None reserves capacity with the engineering team. All report that the project is blocked.

Ask the engineering lead which request can fit and have the owners agree which work moves. Record the deliverable, capacity, timing, and deferred request with the participant's commitment. This operating record helps the owners renegotiate if the schedule changes. [See the two-week capacity decision.](05-organization-as-system.md)

## Case 7: too many guardrails

A leadership team responds to every concern by adding another hard threshold. The OKR becomes impossible to interpret and every decision requires committee review.

Start with the harm serious enough to change the decision. Identify any binding obligation and who must respond if it is breached. For a discretionary Guardrail, ask what evidence its reviewer needs. Remove measures that nobody uses to decide anything.

## Case 8: green dashboards, stale assumptions

A metric remains unchanged for years. Teams learn its quirks, reporting becomes predictable, and the measure stops discriminating between useful and superficial improvements.

Ask when the team last checked that the measure still predicts the outcome. Retire or redesign it when the relationship weakens. [See the example of retiring a call leaderboard.](03-mechanisms-and-incentives.md)

## What the cases share

In each case, a person can hit the assigned target while someone else bears the cost. Before adopting the measure, invite that person or team to describe what they would see first and what action would help.

**Practice exercise.** Pick one case and use the [worksheet](worksheet.md) to record the earliest decision a manager could change, the evidence then available, and who would act.

[Previous](08-adoption-playbook.md) · [Next](10-limits-and-criticisms.md)
