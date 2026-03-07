Jupyter notebooks for data cleaning, feature engineering, and model construction

# Attrition Model Results
- Since the attrition data had a 91-9 split, the data was scaled using weighted averages for both the models

# Linear Regression Results
- Overtime is highly correlated with attrition
- Senior level had high correlation with attrition
- Satisfaction level had negative correlation with attrition
- Work life balance score had negative correlation with attrition
- Precision: 87%
- F1 Score: 71%
- Accuracy: 63%
- Recall (Most Important): 63%

# Random Forest Results
- Precision: 85%
- F1 Score: 71%
- Accuracy: 86%
- Recall (Most Important): 86%
- AUC score: 0.64

# Overall Results: Model is a weak predictor whether an employee will attrition or not.
