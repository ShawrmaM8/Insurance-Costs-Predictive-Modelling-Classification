# Insurance-Costs-Predictive-Modelling-Classification
Predicting Insurance costs using a dataset and classifying whether the patient is high-cost or not.

## Goal: Predictive Cost Modelling + Classification with a priority to accurately capture all patient cases
### Why?
This will reduce long-term insurance costs associated with complications that may arise from missed diagnosis. Furthermore, it contributes to patient satisfaction which improves reputation & customer loyalty.

### How?
We will use RidgeRegression for predicting insurance costs, then RandomForestClassifier (using a threshold) to classify which patients are "high-cost" (Top 25% spenders)
Both models will use optimal parameters to ensure efficiency and robust capture of all patient cases.

### Tradeoffs
While we may effectively identify all early cases and treat them at lower costs (True Positives, False Negatives), we may spend a greater amount in the short-term resulting in greater break-even thresholds for insurance firms, slowing revenue growth.
