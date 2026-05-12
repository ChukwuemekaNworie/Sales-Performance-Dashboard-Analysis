# WELL-UP – Sales Performance Dashboard

## Table of Contents
- [Project Overview](#project-overview)
- [Business Introduction](#business-introduction)
- [Business Problem](#business-problem)
- [Business Objective](#business-objective)
- [Process Taken](#process-taken)
- [Dashboard Features](#dashboard-features)
- [Tools](#tools)
- [Key Insights](#key-insights)
- [Recommendations](#recommendations)
- [Conclusion](#conclusion)

---

## Project Overview

This dashboard focuses on analyzing sales performance, customer behavior, regional revenue distribution, and product category profitability. Designed for **WELL-UP**, the dashboard provides an executive overview of revenue trends, profit margins, return rates, and customer patronage patterns.

The tool enables stakeholders to filter by region, track revenue growth over time, identify top-performing customer segments, and monitor product category performance.

![WELL-UP Sales Dashboard](Images/WELL-UP_Dashboard.jpeg)

---

## Business Introduction

WELL-UP operates in a multi-regional retail environment, serving customers across Australia, North America, Europe, Africa, and Asia. The company sells products across various categories to diverse customer demographics.

Management requires a centralized sales dashboard to:
- Monitor revenue by region and product category
- Track profit margins and returned items
- Analyze customer patronage by occupation and gender
- Identify revenue growth trends over time

---

## Business Problem

The organization faced several sales visibility challenges:

- Lack of real-time regional revenue comparison
- Difficulty identifying which customer occupations drive highest revenue
- Limited insights into profit margins and return rates
- Inability to track revenue growth over multi-year periods
- No centralized view of product category revenue distribution

---

## Business Objective

- Build an interactive sales performance dashboard
- Analyze revenue by region, product category, and customer segment
- Monitor profit margins and return rates
- Track revenue growth over time (2015–2024)
- Support strategic decision-making with data-driven insights

---

## Process Taken

### 1. Data Collection

Sales data was collected including:
- Revenue by region and product category
- Customer occupation and gender
- Order quantities and returned items
- Time-stamped transaction data (2015–2024)

### 2. Data Cleaning and Preparation

- Removed duplicate records
- Standardized region and category names
- Handled missing gender entries (categorized as "NA")
- Verified date formats for time series analysis

### 3. Data Modeling

- Established relationships between regions, products, and customer segments
- Created DAX measures for:
  - Total Revenue
  - Profit Margin
  - Revenue Growth (209.4%)
  - Returned Items Count

### 4. Dashboard Development

- Designed executive-level KPIs
- Created regional filter slicer
- Built time series line chart (Jan 2015 – Jul 2024)
- Added bar charts for:
  - Revenue by region
  - Occupation by customer patronage
  - Revenue by product categories
  - Revenue by customer gender

---

## Dashboard Features

### Region Filter

| Filter Options |
|----------------|
| Australia |
| Canada |
| Central |
| France |
| Germany |
| Northeast |

### Key Performance Indicators (KPIs)

| Metric | Value |
|--------|-------|
| Total Revenue | $24.91M |
| Profit Margin | 42.0% |
| Total Quantity Sold | 84K units |
| Total Returned Items | 1,828 |

### Visualizations Included

| Visualization | Description |
|---------------|-------------|
| Revenue by Region | Bar chart – Australia top at $6.91M |
| Occupation by Customer Patronage | Professional highest at $8.50M |
| Revenue by Year, Quarter, Month | Time series (Jan 2015 – Jul 2024) |
| Revenue by Product Categories | Top category at $24.27M |
| Revenue by Customer Gender | NA category at 0.63% ($0.16M) |
| Key Insights Callouts | 209.4% growth, top region, profit margin |

---

## Tools

| Tool | Purpose |
|------|---------|
| Microsoft Power BI | Dashboard development and visualization |
| DAX | Time intelligence and calculated measures |
| Power Query | Initial data cleaning |
| Slicers & Filters | Interactive dashboard controls |

---

## Key Insights

### Revenue Growth

- **Revenue grew 209.4%** from January 2015 to March 2017

### Profitability

- **Total Profit Margin:** 42.0% (Profit / Revenue)

### Regional Performance

| Region | Revenue ($M) |
|--------|--------------|
| Australia | 6.91 |
| North America | 10.00 |
| Southeast Asia | 5.00 |
| Southwest | 4.32 |
| Northwest | 2.81 |
| United Kingdom | 2.20 |
| Germany | 1.73 |
| France | 1.58 |

**Top Region:** Australia

### Customer Patronage by Occupation

| Occupation | Revenue ($M) |
|------------|--------------|
| Professional | 8.50 |
| Skilled Manual | 5.40 |
| Management | 4.60 |
| Clerical | 4.00 |
| Manual | 2.50 |

### Product Categories

- Highest revenue category generated **$24.27M**
- Significant drop-off after the top category

### Customer Gender

- NA (unspecified) gender accounts for **0.63%** of revenue ($0.16M)

### Returns

- **Total Returned Items:** 1,828 units

---

## Recommendations

| Area | Recommendation |
|------|----------------|
| Regional Strategy | Focus marketing investment on **Australia** and **North America** |
| Customer Targeting | Target **Professional** and **Skilled Manual** occupations |
| Returns Management | Investigate return reasons to reduce 1,828 returned items |
| Product Strategy | Analyze underperforming product categories for improvement |
| Profitability | Maintain or improve 42.0% profit margin through cost control |
| Growth Tracking | Continue tracking revenue growth quarterly to sustain momentum |

---

## Conclusion

The WELL-UP Sales Performance Dashboard provides executive-level visibility into revenue drivers, customer behavior, and regional performance. By leveraging these insights, management can make informed strategic decisions to sustain growth, optimize product mix, and enhance customer engagement.

---

## Dashboard Footer

> **All values are in USD**  
> **Source:** Sales Dataset from Kaggle 
> **Last Refresh:** May 21, 2024 — 10:30 AM

---

## How to Use This Dashboard

1. Apply **Region Filter** to view specific geographical performance
2. Review **KPI cards** for overall business health
3. Analyze **Revenue by Region** to identify top markets
4. Examine **Occupation by Customer Patronage** for targeting insights
5. Track **Time Series** chart for growth trends
6. Use **Product Categories** chart to optimize product mix
7. Monitor **Returned Items** to address quality or logistics issues
