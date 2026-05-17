# E-commerce Sales Performance Analysis

This project analyzes e-commerce sales performance using SQL, Python, and Tableau.  
The goal was to understand sales performance across geography, product categories, traffic channels, devices, and user types.

## Tools Used

- SQL / Google BigQuery
- Python
- pandas, NumPy
- matplotlib, seaborn
- scipy
- Tableau Public

## Project Overview

The analysis covers:

- data extraction from Google BigQuery;
- dataset creation using SQL joins;
- exploratory data analysis and data quality checks;
- sales analysis by country, continent, product category, traffic channel, and user type;
- sales dynamics analysis;
- pivot tables and cross-segment analysis;
- correlation analysis;
- statistical hypothesis testing;
- interactive Tableau dashboard.

## Key Findings

- The dataset contains **349,545 sessions**, but only **33,538 sessions** resulted in purchases, giving a purchase session rate of **9.59%**.
- The United States is the main revenue market, generating **43.6%** of total sales.
- Americas generates **55.38%** of total revenue.
- `Sofas & armchairs`, `Chairs`, and `Beds` together generate more than **60%** of total revenue.
- Organic Search is the strongest traffic channel, accounting for **35.76%** of total sales.
- Unregistered users generate about **91.9%** of total sales.
- Daily sessions and daily sales have a strong positive correlation: **r = 0.791**.

## Tableau Dashboard

The interactive Tableau dashboard is available here:

[View Tableau Dashboard](https://public.tableau.com/app/profile/oleksandra.yakovenko/viz/E-commerceSalesPerformanceDashboard_17790298798380/SalesOverview)

## Dashboard Preview

### Sales Overview

![Sales Overview](images/sales_overview_dashboard.png)

### Traffic & User Behavior

![Traffic & User Behavior](images/traffic_user_behavior_dashboard.png)

## Repository Structure

```text
.
├── README.md
├── ecommerce_sales_analysis.ipynb
├── sql/
│   └── final_dataset_query.sql
├── images/
│   ├── sales_overview_dashboard.png
│   └── traffic_user_behavior_dashboard.png
└── requirements.txt
