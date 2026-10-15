# Retail Sales & Business Performance Analysis

An end-to-end retail analytics project using **Microsoft Power BI**, **DAX**, and a retail invoice dataset. The dashboard explores sales performance, profitability, discount effectiveness, seasonal campaigns, basket behaviour, regional performance, and revenue leakage from returns and cancellations.

> **Data note:** The original row-level retail invoice dataset was not included among the files provided for this repository build. The Power BI report and presentation are included, along with the reported project findings. Add the source dataset to `data/` before publishing if you have permission to share it. Do not represent the summary metrics in `data/project_metrics.csv` as raw transaction data.

## Project files

```text
retail-sales-business-performance-analysis/
├── README.md
├── .gitignore
├── dashboard/
│   └── Retail_Sales_Business_Performance_Analysis.pbix
├── presentation/
│   └── Retail_Sales_Business_Performance_Analysis.pptx
├── data/
│   ├── README.md
│   └── project_metrics.csv
├── docs/
│   ├── data_dictionary_template.md
│   └── methodology.md
└── screenshots/
    └── README.md
```

## Business questions

1. How do discount bands relate to sales volume and order value?
2. Which months and festive campaigns show stronger sales?
3. Do multi-item baskets and category combinations create opportunities for bundling?
4. How do discounts relate to profit and margin?
5. Which states and cities contribute to sales and profit?
6. Where are returns and cancellations concentrated, and what revenue is associated with them?

## Key findings reported in the project

- **Net sales:** ₹40.10M
- **Profit:** ₹8.95M
- **Invoices:** 575
- **Customers:** 364
- **Units sold:** 2,426
- **Profit margin:** 22.33%
- **Discount analysis:** the 10–20% band recorded ₹13.16M in sales and 749 units sold.
- **Seasonality:** October 2025 peak monthly sales were reported as ₹37.57 lakh; Diwali Mega Sale net sales were reported as ₹6.64M.
- **Basket behaviour:** 397 multi-item orders, 178 single-item orders, and an average basket size of 4.22 were reported.
- **Returns/cancellations:** 57 cancelled orders and 37 returned orders were reported, with approximately ₹33.25 lakh in associated revenue leakage. Electronics accounted for about 59% of the related leakage.

**Metric consistency note:** The supplied presentation contains a few inconsistent totals across slides (for example, the headline dashboard reports ₹40.10M sales and ₹8.95M profit, while the conclusion slide shows different rounded totals). This README uses the headline dashboard figures and labels other values as reported findings. Verify all measures against the PBIX before using them in formal business decisions.

## Tools and techniques

- Microsoft Power BI
- DAX measures and calculated metrics
- Power Query / data transformation workflow
- Data modelling and time-based analysis
- KPI cards, tables, bar/column charts, line charts, and category comparisons
- Business insight communication and dashboard storytelling

## How to view the project

1. Download or clone this repository.
2. Open `dashboard/Retail_Sales_Business_Performance_Analysis.pbix` in **Power BI Desktop**.
3. If Power BI prompts for a data source, reconnect it to the original invoice dataset and refresh the report.
4. Open the PowerPoint in `presentation/` for the project walkthrough and key findings.

The PBIX may rely on the original data source path or embedded model. Because the source dataset was not provided separately here, a fresh refresh on another computer may require reconnecting the data.

## Data and privacy

- Only publish source data if you own it or have permission to redistribute it.
- Remove personal/customer identifiers and sensitive fields before committing data.
- For large datasets, consider Git LFS or a link to an approved public source rather than committing sensitive or very large files.
- `data/project_metrics.csv` is a compact summary of metrics reported in the presentation; it is **not** a replacement for the source invoice dataset.

## Suggested resume bullet

Built a multi-page Power BI dashboard using DAX to analyse retail sales, profit, discount effectiveness, seasonal campaigns, basket behaviour, regional performance, and returns/cancellations; reported ₹40.10M net sales, ₹8.95M profit, and approximately ₹33.25 lakh in associated revenue leakage.

## Author

**Chinmay Kumar Sethy**  
Add your LinkedIn, GitHub profile, and contact details here before publishing.
