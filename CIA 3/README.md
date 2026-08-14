# FairLoan Assist — CIA 3

Single-notebook ensemble ML project for financial inclusion.

## Dataset

OpenML `credit-g` / UCI Statlog German Credit Data: 1,000 anonymised historical credit applications. Target: `bad` credit outcome (default-risk signal). Source: https://www.openml.org/d/31

## Run

```powershell
pip install -r requirements.txt
jupyter notebook FairLoan_Assist_CIA3.ipynb
```

Run all notebook cells in order. Outputs, trained model, metrics, figures, fairness audit, and explanations are generated in `outputs/`.

## Important limit

This is an educational human-review tool, never an automated loan decision. See [ETHICS.md](ETHICS.md).
