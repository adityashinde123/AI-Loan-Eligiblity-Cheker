# Project Workflow

```text
User
  |
  v
Responsive Web UI
  |
  +--> Loan Eligibility Form --> Flask API --> ML Model --> Eligibility + Risk
  |
  +--> Credit Score --> Flask API --> Credit Analysis
  |
  +--> EMI Inputs --> Flask API --> EMI Formula --> EMI Result
  |
  +--> Financial Inputs --> Flask API --> Optional Claude API --> General Tips
```

## Technology Stack

- Frontend: HTML, CSS, JavaScript
- Backend: Python, Flask
- Machine Learning: Pandas, Scikit-learn, Logistic Regression
- AI API: Anthropic Claude (optional)
- Deployment: Gunicorn + a Python-capable hosting platform
- Data: Synthetic CSV for educational model training

## Security notes

- Keep API keys server-side.
- Never commit `.env`.
- Validate inputs on the server, not only in JavaScript.
- Avoid storing real financial information in the demo.
