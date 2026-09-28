# 📊 Sales Performance Dashboard - Power BI

## 📌 Project Overview
Built an interactive Sales Performance Dashboard using Power BI to analyze Superstore sales data (2014-2017). This dashboard helps stakeholders track overall business performance, profitability, and regional sales insights for data-driven decision making.

## 🎯 Problem Statement
The business was facing challenges in identifying:
- Which regions and products are most/least profitable?
- What are the seasonal sales trends?
- Which customer segments drive maximum revenue?

This dashboard solves it by providing a single view of sales performance.

## 📊 Key KPIs Tracked
- **Total Sales:** $632.63K
- **Total Profit:** $85.80K
- **Profit Margin:** 13.56%
- **Total Orders:** 1K
- **Total Quantity:** 10K

## ✨ Dashboard Features
- **Executive Summary:** Overall KPIs with cards
- **Sales Trend Analysis:** Month-wise and Year-wise sales trend (Line Chart)
- **Category & Sub-Category Analysis:** Sales by Technology, Furniture, Office Supplies (Donut & Bar Chart)
- **Regional Performance:** Profit distribution by East, West, Central, South (Map & Treemap)
- **State & Product Drill-down:** Detailed product level performance
- **Interactive Filters:** Year, Month, Segment, Ship Mode (Slicers)

## 🛠️ Tools & Skills Used
- Power BI Desktop
- Power Query - Data Cleaning & Transformation
- DAX (Data Analysis Expressions)
- Data Modeling & Relationships
- Data Visualization

## 🧮 DAX Measures Created
```DAX
Total Sales = SUM(Superstore[Sales])
Total Profit = SUM(Superstore[Profit])
Profit Margin = DIVIDE([Total Profit], [Total Sales], 0)
Total Orders = DISTINCTCOUNT(Superstore[Order ID])
