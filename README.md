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
```

## 📂 Dataset
- **Source:** Superstore Dataset from Kaggle
- **Author / Owner:** Vivek468 (Kaggle) + Tableau Community
- **Link:** https://www.kaggle.com/datasets/vivek468/superstore-dataset-final
- **Period:** 2014-2017
- **Rows:** 9,994 Orders

## 📁 Repository Structure
- `Sales_Performance_Dashboard.pbix` - Power BI source file
- `Sales_Performance_Dashboard_Superstore.pdf` - Dashboard preview (4 Pages)
- `README.md` - Project documentation

## 🔍 Key Insights
1. Technology category generates the highest sales of $256K (40% of total sales).
2. East region is the most profitable region contributing 38.42% of total profit.
3. Peak sales were observed in March ($105K) and January ($96K) - seasonal trend.
4. Consumer segment drives maximum sales compared to Corporate and Home Office.

## 🚀 How to Use
1. Download the `.pbix` file
2. Open in Power BI Desktop
3. Refresh data and interact with filters

## 🔗 Live Dashboard
https://drive.google.com/file/d/1wyPbH7j5fzueki4huq8f3nD3s362pbBC/view?usp=drivesdk

## 👩‍💻 Created By
**Kiruba V** | Aspiring Data Analyst | Power BI | SQL | Python
