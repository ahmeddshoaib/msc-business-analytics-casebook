# Ophthalmology capacity allocation

## Ownership

This was a six-person group project. I co-developed the work and owned the R-based multi-criteria decision analysis and Pareto analysis. The shared simulator and optimisation code remain private until every contributor consents to publication.

## Decision

Compare 52-week ophthalmology allocation policies on total cost and urgency-weighted delay, including a hill-climbing booking optimiser.

## Evidence

- Four patient types with treatment-generated Markov demand.
- Five rule-based policies plus hill climbing.
- Zero structural violations across 260 model-week outputs.
- Lowest rule-based cost: £1,858,356 for Model 3.
- Two Pareto-efficient alternatives: Model 3 and hill climbing.
- Hill climbing cost £837,418 more than Model 3 while producing 24,047.6 fewer urgency-weighted delayed patient-weeks.

## Boundary

The reported 48% hill-climbing improvement used its own fixed-booking starting surface and is not directly comparable with Model 3's dynamic rule-based headline cost. The defensible result is the Pareto trade-off above.

