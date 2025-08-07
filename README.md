# Data-Analyst-Task3

# 📊 Power BI Dashboard – Sample Superstore

## 📁 Dataset
- Sample - Superstore.csv (uploaded)

## 🎯 Objective
Create a dynamic dashboard using Power BI to track and analyze sales KPIs.

## ✅ KPIs Included:
- Total Sales
- Total Profit
- Total Quantity
- Profit Margin %

## 📈 Visuals Used:
- KPI Cards
- Slicers (Region, Category, Segment, Year)
- Time-Series Line Chart
- Profit Margin Table with Conditional Formatting

## ⚙️ DAX Measures Used:
```DAX
Total Sales = SUM('Sample - Superstore'[Sales])
Total Profit = SUM('Sample - Superstore'[Profit])
Total Quantity = SUM('Sample - Superstore'[Quantity])
Profit Margin % = DIVIDE([Total Profit], [Total Sales]) * 100
