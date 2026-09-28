# Scientific novelty and citation modelling

## Decision

Compare linear, tree-based and margin-based methods for citation impact and high-citation classification, then balance interpretability against predictive flexibility.

## Evidence

- 165,792 PubMed observations in the analysed report.
- LASSO feature selection, decision tree and random-forest regression.
- LDA, linear SVM and radial-basis SVM classification.
- Bias–variance analysis and a leakage-free stacking design.
- Polynomial holdout RMSE: 1.124.
- Radial-basis SVM ROC-AUC: 0.658.

## Interpretation

The moderate classification AUC is useful evidence of judgement: a complex learner did not turn the available features into a highly discriminative model. The case therefore supports method comparison and honest limits rather than an inflated predictive claim.

