# DX799S — Milestone One: Credit Risk Capstone (Triet Pham)

Weekly Jupyter notebooks supporting the Milestone One summary document.
**Two datasets, treated equally.** Every notebook loads both datasets and applies each week's
technique to both, with matching visualizations (no separate "Part A / Part B").

- **Credit Risk** — [Kaggle credit-risk dataset](https://www.kaggle.com/datasets/laotse/credit-risk-dataset) (~29k applications after cleaning).
- **German Credit** — [Statlog German Credit](https://archive.ics.uci.edu/dataset/144/statlog+german+credit+data) (1,000 applications; coded attributes decoded to readable names).

| Week | Topic | Notebook |
|------|-------|----------|
| 1 | Polynomial & interaction terms | `Week1_CreditRisk_Regression.ipynb` |
| 2 | Ridge, Lasso, Elastic Net | `Week2_CreditRisk_Regularization.ipynb` |
| 3 | Forward/backward selection, PCR, PLSR | `Week3_CreditRisk_Selection_PCR_PLSR.ipynb` |
| 4 | Logistic regression & feature scaling | `Week4_CreditRisk_Logistic.ipynb` |
| 5 | Support vector machines & the kernel trick | `Week5_CreditRisk_SVM.ipynb` |
| 6 | Decision trees & random forests | `Week6_CreditRisk_RandomForest.ipynb` |

**Targets.** Weeks 1–3 model continuous targets (Credit Risk `loan_int_rate`; German `log(credit_amount)`).
Weeks 4–6 model binary targets (Credit Risk `loan_status` default; German good/bad credit).

## Reproducing
```bash
pip install scikit-learn pandas numpy matplotlib seaborn statsmodels jupyter
jupyter notebook
```
Place `credit_risk_dataset.csv` and `german_credit_data.csv` in the working directory before running.
