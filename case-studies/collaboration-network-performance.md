# Collaboration-network performance modelling

## Decision

Test whether access to elite collaborators, network structure and career experience explain research impact and the probability of high performance.

## Evidence

- Started from 462,248 observations; used a reproducible 184,900-row analytical subset and 168,618 complete modelling rows.
- Compared OLS, polynomial regression, LASSO, forward selection, logistic regression and LDA in R.
- LASSO cross-validated MSE: 1.7394, versus 4.747 for the full OLS comparison.
- High performers represented about 4.1% of the classification sample.
- Interaction analysis found a negative elite-collaborator × elite-cohesion term, supporting a nuanced brokerage interpretation rather than a simple “more elite contacts is always better” claim.

## Interpretation

The model comparison shows that collaboration access, network position and career experience contribute different types of signal. The interaction result also warns against treating elite contacts as automatically beneficial without considering the surrounding network structure.
