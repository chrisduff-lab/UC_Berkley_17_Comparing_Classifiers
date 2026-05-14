# Practical Application III: Comparing Classifiers

**UC Berkeley Professional Certificate in Machine Learning & Artificial Intelligence — Module 17**

## Overview
Comparison of four classifiers (Logistic Regression, KNN, Decision Tree, SVM) applied to the UCI Bank Marketing dataset to predict term deposit subscription.

## Key Finding
Logistic Regression is the recommended model — highest ROC-AUC (0.80), trains in under a second, and produces interpretable coefficients that directly support business decision-making.

## Actionable Insights
1. **Schedule campaigns in March** — clients contacted in March are 2.9x more likely to subscribe
2. **Switch to cellular contact** — landline contacts are half as likely to convert (OR 0.55)
3. **Limit contacts per client** — each additional call in a campaign reduces subscription likelihood

## Next Steps
- Explore ensemble methods (Random Forest, Gradient Boosting)
- Address class imbalance with `class_weight='balanced'`
- Optimise decision threshold for the bank's cost function

## Notebook
[Prac_3_comparing_classifiers.ipynb](Prac_3_comparing_classifiers.ipynb)

## Data
[UCI Bank Marketing Dataset](https://archive.uci.edu/ml/datasets/bank+marketing)
