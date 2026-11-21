# MoneyGuard — FinTech Analysis & Product Recommendation

**Project status:** Documentation and presentation draft prepared. The Power BI report file and final dashboard screenshots still need to be added.

## Project overview

MoneyGuard is a proposed financial wellness concept designed to help users understand whether their income can cover regular expenses and loan repayments before taking on additional borrowing.

The analysis used **FinTech.csv**, containing 32,424 user records and 20 columns, covering July 2021 to July 2025. The analysis and dashboard work used **Microsoft Power BI and Excel/CSV**.

## Key findings

- **Loan penetration:** 40.08% of users (12,995 / 32,424) had loans.
- **Outflow pressure:** 33.07% of users (10,724 / 32,424) had monthly expenses plus EMI exceeding monthly income.
- **High DTI:** 82.24% of borrowers had DTI above 0.4; 59.65% had DTI above 1.0.
- **Median borrower DTI:** 1.35 (135%), subject to the dataset's DTI definition.
- **Median monthly shortfall:** approximately $4,739 among users whose monthly expenses plus EMI exceeded income.

These are dataset-derived observations. They do not prove missed payments, real-world financial distress, or customer demand. Interpretations of DTI depend on the formula and definition used in the source dataset.

## Product recommendation

The proposed MVP focuses on:
1. A loan affordability calculator.
2. A monthly cash-flow breakdown showing income, expenses, EMI, and projected remaining balance.
3. Financial pressure alerts when projected outflows exceed income.

## Repository contents

- `documentation/` — two-page guide covering data sources, metrics, insights, product decisions, and limitations.
- `presentation/` — MoneyGuard presentation draft. **It contains placeholders for the three finished Power BI dashboard screenshots.**
- `dashboard/` — add the final Power BI `.pbix` file here.
- `images/` — add genuine screenshots of the finished dashboard pages here.

## Tools

- Microsoft Power BI
- Microsoft Excel / CSV

## Data and publication note

The original `FinTech.csv` source dataset is not included. Only publish the source data if you have permission to share it and have confirmed it contains no personal, confidential, or otherwise restricted information.

Before presenting this as a complete portfolio project, add the `.pbix` file, export genuine screenshots of the dashboard pages, and replace the screenshot placeholders in the PowerPoint. Verify the figures against the final report before publication.
