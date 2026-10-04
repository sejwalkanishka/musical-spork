# 📊 RetailPulse: Superstore Analytics Dashboard

> A comprehensive retail analytics project showcasing data transformation, aggregation, and visualization for actionable business insights.

---

## 🎯 Project Overview

**RetailPulse** is an end-to-end retail analytics solution that transforms raw superstore transactional data into meaningful business intelligence. The project demonstrates a complete analytics workflow—from data ingestion and transformation to aggregation and presentation—using industry-standard tools.

This repository contains:
- 🔍 Raw transactional sales data
- 📈 Pre-aggregated analysis datasets
- 📊 Interactive dashboard visualizations
- 📑 Executive summary report

Perfect for learning analytics pipelines, data transformation workflows, or as a foundation for retail business intelligence projects.

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| **Alteryx** | Data transformation, ETL workflows, and data cleaning |
| **Google Sheets** | Collaborative data management and quick analysis |
| **Looker Studio** | Interactive dashboard creation and visualization |
| **CSV/Excel** | Data storage and export |

---

## 📁 Repository Structure

```
musical-spork/
├── RetailPulse_Master.csv              # Main transactional dataset (raw data)
├── Data Source.xlsx                     # Source workbook for reference
├── Category_Analysis.csv                # Category-level performance summary
├── Region_Analysis.csv                  # Regional sales & profit breakdown
├── Monthly_Trend.csv                    # Monthly sales trends (2014–2017)
├── Customer_Analysis.csv                # Customer-level metrics & profitability
├── RetailPulse__Superstore_Analytics.pdf # Executive dashboard & report
└── README.md                             # This file
```

---

## 📊 Dataset Summary

**Data Scope:** Multi-year superstore sales dataset (2014–2017)

**Key Metrics:**
- Total Sales: ~$2.3M across 11,050+ orders
- Total Profit: ~$286K
- Products: 3 categories (Furniture, Office Supplies, Technology)
- Regions: 4 regions (West, East, Central, South)
- Customers: 800+ unique customers

**Data Fields:**
- Order details (ID, date, quantity)
- Customer information (name, segment)
- Geographic data (region, country, city)
- Product data (category, sub-category)
- Financial metrics (sales, profit, discount)

---

## 💡 Key Insights

| Metric | Value | Finding |
|--------|-------|---------|
| **Top Region by Sales** | West | $725K in sales |
| **Top Category by Sales** | Technology | $836K in sales |
| **Top Category by Profit** | Technology | $145K profit |
| **Best Discount Impact** | West | 11% avg discount with highest ROI |
| **Highest Risk Region** | Central | 24% avg discount, lowest profit margin |

---

## 🚀 Quick Start

### 1. **Explore the Data**
   - Start with `RetailPulse_Master.csv` for the full transaction-level dataset
   - Use analysis CSVs for quick summaries by category, region, or customer

### 2. **View the Dashboard**
   - Open `RetailPulse__Superstore_Analytics.pdf` for the executive summary
   - Review trends, regional performance, and customer insights

### 3. **Dive Deeper**
   - Import CSVs into Google Sheets for collaborative analysis
   - Connect data to Looker Studio for interactive visualizations
   - Use Alteryx to create custom workflows or extend the analysis

### 4. **Create Your Own Reports**
   - Use the cleaned data as a foundation for your analytics projects
   - Build custom dashboards in Looker Studio
   - Generate automated reports with Alteryx

---

## 📈 Analysis Highlights

### Sales Performance
- Consistent growth in Q4 across all years
- Technology category drives profitability despite lower volume
- Regional performance shows West outperforming other regions

### Customer Insights
- High variance in customer profitability—top 20% of customers generate majority of profit
- Discount sensitivity: higher discounts correlate with lower profit margins
- Customer retention opportunities in low-profit segments

### Operational Observations
- Central region has highest discount rate but lowest profit—opportunity for margin improvement
- Seasonal patterns evident in monthly trends
- Office Supplies have lowest profit margins despite high sales volume

---

## 🔄 Data Transformation Workflow

```
Raw Data (Data Source.xlsx)
         ↓
Alteryx ETL & Cleaning
         ↓
Google Sheets Collaboration & Review
         ↓
Aggregation to Summary Tables
         ↓
Looker Studio Visualization
         ↓
Executive Report PDF Output
```

---

## 📊 Files Guide

| File | Purpose | Format |
|------|---------|--------|
| `RetailPulse_Master.csv` | Complete transaction-level data | CSV (2.8 MB) |
| `Monthly_Trend.csv` | Sales & profit by month | CSV (3 KB) |
| `Region_Analysis.csv` | Regional performance summary | CSV (0.4 KB) |
| `Category_Analysis.csv` | Product category analysis | CSV (0.5 KB) |
| `Customer_Analysis.csv` | Customer-level profitability | CSV (51 KB) |
| `Data Source.xlsx` | Original source file | Excel (1 MB) |

---

## 🎨 Dashboard Features

The Looker Studio dashboard includes:
- ✅ Real-time sales and profit KPIs
- ✅ Regional performance comparison
- ✅ Category trend analysis
- ✅ Monthly sales patterns
- ✅ Customer segmentation views
- ✅ Discount impact analysis

**View the report:** [RetailPulse Analytics PDF](./RetailPulse__Superstore_Analytics%20(1).pdf)

---

## 💼 Use Cases

- 📚 **Learning:** Understand end-to-end analytics workflows
- 📊 **Prototyping:** Build BI dashboards and test visualization approaches
- 🔍 **Analysis:** Explore retail KPIs and business trends
- 🎯 **Reporting:** Create executive summaries and business reviews
- 📈 **Forecasting:** Use historical data for predictive modeling
- 🤝 **Collaboration:** Share insights across teams using interactive dashboards

---

## 🔧 How to Use This Repository

### For Data Analysis:
```bash
# Load the master dataset
import pandas as pd
df = pd.read_csv('RetailPulse_Master.csv')

# View summary statistics
df.describe()

# Explore by region
df.groupby('Region')[['Sales', 'Profit']].sum()
```

### For Dashboard Creation:
1. Open `RetailPulse_Master.csv` or summary files in Google Sheets
2. Connect to Looker Studio
3. Build custom visualizations
4. Share interactive dashboards with stakeholders

### For Data Transformation:
1. Use Alteryx to design custom workflows
2. Import raw data from Excel/CSV
3. Apply data cleaning and aggregation steps
4. Export to formats compatible with analytics tools

---

## 📝 Project Workflow

1. **Data Collection** → Raw transactional data from superstore operations
2. **Data Cleaning** → Alteryx ETL processes remove duplicates, handle nulls, standardize formats
3. **Data Aggregation** → Summary tables created by category, region, customer, and month
4. **Data Collaboration** → Google Sheets enable team review and feedback
5. **Visualization** → Looker Studio transforms data into interactive dashboards
6. **Reporting** → Executive summary PDF generated for stakeholder presentation

---

## 📚 Learning Resources

- [Alteryx Documentation](https://www.alteryx.com/resources)
- [Google Sheets Guide](https://support.google.com/docs)
- [Looker Studio Tutorials](https://support.google.com/looker-studio)
- [Retail Analytics Best Practices](https://en.wikipedia.org/wiki/Business_intelligence)

---

## 🎯 Potential Enhancements

- [ ] Add predictive forecasting models for future sales
- [ ] Implement customer lifetime value (CLV) calculations
- [ ] Create churn prediction models
- [ ] Build automated alerts for KPI anomalies
- [ ] Add geospatial visualizations
- [ ] Integrate real-time data sources

---

## 📄 License

This project and all associated materials are the proprietary property of the repository owner, [sejwalkanishka](https://github.com/sejwalkanishka).

No part of this project may be used, copied, modified, distributed, reproduced, or published without explicit written permission from the owner.

For licensing inquiries, permission requests, or collaboration opportunities, please contact the repository owner through GitHub.

All rights reserved.

It is created for educational purposes so viewers can explore the project, understand how the workflow works, and learn from the data analysis process. If you want to learn more, discuss ideas, or have any questions, feel free to connect with me on GitHub.
---

## 👤 About

Created by [sejwalkanishka](https://github.com/sejwalkanishka) as a portfolio-style demonstration of retail analytics best practices using modern BI tools and workflows.

This project showcases end-to-end data transformation, KPI analysis, and dashboard storytelling for business decision-making in a retail context.

Questions or collaboration inquiries? Feel free to open an issue or reach out via GitHub.

---

<div align="center">

**⭐ If this project helped you, please consider giving it a star!**

Made with 📊 and 💡 for data-driven decision making

</div>
