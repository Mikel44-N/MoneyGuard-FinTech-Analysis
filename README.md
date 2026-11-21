
# MoneyGuard — FinTech Analysis & Product Recommendation

**Project status:** The MoneyGuard project guide, 10-slide presentation featuring screenshots of all three Power BI dashboard pages, and interactive Power BI dashboard file (.pbix) are published in this repository.

## Project overview

MoneyGuard is a proposed financial wellness concept designed to help users understand whether their income can cover regular expenses and loan repayments before taking on additional borrowing.

The analysis used `FinTech.csv`, containing 32,424 user records and 20 columns, covering July 2021 to July 2025. The analysis and dashboard work used **Microsoft Power BI and Excel/CSV**.

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

## Repository files

- `MoneyGuard FinTech Dashboard.pbix` — interactive Power BI dashboard.
- `MoneyGuard_FinTech_Presentation.pptx` — 10-slide project presentation, including screenshots of the Financial Health Overview, Loan Affordability & Cash Flow, and Customer Insights & Product Opportunities dashboard pages.
- `MoneyGuard_Data_Sources_Metrics_Insights_Product_Decision.docx` — two-page guide covering data sources, key metrics, insights, product decisions, and limitations.
- `README.md` — project overview, findings, and publication notes.

## Tools

- Microsoft Power BI
- Microsoft Excel / CSV

## Data and publication notes

- The original `FinTech.csv` source dataset is not included in this repository. Only publish it if you have permission to share it and have confirmed that it contains no personal, confidential, or otherwise restricted information.
- Before sharing the Power BI file publicly, confirm that it does not expose personal or confidential source data, credentials, or other restricted information.
- The findings describe patterns in this dataset; they should not be presented as proof of missed payments, financial distress, or validated customer demand.
- Check that any photographs or identifiable people included in the public presentation are approved for public sharing.
