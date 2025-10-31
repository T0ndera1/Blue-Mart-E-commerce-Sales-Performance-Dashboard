# Blue-Mart E-commerce Sales Performance Dashboard

**Tools:** Power BI | Excel (Power Query) | DAX | Data Modeling  

This project analyzes Blue-Mart’s online sales data to identify performance trends, profit drivers, and growth opportunities. The dashboard highlights total revenue, profit margin, regional performance, and customer segmentation insights to guide better business decisions.

---

## 🔧 Data Preparation
- Cleaned and transformed data using **Power Query** (removed duplicates, standardized formats)
- Created relationships between tables for orders, products, and customers
- Built **Date Table** and established time-intelligence measures

---

## 📊 Key DAX Measures
- **Total Sales:** `SUM(Sales[Revenue])`
- **Total Profit:** `SUM(Sales[Profit])`
- **Profit Margin %:** `DIVIDE([Total Profit], [Total Sales])`
- **YoY Growth:** `([Total Sales] - [Sales LY]) / [Sales LY]`

---

## 📈 Dashboard Insights
- The **South Region** shows strong sales growth but lower profit margins  
- **Top 3 Product Categories** contribute over 60% of total revenue  
- Identified **10% return rate** linked to 2 underperforming suppliers  
- Highlighted peak months and seasonal buying patterns  

---

## 🖼️ Dashboard Preview
## 🖼️ Dashboard Preview

<p align="center">
  <img src="Screenshot-2025-10-30-190036.png" alt="Blue-Mart Sales Overview" width="48%">
  <img src="Screenshot-2025-10-30-190113.png" alt="Blue-Mart Profit Analysis" width="48%">
</p>
---

## 🚀 Impact
This analysis improved marketing strategy and helped Blue-Mart target high-performing products and regions more efficiently.

---

## 📁 Files
- `Blue Mart Sales Performance.pbix` – Power BI report  
- `Blue Mart Dataset.xlsx` – Cleaned dataset (optional)  
- `images/` – Dashboard screenshots  
- `README.md` – Project documentation

---

## 🌐 View on Portfolio
