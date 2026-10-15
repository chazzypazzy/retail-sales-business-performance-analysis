# Methodology

## Workflow represented in the project

Excel/source data → data cleaning → data modelling → DAX measures → Power BI visuals → business insights.

## Analysis areas

- Sales and profit KPI monitoring
- Discount band comparison
- Monthly and festive campaign trends
- Basket size and frequently occurring category pairs
- Profitability and discount trade-offs
- State and city sales/profit comparison
- Returned/cancelled orders and associated revenue leakage

## Reproducibility

The PBIX is the main analytical artifact. To reproduce or refresh results, use the original invoice-level dataset and confirm the model relationships, Power Query steps, and DAX measures in Power BI Desktop. The source dataset and DAX definitions were not provided as separate files for this repository package, so they have not been recreated or guessed here.

## Validation note

The presentation contains inconsistent totals in different places. Reconcile the dashboard headline figures and conclusion slide with the actual Power BI measures before publishing a final business case or claiming audited results.
