# Porter Delivery Excel Analysis

## Project Overview

This project analyzes Porter delivery operations using Microsoft Excel. The objective is to clean the dataset, perform exploratory data analysis (EDA), generate business insights, and build an interactive dashboard to evaluate delivery performance, order trends, and operational efficiency.

---

## Objectives

- Analyze order distribution across different markets.
- Evaluate delivery performance across store categories.
- Identify peak order hours and weekly demand patterns.
- Perform statistical analysis using correlation and standard deviation.
- Develop an interactive dashboard with KPIs, Pivot Charts, and Slicers.

---

## Dataset Information

- Total Orders: 197,386
- Markets Covered: 6
- Tool Used: Microsoft Excel
- Dashboard Type: Interactive Excel Dashboard

---

## Data Cleaning

The following preprocessing steps were performed:

- Removed duplicate records.
- Handled missing and invalid values.
- Calculated delivery duration in minutes.
- Removed unrealistic delivery time outliers (greater than 300 minutes).
- Created helper columns for analysis.
- Standardized data formats.

---

## Key Analysis Performed

### Basic Analysis

- Order volume by market
- Average delivery time by store category
- Peak order hours
- Weekly order distribution
- Correlation between total items and subtotal
- Delivery time distribution
- Orders delivered within 30 minutes
- Correlation between busy partners and order volume
- Delivery time by weekday
- Top stores with highest delivery time

### Medium Analysis

- Order protocol efficiency
- Average order value by market
- Partner availability vs delivery time
- Correlation between order complexity and delivery time
- Weekly delivery trend
- Price range vs subtotal correlation
- High-value order likelihood by store category
- Delivery time consistency using standard deviation
- Partner utilization correlation
- Dataset limitation for repeat customer analysis

---

## Dashboard Preview

The interactive dashboard provides a consolidated view of Porter delivery operations, enabling users to monitor order volumes, delivery performance, and operational trends through dynamic KPIs, charts, and slicers.

<p align="center">
  <img src="dashboard/dashboard.png" alt="Porter Delivery Dashboard" width="100%">
</p>


## Dashboard Features

The dashboard includes:

- Total Orders KPI
- Average Delivery Time KPI
- Average Order Value KPI
- Orders Delivered Within 30 Minutes KPI
- Markets Covered KPI
- Order Volume by Market
- Top 10 Categories by Average Delivery Time
- Peak Order Hours
- Weekly Delivery Time Trend
- Interactive Slicers
  - Market ID
  - Store Category
  - Order Protocol

---

## Key Business Insights

- Market 2 recorded the highest order volume.
- Average delivery time is 47.62 minutes.
- Only 13.14% of orders were delivered within 30 minutes.
- Peak ordering activity occurs during early morning hours.
- Delivery performance varies significantly across store categories.
- Price range has a moderate positive relationship with order value.
- Partner utilization shows only a weak relationship with delivery time, suggesting additional operational factors influence performance.

---

## Project Limitations

The dataset does not contain a unique Customer ID. Therefore, first-time and repeat customer analysis could not be performed without making unsupported assumptions.

---

## Skills Demonstrated

- Data Cleaning
- Data Validation
- Exploratory Data Analysis (EDA)
- Pivot Tables
- Pivot Charts
- Dashboard Design
- KPI Development
- Correlation Analysis
- Standard Deviation Analysis
- Business Insight Generation
- Excel Reporting

---

## Files Included

```
porter-delivery-excel-analysis/
│
├── analysis/
│   └── Porter_Delivery_Analysis.xlsx
│
├── data/
|   └── raw/
|       └── dataset.csv/
│   └── processed/
│       └── porter_delivery_cleaned.xlsx
│
├── docs/
│   └── porter_optimizing_delivery.pdf
│
├── dashboard/
│   └── Dashboard (inside Excel workbook)
├── report/
│   └── Porter_Delivery_Project_Report.pdf
└── README.md
```

---

## Tools Used

- Microsoft Excel
- Pivot Tables
- Pivot Charts
- Slicers
- Conditional Formatting
- Excel Functions
- Correlation (CORREL)
- Standard Deviation

---

## Conclusion

This project demonstrates an end-to-end Excel analytics workflow, including data cleaning, exploratory data analysis, statistical analysis, dashboard creation, and business reporting. The final interactive dashboard enables stakeholders to monitor delivery performance, demand patterns, and operational efficiency, making it suitable as a portfolio project for Data Analytics and Business Intelligence roles.