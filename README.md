📊 Customer Churn Analysis Dashboard

This Power BI dashboard analyzes customer churn behavior using demographics, satisfaction scores, tenure, and Customer Lifetime Value (CLTV). It helps business stakeholders understand churn patterns, 
key risk factors, and retention opportunities.

## 📁 Project Overview

- **Tool Used**: Power BI
- **Data Sources**: 5 tables - `Demographics`, `Location`, `Population`, `Services`, `Status`, `Customers` (bridge created using DAX)
- **Objective**: To visualize and identify churn trends, customer segments, and relationships between satisfaction, tenure, and CLTV.

## 📌 Key Features

### 📈 Page 1: Overall Churn Summary

- **KPI Cards**:
  - Total Customers
  - Active Customers
  - Churned Customers
  - Retained Customers

- **Charts & Insights**:
  - Column chart: Churn Rate by Churn Reason
  - Column chart: Customers Churned by Tenure
  - Stacked column: Total vs Churned by CLTV Ranges
  - Field Parameter visuals:
    - Gender-wise churn
    - CLTV bins (2k–3k, 3k–4k, 4k–5k, 5k–6k, High Tier)
    - Satisfaction scores
    - Senior citizen impact

### 📈 Page 2: In-depth CLTV and Satisfaction Insights

- **Scatter Plot**:
  - X-axis: CLTV Ranges
  - Y-axis: Avg. Satisfaction
  - Bubble Size: Churned Customers

- **Donut Chart**:
  - Customers churned by churn category

- **Customer Churn by CLTV Bins**:
  - Highlights imbalance of churn in medium CLTV segments

- **Insight Text Boxes**:
  - Summarized interpretations for each major visual

## 🔍 Key Insights

- High-tier customers show lowest churn and highest satisfaction.
- Short tenure customers exhibit the highest churn volume.
- Medium CLTV segments (3k–5k) have surprisingly higher churn despite decent spend.
- Senior citizens and customers with low satisfaction are more likely to churn.



## 📂 Files Included

- `Churn analysis dashboard.pbix` (Power BI report)
- `Dataset.csv` 
- `Screenshots/` folder 
---

## 📝 Notes

- **CLTV** stands for *Customer Lifetime Value*
- Visual formatting includes card shadowing, modern fonts, and color consistency for clarity.


## 🚀 Getting Started

You can:
1. Clone the repository.
2. Open the `.pbix` file in Power BI Desktop.
3. Replace with your dataset or modify visuals as needed.

---



