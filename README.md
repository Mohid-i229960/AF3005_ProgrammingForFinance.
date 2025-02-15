# AF3005_ProgrammingForFinance.


This repository contains a financial management automation project for SecureBank, designed for the Programming for Finance course. The system offers five essential financial operations, all implemented using Python and `ipywidgets` for dynamic interactivity.

---

## Key Modules

### 1. Loan Approval and Interest Calculation
- Validates employment status, income threshold, and credit score.
- Determines loan approval and calculates applicable interest rates.
- Utilizes `ipywidgets` for seamless user input.

### 2. Portfolio Risk Analysis
- Analyzes stock portfolios to determine risk levels.
- Categorizes portfolios as High, Medium, or Low risk.
- Allows users to input stock returns interactively via `ipywidgets`.

### 3. Loan Repayment Management
- Monitors loan balances throughout the repayment period.
- Deducts fixed monthly payments until the balance is cleared.
- Displays remaining balances interactively using `ipywidgets`.

### 4. Stock Price Tracking and Trading Alerts
- Loops through daily stock prices for monitoring.
- Ignores missing entries using `continue`.
- Halts tracking when the stock price hits PKR 200 with `break`.
- Incorporates `ipywidgets` for real-time price input and alerts.

### 5. Currency Exchange Rate Monitoring
- Tracks the PKR to USD exchange rate incrementally.
- Increases the rate daily until PKR 300/USD is reached.
- Provides interactive exchange rate displays with `ipywidgets`.
