# 🛒 US Superstore Profit Analysis — Power BI Dashboard

## 📌 Project Overview
This project analyzes sales and profit data from a US-based retail superstore to uncover key business insights across regions, categories, and time periods. The central business question driving this analysis is:

> **"What is driving low profit margins — and how are discounts impacting profitability?"**

---

## 📊 Dashboard Pages

| Page | Description |
|---|---|
| **Executive Summary** | High-level KPIs — Total Sales, Total Profit, Profit Margin %, Total Orders with year slicer |
| **Sales Trend Analysis** | Month-wise Sales LY vs Sales TY comparison with Growth % using DAX |
| **Category Performance** | Waterfall chart showing Total Sales by Category and Year |
| **Regional Performance** | Hierarchy drill-down — Country → Region → State → City → Postal Code |
| **West Region Deep Dive** | Drill-through page showing category-wise sales for the most profitable region |
| **Sub-Category Analysis** | Conditional formatting table showing Sales, Profit, Quantity and Discount by Sub-Category |
| **Discount Impact** | Scatter plot showing negative correlation between Discount % and Profit Margin % |

---

## 💡 Key Insights

- 📉 **Furniture has the lowest profit margin (2.5%)** despite being the second highest in sales ($742K)
- 🔴 **Tables and Bookcases are loss-making** sub-categories with negative profits of -$17K and -$3.4K respectively
- 📈 **Technology is the most profitable category** with $145K profit on $836K sales (17.4% margin)
- 🌍 **West region is the most profitable** contributing $108K (37.8%) of total profit
- 💸 **As Discount increases beyond 20%, Profit Margin turns negative** — high discounts are directly hurting profitability

---

## 🛠️ Tools & Techniques Used

- **Tool:** Microsoft Power BI Desktop
- **Data Modeling:** Star schema with Orders, Returns, People and DateTable
- **DAX Measures:**
  - Sales LY (SAMEPERIODLASTYEAR)
  - Sales TY
  - Growth %
  - Profit Margin %
- **Visualizations:** Line & Clustered Column Chart, Waterfall Chart, Donut Chart, Scatter Plot, Table with Conditional Formatting
- **Features:** Drill-through, Hierarchy, Bookmarks, Navigation Buttons, Conditional Formatting, Trend Line

---

## 📁 Dataset

- **Source:** Sample Superstore Dataset
- **File:** `sample_-_superstore.xlsx`
- **Tables:** Orders (9,994 rows), Returns, People
- **Time Period:** January 2014 — December 2017
- **Fields:** Order Date, Ship Date, Customer, Region, Category, Sub-Category, Sales, Profit, Quantity, Discount

---

## 📸 Screenshots

| Executive Summary | Sales Trend Analysis |
|---|---|
| ![Executive Summary](screenshots/1_executive_summary.png) | ![Sales Trend](screenshots/2_sales_trend.png) |

| Category Performance | Regional Performance |
|---|---|
| ![Category](screenshots/3_category_performance.png) | ![Regional](screenshots/4_regional_performance.png) |

| Sub-Category Analysis | Discount Impact |
|---|---|
| ![Table](screenshots/5_subcategory_analysis.png) | ![Discount](screenshots/6_discount_impact.png) |

---

## 🚀 How to Open

1. Download and install [Power BI Desktop](https://powerbi.microsoft.com/desktop/)
2. Clone or download this repository
3. Open `US_Superstore_Profit_Analysis.pbix`
4. Make sure `sample_-_superstore.xlsx` is in the same folder
5. Refresh data if prompted

---

## 👤 Author

**Mohammed Zabin Shukkoor**  
 

---
