# HR Attrition Risk Model

## Business Problem
Employee attrition costs organisations 50–200% of an employee's annual salary in recruitment, onboarding, and lost productivity. This project builds a predictive model to identify employees at high risk of leaving — enabling HR teams to intervene early, target retention efforts, and reduce involuntary talent loss.

## Project Summary
| Metric | Result |
|---|---|
| Dataset | 1,000 synthetic employee records |
| Features | 12 employee attributes |
| Attrition Rate | 17.4% |
| Model | Random Forest Classifier |
| ROC-AUC Score | 0.982 |
| Accuracy | 92% |
| Recall on Leavers | 91% |

## Key Findings
- **179 employees (17.9%)** identified as High Risk
- **Engagement score** is the single strongest predictor of attrition
- **Zero promotions in 3 years** is present in every top-10 high risk employee
- **Finance department** is disproportionately represented in high risk segment
- Salary alone does not explain attrition — disengaged employees leave regardless of pay

## Top 3 Attrition Predictors
1. Engagement Score
2. Monthly Salary
3. Promotions in Last 3 Years

## Tech Stack
- Python · pandas · numpy
- scikit-learn · imbalanced-learn
- matplotlib · seaborn

## Files
| File | Description |
|---|---|
| `01_attrition_analysis.ipynb` | Full analysis notebook |
| `attrition_patterns.png` | Attrition pattern visualisations |
| `attrition_model_results.png` | Feature importance and risk score charts |
| `attrition_risk_scores.csv` | Employee risk scores output |
