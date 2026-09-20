# Credit Risk Scorecard Model
**Author:** Krishnaprasad Seshadri  
**Tools:** Python, Scikit-learn, Matplotlib, Seaborn

## Project Summary
Credit risk scorecard built on 32,581 real loan applications using Logistic 
Regression to predict the probability of borrower default. Logistic Regression 
was deliberately chosen over more complex models because interpretability is a 
legal requirement in credit decisioning.

## Key Results
| Metric | Score |
|--------|-------|
| ROC AUC Score | 0.853 |
| Default Recall | 77% |
| Default Precision | 50% |
| Dataset Size | 32,581 loan applications |
| Default Rate | 21.82% |

## Key Techniques
- Exploratory analysis of default rates by loan grade, home ownership and intent
- Missing value treatment using median imputation
- Feature scaling using StandardScaler
- Logistic Regression with class_weight='balanced'
- Evaluation using precision, recall, F1 and ROC AUC

## Key Business Insights
- Default rates increase consistently from loan grade A to G
- Renters default more than mortgage holders or outright owners
- Debt consolidation and medical loans carry the highest default rates
- Loan percent income and loan grade are the strongest predictors of default

## Dataset
[Credit Risk Dataset — Kaggle](https://www.kaggle.com/datasets/laotse/credit-risk-dataset)

## Notebook
See `credit_risk_scorecard.ipynb` for the full annotated walkthrough.
