# us-superstore-business-analysis-excel
Interactive Excel workbook and analysis on the US Superstore dataset. Evaluates regional revenue, monthly order trends, producut return rates by category, and overall profitability.
# 📊 US Superstore Sales & Performance Analysis (Excel)

An end-to-end exploratory data analysis and interactive executive dashboard built using **Microsoft Excel** to evaluate revenue, profitability, regional trends, and product return rates for the US Superstore dataset.

---

## 📸 Executive Dashboard Preview

![Dashboard Overview](screenshots/dashboard_overview.png)
*(Replace the image path above with a screenshot of your main Excel dashboard)*

---

## 📌 Project Overview

This project analyzes historical transactional data from the US Superstore to identify key business drivers, operational bottlenecks, and regional performance metrics. The goal is to provide actionable commercial insights into revenue growth, product profitability, demand seasonality, and product return patterns.

---

## 🎯 Key Analytical Focus Areas

* **Financial Performance:** Tracking total revenue, net profit, and gross margins across order cohorts.
* **Regional Breakdown:** Evaluating monthly revenue, sales volume (quantity), order volume (transactions), and unit demand across geographical regions.
* **Product Performance:** Identifying top-performing product categories, sub-categories, and items by sales volume and profitability.
* **Return Rate Analysis:** Assessing product returns across product categories to pinpoint high-friction inventory.

---

## 🛠️ Tools & Excel Features Used

* **Data Cleaning & Transformation:** Power Query / Advanced Data Formatting (handling duplicates, missing values, and date parsing).
* **Data Modeling & Formulas:** Dynamic array functions, `XLOOKUP`, `INDEX/MATCH`, `SUMIFS`, `COUNTIFS`, `GETPIVOTDATA`, and calculated fields.
* **Aggregation & Summarization:** PivotTables and PivotCharts for multi-dimensional data grouping.
* **Visualization & UX:** Custom KPI cards, conditional formatting, slice-and-dice timeline slicers, and interactive dashboard layouts.

---

## 💡 Key Business Insights

1. **Regional Demand Dynamics:** 
   * *(Example: Insert key insight, e.g., The West region drove the highest overall revenue, with peak sales occurring during Q4.)*
2. **Category Profitability vs. Volume:** 
   * *(Example: Technology products yielded the highest profit margins, while Office Supplies generated the highest transaction count.)*
3. **Product Returns Mitigation:** 
   * *(Example: Product return rates were highest in the Furniture category, driven mainly by Chair and Table orders.)*

---

## 📂 Repository Structure

```text
us-superstore-excel-analytics/
├── data/
│ └── raw_superstore_data.xlsx # Original dataset
├── dashboards/
│ └── superstore_analysis.xlsx # Main Excel workbook with PivotTables & Dashboard
├── screenshots/
│ ├── dashboard_overview.png # Screenshot of the main dashboard
│ └── regional_analysis.png # Additional chart preview
└── README.md #
