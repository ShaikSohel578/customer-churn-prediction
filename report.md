# Churn Prediction Report

## Models Evaluated

- **LogReg** — Accuracy: 0.644, Precision: 0.637, Recall: 0.657, F1: 0.647, ROC-AUC: 0.678
- **RandomForest** — Accuracy: 0.636, Precision: 0.627, Recall: 0.657, F1: 0.642, ROC-AUC: 0.674
- **XGBoost** — Accuracy: 0.602, Precision: 0.597, Recall: 0.609, F1: 0.603, ROC-AUC: 0.641

## Best Model
- **LogReg** (by ROC-AUC/F1)

See the confusion matrix, ROC and PR curves under `reports/`.


## Business Takeaways (edit this section)
- Customers on month-to-month contracts show higher churn risk.
- Electronic check payment correlates with higher churn.
- Longer tenure correlates with lower churn.
- Consider targeted retention offers for high-risk segments.
