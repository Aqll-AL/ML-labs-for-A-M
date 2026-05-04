# Decision Trees & Random Forest – Loan Prediction LAB 9

Predicts whether a LendingClub borrower will fully repay their loan using 2007–2010 data.

## Dataset
`loan_data.csv` — 9,578 rows, 14 features (FICO score, interest rate, debt-to-income ratio, etc.)

## Models
| Model | Accuracy |
|-------|----------|
| Decision Tree | ~73% |
| Random Forest (200 trees) | ~84% |

Random Forest wins overall, though both struggle with class imbalance on defaulted loans.
