# Elevate-Labs-task-2
# 📊 Sales Performance Analysis Dashboard

This Power BI dashboard provides a comprehensive analysis of sales performance across various dimensions, including product categories, customer segments, regions, and time periods. It is designed to help stakeholders uncover trends, identify high/low-performing areas, and make data-driven business decisions.

---

## 🎯 Objective

To visualize and analyze sales, profit, and order data to uncover growth opportunities, track performance trends, and enable strategic business insights.

---

## 🧰 Tools & Technologies

- **Power BI Desktop**
- **Data Source:** CSV file (e.g., Superstore dataset)
- **DAX** for calculated columns and KPIs
- **Power Query** for data cleaning and transformation

---

## 📁 Dataset Fields Used

- `Order Date` (Date)
- `Sales` (Currency)
- `Profit` (Currency)
- `Quantity` (Numeric)
- `Discount` (Percentage)
- `Region`, `State`, `City`
- `Product Category`, `Sub-Category`, `Product Name`
- `Customer Segment`
- `Ship Mode`

---

## 📈 Visualizations Included

| **Chart Type**        | **Purpose**                                  |
|-----------------------|----------------------------------------------|
| Line Chart            | Sales trend over time                        |
| Column/Bar Chart      | Sales by Category, Region, Segment           |
| KPI Cards             | Total Sales, Profit, Orders, Profit Margin   |
| Donut Chart           | Sales by Customer Segment                    |
| Filled Map            | Regional sales performance                   |
| Tree Map              | Product Category/Sub-category sales          |
| Scatter Plot          | Sales vs. Profit by Product                  |
| Table/Matrix          | Detailed drill-down of orders and revenue    |
| Slicers               | Interactive filters (e.g., Region, Category) |

---

## 📌 Key Features

- 🚀 **Interactive slicers** for dynamic filtering
- 📍 **Map visualization** to analyze regional performance
- 📊 **Trend analysis** using line charts and KPIs
- 🔍 **Drill-down capabilities** for granular insights
- ✅ **User-friendly layout** with clean visuals and titles

---

## 📦 Folder Structure

```plaintext
📁 Sales-Performance-Dashboard/
│
├── 📁 Dataset/
│   └── superstore_cleaned.csv
│
├── 📁 Reports/
│   └── Sales_Performance.pbix
│
├── 📁 Screenshots/
│   └── dashboard-preview.png
│
├── README.md
└── LICENSE
