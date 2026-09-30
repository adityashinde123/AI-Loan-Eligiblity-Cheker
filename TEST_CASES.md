# Test Cases

| ID | Module | Input | Expected |
|---|---|---|---|
| TC01 | EMI | 500000, 10%, 5 years | EMI shown |
| TC02 | EMI | negative loan | Validation error |
| TC03 | Credit | 760 | Excellent/low risk band |
| TC04 | Credit | 250 | Validation error |
| TC05 | Loan | valid financial details | Prediction + probability + reasons |
| TC06 | Loan | missing age | Required-field error |
| TC07 | Loan | credit score 950 | Validation error |
| TC08 | AI Tips | income 50000, expenses 30000 | General tips shown |
| TC09 | Responsive UI | mobile width | Layout remains usable |
| TC10 | Security | missing API key | App continues using demo tips |
