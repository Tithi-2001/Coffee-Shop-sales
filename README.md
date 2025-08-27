

☕ Coffee Shop Sales Analysis
📌 Project Overview

This project analyzes coffee shop sales data to uncover key insights about customer behavior, product performance, and sales trends. The analysis was performed in Excel using PivotTables, PivotCharts, Slicers, and Dashboard techniques to create an interactive and dynamic sales reporting system.

The goal was to build a business-oriented dashboard that allows decision-makers to quickly track performance across stores, products, time periods, and customer preferences.

📂 Dataset Description

The dataset (Sheet1) contains detailed transaction-level data with the following key columns:

Transaction Details: transaction_id, transaction_date, transaction_time

Store Information: store_id, store_location

Product Details: product_id, product_category, product_type, product_detail, size

Sales Metrics: transaction_qty, unit_price, total bill

Time Attributes: month, month name, day name, day of week, hour

🔎 Methods & Analysis Performed
1. Data Cleaning & Preparation

Converted raw data into a structured Excel Table for easier referencing.

Created calculated columns for month, day name, day of week, and hour to support time-series analysis.

Ensured correct data types for dates, times, and numeric fields.

2. PivotTables & Measures

Built PivotTables to summarize:

Total Sales Revenue

Transaction Count

Quantity Sold

Sales by Product Category, Product Type, and Size

Sales by Store Location

Hourly, Daily, and Monthly Sales Trends

Used Power Pivot Measures (DAX) such as Total Sales = SUM([Total Bill]).

3. Dashboard Creation

Designed a dashboard sheet with the following:

KPI Cards (Text Boxes linked to PivotTable cells) → showing key measures like Total Sales, Total Quantity, Average Transaction Value.

Line Chart → showing hourly trends in sales quantity.

Pie Charts → showing product category mix and size distribution.

Slicers → interactive filtering by Day, Month, Product, and Store Location.

Applied consistent color themes, formatting, and layout to ensure readability.

4. Advanced Excel Features

Used GETPIVOTDATA to extract KPI values dynamically.

Linked Text Boxes to PivotTable cells for dynamic KPI display.

Applied interactive slicers and timelines for dynamic filtering.

📊 Key Insights

Peak Sales Hours: Highest order quantities occur between 8–11 AM (morning rush).

Best-Selling Products: Coffee beverages dominate, especially Drinks and Espresso-based products.

Day-wise Sales: Weekdays show steady performance, with Friday and Saturday having the highest transactions.

Store Performance: Some store locations outperform others, suggesting differences in customer footfall and demand.

Size Preference: Medium and Large sizes contribute the most to sales revenue.

🚀 Business Value

This analysis and dashboard empower management to:

Track real-time sales performance.

Identify high-demand time slots for staffing and inventory planning.

Optimize product offerings by identifying top-performing categories.

Compare store performance and strategize accordingly.

Enhance customer experience by aligning promotions with demand patterns.

🛠️ Tools & Skills Demonstrated

Excel (Advanced): PivotTables, PivotCharts, Slicers, Conditional Formatting.

Power Pivot (DAX): Custom Measures for Sales KPIs.

Dashboard Design: KPI Cards, Interactive Visuals, Layout & Storytelling.

Business Analysis: Translating raw sales data into actionable insights.
