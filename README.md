# MSc Business Analytics Project Casebook

This casebook maps the analytical work I completed during the MSc Business Analytics at Queen's University Belfast. It gives recruiters and hiring managers one place to understand the decisions behind the code: what the business problem was, which methods I used, what the analysis established and where the evidence stops.

The work spans forecasting, machine learning, statistical modelling, optimisation, data engineering, customer analytics, HR analytics and decision communication. Six projects have full public repositories; the remaining assessed work is documented as concise case studies where the original data or team code should not be redistributed.

## Portfolio map

| Project | Decision supported | Methods and tools | Public evidence |
|---|---|---|---|
| Retail demand forecasting dissertation | Select, explain and govern a 28-day retail forecast | Python, LightGBM, temporal backtesting, Power BI | [Flagship repository](https://github.com/ahmeddshoaib/retail-demand-forecast-governance) |
| Healthcare room capacity | Configure 10 rooms across 26 weeks | R, MILP, `ompr`, HiGHS | [Optimisation repository](https://github.com/ahmeddshoaib/healthcare-capacity-optimisation-r) |
| Airline recommendation analytics | Diagnose service drivers of recommendation | Python, classification, TF-IDF, holdout testing | [Customer analytics repository](https://github.com/ahmeddshoaib/airline-review-recommendation-analytics) |
| Insurance Customer 360 | Integrate policy data and identify cross-sell cohorts | SQL, R, Access, data quality | [SQL + R repository](https://github.com/ahmeddshoaib/insurance-customer-360-sql-r) |
| Employee attrition | Prioritise retention interventions | KNIME, Tableau, trees, boosting | [Decision analytics repository](https://github.com/ahmeddshoaib/employee-attrition-decision-analytics) |
| Retail coffee strategy | Select target segments and product attributes | RFM, clustering, conjoint, PCA | [Retail strategy repository](https://github.com/ahmeddshoaib/retail-customer-product-strategy-r) |
| Customer subscription propensity | Target pre-call banking campaigns | R, logistic regression, lift, threshold analysis | [Case study](case-studies/customer-subscription-propensity.md) |
| Collaboration-network performance | Explain research impact and high performance | R, LASSO, OLS, logistic regression, LDA | [Case study](case-studies/collaboration-network-performance.md) |
| Scientific novelty and citation | Compare non-linear regression and classifiers | R, LASSO, trees, random forest, LDA, SVM | [Case study](case-studies/scientific-novelty-modelling.md) |
| Austin house prices | Explain and predict log house price | R, regression, diagnostics | [Case study](case-studies/austin-house-prices.md) |
| Ophthalmology allocation, group project | Compare cost and urgency-weighted delay | R, simulation, hill climbing, MCDM | [Contribution case study](case-studies/ophthalmology-capacity-allocation.md) |

## What the MSc trained me to do

### Structure an unclear decision

Each project begins by defining the unit of analysis, target outcome, decision owner and evidence required. That discipline is visible in the difference between predicting customer response, explaining employee attrition, choosing a forecast and optimising scarce clinical capacity: the methods change because the decisions are different.

### Build reliable analytical evidence

The projects use relational data checks, regression diagnostics, temporal backtesting, train/test separation, leakage controls, cross-validation, model comparison and optimisation feasibility checks. I learned to treat validation as part of the analytical product rather than a final accuracy number.

### Translate analysis into action

Outputs include Power BI and Tableau dashboards, customer and supplier scorecards, exception queues, retention-priority matrices, product-positioning recommendations and room schedules. The aim is to make the analytical conclusion usable while preserving uncertainty and limitations.

## Selected assessment evidence

These are individual assignment results unless noted; they are not presented as final module classifications.

| Assessed work | Result | Evidence demonstrated |
|---|---:|---|
| Data-Driven Decision Making — individual analysis | **90** | Method critique, healthcare context, practical implications |
| Data Management | **77** | SQL, relational integration, data quality, business analysis |
| Data Mining | **77** | Text and structured-data classification, evaluation |
| Data-Driven Decision Making — group optimisation | **74** | Markov transitions, scheduling, cost and delay trade-offs |
| Statistics for Business — assignment 2 | **73** | Logistic regression, association, prediction and thresholds |
| Statistics for Business — assignment 1 | **72** | Data quality, visualisation, regression and prediction |

The assessed feedback also identified improvements that shaped the public portfolio rebuild: make numerical interpretation explicit, prevent leakage, justify model choice, compare models on the same evidence, and connect results more directly to business decisions.

## Dissertation as the integrating project

The dissertation brought the degree together in one end-to-end system. It required data preparation, time-series feature engineering, statistical baselines, machine learning, ordered backtesting, explainability, governance and Power BI delivery. The final framework evaluated 10,080 out-of-sample forecasts across 30 category-store series and selected global recursive LightGBM while preserving the series and horizon cases where Holt-Winters remained stronger.

The [flagship repository](https://github.com/ahmeddshoaib/retail-demand-forecast-governance) includes the exact dashboard captures from the submitted technical report, the documented semantic model, public-safe code, aggregate results and automated checks.

## Professional connection

The degree complements two years of supply-chain experience at Ibrahim Fibres and current UK retail experience at Currys. Forecasting and optimisation connect to planning and capacity; SQL and data management connect to ERP and operational reporting; customer analytics connects to consultative selling and service performance; dashboarding connects the analysis to a manager who must act on it.

The [supply chain operations analytics](https://github.com/ahmeddshoaib/supply-chain-analytics-platform) repository is a separate self-directed project built after the MSc. It uses synthetic data to translate supplier, purchase-order, inventory and lead-time questions from my professional experience into a reproducible Python workflow. It is not an employer system or a university submission.

## How the public work is presented

These repositories are recruiter-facing editions of completed MSc work. They retain the original decision, methods, validated results and limitations while removing student numbers, marker comments, university-only paths and source data whose redistribution rights are unclear.

Where the original records cannot be published, the repository distinguishes archived academic results from synthetic validation outputs. Group projects state my own contribution and do not release team code without consent. This keeps the evidence useful without misrepresenting private data, shared work or a rebuilt software pipeline as the original submission.

## Author

**Muhammad Ahmed Shoaib**<br>
MSc Business Analytics, Queen's University Belfast<br>
[GitHub profile](https://github.com/ahmeddshoaib) · [LinkedIn](https://www.linkedin.com/in/ahmed-shoaibed)
