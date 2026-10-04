# musical-spork

A retail analytics repository focused on a superstore sales dataset, combining raw transactional data with curated analysis tables and a presentation-style summary report.

## Overview

This project contains a superstore dataset and derived analysis files used to explore sales performance, customer behavior, region performance, category trends, and monthly trends. The repo is designed for business reporting and dashboarding workflows, with outputs aligned to tools such as Alteryx and Looker Studio.

The project includes:
- a master sales dataset
- regional, category, customer, and monthly rollups
- a PDF summary report
- source data in Excel format

## Repository Contents

- `RetailPulse_Master.csv` — main transactional dataset for the superstore
- `Data Source.xlsx` — original source workbook
- `Category_Analysis.csv` — category-level performance summary
- `Region_Analysis.csv` — regional sales and profit breakdown
- `Monthly_Trend.csv` — monthly sales/profit trend data
- `Customer_Analysis.csv` — customer-level sales and profitability metrics
- `RetailPulse__Superstore_Analytics (1).pdf` — summary report / dashboard PDF
- `README.md` — project documentation

## Data Summary

The dataset represents superstore sales across multiple years and includes metrics such as:
- sales
- profit
- quantity sold
- number of orders
- discount rates
- customer and regional segmentation

### Key observations from the analysis files

- Highest sales by region: West (`$725,458`)
- Highest sales by category: Technology (`$836,154`)
- Highest profit by category: Technology (`$145,455`)
- Monthly sales trend data spans multiple months across 2014–2017
- Customer analysis includes large-scale customer-level metrics for revenue and profitability

## Suggested Use Cases

This repository can be used for:
- exploratory data analysis (EDA)
- sales trend analysis
- profitability analysis
- customer segmentation analysis
- region/category performance reporting
- dashboard creation in Looker Studio or Power BI

## How to Use

1. Open `RetailPulse_Master.csv` for the base dataset.
2. Use the rollup files (`Category_Analysis.csv`, `Region_Analysis.csv`, `Monthly_Trend.csv`, `Customer_Analysis.csv`) for quick summaries.
3. Review `RetailPulse__Superstore_Analytics (1).pdf` for a presentation-ready executive snapshot.
4. If needed, connect the CSV files to BI tools for visual dashboards and KPI tracking.

## File Interpretation

- `RetailPulse_Master.csv` contains the detailed transaction-level data.
- The summary CSV files are aggregated to support analysis by category, region, month, and customer.
- `Data Source.xlsx` is the source file from which the analysis was derived.

## Project Goal

The goal of this repository is to provide a clean, analysis-ready superstore dataset and supporting summaries for understanding retail performance and business insights.

## Notes

This project is intended for analytics, reporting, and learning purposes. The data and summaries can be extended with additional KPIs, forecasting, or dashboard visualizations.

## License

No explicit license file is present in this repository. Please confirm with the repository owner before using the contents in commercial or public-facing applications.
