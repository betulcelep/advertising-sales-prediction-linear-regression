# Advertising Sales Prediction – Multiple Linear Regression

Regression on the classic **Advertising** dataset (200 markets): predicting product sales from advertising budgets for **TV, radio and newspaper**, and identifying the most effective channel.

## Approach
- No missing values; 80/20 train-test split.
- Multiple linear regression with scikit-learn.
- Evaluation with R², RMSE and the distribution of residuals; actual vs predicted sales plotted for the test set.

## Results
- **R² = 0.91** on test data; **RMSE = 1.68** sales units.

| Channel | Coefficient (sales per unit of spend) |
|---|---|
| Radio | 0.181 |
| TV | 0.046 |
| Newspaper | 0.0001 |

Holding the other channels constant, radio delivers the largest sales increase per unit of spend, followed by TV; newspaper spending contributes almost nothing.

## Files
- `advertising-sales-prediction-linear-regression.ipynb` – full notebook with code and charts

## Tools
Python · pandas · scikit-learn · matplotlib · seaborn

---
Part of my [data science portfolio](https://betulcelep.github.io/#data-science), completed during the *Mastering Applied Data Science with Deep Learning* programme.
