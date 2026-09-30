# Austin house-price regression

## Decision

Explain and predict house prices while checking whether transformations and richer property attributes improve out-of-sample error.

## Evidence

- Data-quality rules for living area, lot size, bedrooms and bathrooms.
- Log transformations for skewed price and size variables.
- Four regression specifications with an 80/20 holdout.
- Best adjusted R²: 0.4667.
- Best log-price RMSE: 0.368 and MAE: 0.265.
- Approximately 6.6% RMSE improvement over the baseline specification.
- VIF, Durbin-Watson, Cook's distance and residual diagnostics.

## Learning

The lower tail of the Q-Q plot still deviated from normality. A production rebuild would report original-currency error, resampling uncertainty and an explicit missing-data pipeline.

