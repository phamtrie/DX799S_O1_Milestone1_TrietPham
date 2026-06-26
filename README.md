# DX799S — Milestone One: Credit Risk Capstone (Triet Pham)

Weekly Jupyter Notebook completions supporting the Milestone One summary document.
Project: predicting consumer credit risk on the [Kaggle Credit Risk dataset](https://www.kaggle.com/datasets/laotse/credit-risk-dataset).

| Week | Topic | Notebook |
|------|-------|----------|
| 1 | Polynomial & interaction terms | `Week1_CreditRisk_Regression.ipynb` |
| 2 | Ridge, Lasso, Elastic Net | `Week2_CreditRisk_Regularization.ipynb` |
| 3 | Forward/backward selection, PCR, PLSR | `Week3_CreditRisk_Selection_PCR_PLSR.ipynb` |
| 4 | Logistic regression & feature scaling | `Week4_CreditRisk_Logistic.ipynb` |
| 5 | Support vector machines & the kernel trick | `Week5_CreditRisk_SVM.ipynb` |
| 6 | Decision trees & random forests | `Week6_CreditRisk_RandomForest.ipynb` |

**Targets.** Weeks 1–3 model the continuous `loan_int_rate`; Weeks 4–6 model the binary `loan_status` (default).

## Reproducing
```bash
pip install scikit-learn pandas numpy matplotlib statsmodels jupyter
jupyter notebook
```
