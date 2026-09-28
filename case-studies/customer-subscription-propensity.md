# Customer subscription propensity

## Decision

Prioritise customers for a term-deposit campaign using information available before a call, while separating post-contact variables that cannot support pre-call targeting.

## Evidence

- 40,964 customer records and 4,632 subscriptions (11.31%).
- Three logistic-regression specifications in R.
- Deployable pre-call model ROC-AUC: 0.8133.
- Post-contact model ROC-AUC: 0.9273, but this included call duration and is not valid for choosing whom to call.
- Hypothesis tests, odds ratios, VIF checks, confusion matrices and ROC analysis.

## Portfolio repair

The clean production design would choose thresholds on cross-validation, report lift and calibration, and keep pre-call targeting separate from post-call quality analysis. This distinction is more important than advertising the largest AUC.

