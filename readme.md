## Decoding Superhost Success: Leveraging AI to Elevate Airbnb’s Program

_(MGMT 687: AI for Business Decisions)_

- **Performance Benchmarking:** Quantified differences between Superhosts and Non-Superhosts in Chicago—Superhosts achieve 16% vs 12% occupancy, \$3,249.55 vs \$2,693.40 average monthly revenue, and 4.88 vs 4.68 average rating despite slightly lower nightly rates.
- **Data Preparation & Feature Engineering:** Applied tailored imputation (zero-fill for counts, mean/median for continuous, mode for categoricals, selective row drops), one-hot encoding, and distilled core predictors (ratings, review counts, cancellations, pricing, occupancy, revenue).
- **Predictive Modeling:** Built a Gradient Boosting model with SMOTE to address class imbalance and used GridSearchCV for hyperparameter tuning—achieving 89% accuracy, 94% recall, and a 0.968 ROC AUC in forecasting Superhost attainment.
- **Early-Warning & Recommendations:** Identified 10.6% of Superhosts at risk and 7.6% of non-Superhosts as high-potential, surfacing decline in ratings, rising cancellations, and low occupancy as key risk factors; proposed targeted support, pricing adjustments, and marketing interventions.
- **Geospatial & Cluster Insights:** Mapped Superhost density by census tract to contrast urban core vs outskirts, then clustered listings into archetypes (High Success, Luxury, Mid-Range, Economical) to inform location-specific growth strategies.

This end-to-end project demonstrates expertise in data engineering, machine learning, geospatial analysis, and translating insights into actionable business decisions.
