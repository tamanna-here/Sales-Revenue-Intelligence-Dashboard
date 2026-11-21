# Sales & Revenue Intelligence Dashboard

An interactive Power BI dashboard built to analyse retail sales, revenue performance, product performance, and customer activity using the Online Retail dataset.

## Dashboard Preview

![Sales & Revenue Intelligence Dashboard](https://github.com/user-attachments/assets/fa19e785-7e88-47f1-8a15-712df816aaba)

## Project Overview

This project transforms raw retail transaction data into meaningful business insights through an interactive Power BI dashboard. It focuses on analysing revenue trends, identifying top-performing products and markets, and understanding monthly customer activity.

## Tools & Technologies

- **Power BI Desktop** – Dashboard development and visualisation
- **Power Query** – Data cleaning and transformation
- **DAX** – Measures, KPIs, and business calculations
- **Microsoft Excel** – Source dataset

## Dataset

[Online Retail Dataset – UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/352/online+retail)

The dataset contains approximately 541,909 transaction records from December 2010 to December 2011. December 2011 contains only partial-month data, so it has been excluded from the dashboard's reporting period to maintain consistency.

## Dashboard Features

- **Key Performance Indicators:** Total Revenue, Total Orders, Total Customers, and Average Order Value.
- **Monthly Revenue Trend:** Tracks changes in revenue over time.
- **Revenue Contribution by Country:** Compares country-level revenue and groups smaller markets into "Others".
- **Top 10 Products by Revenue:** Identifies the products generating the highest revenue.
- **Monthly Active Customers:** Tracks the number of distinct purchasing customers each month.
- **Month-over-Month Growth:** Measures changes in revenue and active customers compared with the previous month.
- **Interactive Filters:** Year, Month, and Country slicers.
- **Dynamic Business Insights:** Highlights the top-performing market and product with their revenue contributions.

## Key Findings

Based on the November 2011 reporting period:

- **Top Market:** United Kingdom.
- **Revenue Growth:** 37% compared with October 2011.
- **Customer Growth:** 20% compared with October 2011.

These figures describe month-over-month performance and should be interpreted in the context of seasonal retail activity.

## Data Preparation

Data preparation and transformation were performed using Power Query. The process included:

- Checking duplicate records.
- Examining negative quantities and unit prices.
- Creating calculated Revenue and date-related columns.
- Creating a separate Date Table for time-based analysis.
- Excluding incomplete December 2011 data from the reporting period.

## Key Metric Definitions

- **Total Revenue:** Sum of transaction revenue.
- **Average Order Value (AOV):** Total Revenue divided by Total Orders.
- **Monthly Active Customers:** Distinct customers who made at least one purchase during a month.
- **Revenue Growth:** Percentage change in revenue compared with the previous month.
- **Customer Growth:** Percentage change in monthly active customers compared with the previous month.

*Note: The dataset's monetary values are denominated in British Pounds (GBP).*

## Business Recommendations

- **Market Diversification:** Evaluate opportunities to expand sales beyond the leading market and reduce dependence on a single country.
- **Product Strategy:** Use top-product performance to guide inventory planning and identify products worth promoting.
- **Customer Engagement:** Investigate changes in monthly active customers and develop campaigns to encourage repeat purchases.
- **Seasonal Planning:** Use monthly revenue trends to prepare inventory and marketing activities ahead of peak shopping periods.

## Project Files

- `sales_revenue_intelligence.pbix` – Interactive Power BI dashboard.
- `dashboard_preview.png` – Dashboard screenshot.

## How to Explore

1. Download the `.pbix` file from this repository.
2. Open it using Power BI Desktop.
3. If required, update the source dataset location in Power BI.
4. Use the interactive slicers to explore revenue and customer trends across different months and countries.

## Reporting Note

December 2011 was excluded because the available data for that month was incomplete. The dashboard therefore uses a consistent reporting period through November 2011.

---

**Developed as a Data Analytics Portfolio Project.**
