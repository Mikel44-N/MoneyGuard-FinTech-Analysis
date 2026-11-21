# MoneyGuard — FinTech Analysis & Product Recommendation

**Project status:** The project guide and presentation are published. The presentation includes screenshots of all three Power BI dashboard pages. The Power BI `.pbix` file has not yet been added to this repository.

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

- `MoneyGuard_Data_Sources_Metrics_Insights_Product_Decision.docx` — two-page guide covering data sources, metrics, insights, product decisions, and limitations.
- `MoneyGuard_FinTech_Presentation.pptx` — 11-slide project presentation. It includes the Financial Health Overview, Loan Affordability & Cash Flow, and Customer Insights & Product Opportunities dashboard screenshots.
- `README.md` — project overview and publication notes.

## Tools

- Microsoft Power BI
- Microsoft Excel / CSV

## Data and publication notes

- The original `FinTech.csv` source dataset is not included. Only publish the source data if you have permission to share it and have confirmed it contains no personal, confidential, or otherwise restricted information.
- The Power BI `.pbix` file is not included yet. Add it to the repository when ready, after checking that it does not embed restricted source data or credentials.
- The third dashboard slide in the PowerPoint still contains a residual instruction to replace the screenshot area. Remove that line because the screenshot is already embedded.
- The first slide contains a cohort group photograph with identifiable people and names. Confirm that you have permission to make it publicly accessible, or remove that slide before sharing the deck publicly.
- Verify the figures against the final Power BI report before publication.
