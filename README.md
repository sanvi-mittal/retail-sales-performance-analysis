# Retail Sales Performance Analysis

A retail sales performance analysis project developed using Microsoft Excel to evaluate sales, profit, customer segments, products, brands, cities, payment modes, and sales executives through KPIs, PivotTables, PivotCharts, and a dashboard.

---

## 📌 Project Overview

This project analyzes a retail sales transaction dataset containing 500 records across May and June 2026.

The objective was to transform raw retail transaction data into meaningful business insights using Microsoft Excel.

The analysis covers:

- Overall sales and profitability
- Monthly revenue performance
- City-wise revenue
- Brand-wise revenue
- Product-wise revenue
- Payment mode analysis
- Customer segment analysis
- Sales executive performance
- Delivery status
- Order size
- Profit margin

The final output is an Excel-based analytical dashboard supported by PivotTables and PivotCharts.

---

## 🎯 Objectives

The main objectives of this project were to:

1. Understand and structure the retail transaction dataset.
2. Check the dataset for missing and duplicate values.
3. Create useful calculated fields for analysis.
4. Calculate important business KPIs.
5. Analyze sales performance across different business dimensions.
6. Use PivotTables to summarize large amounts of transaction data.
7. Use PivotCharts to visualize the analysis.
8. Build a dashboard containing key performance indicators and visualizations.
9. Convert numerical results into useful business insights.

---

## 📊 Dataset

The dataset contains **500 retail transaction records** and **26 columns**.

### Major Dataset Fields

| Category | Fields |
|---|---|
| Order Information | Order ID, Invoice ID, Order Date |
| Customer Information | Customer ID, Customer Name, Gender, Customer Type |
| Location | City |
| Product Information | Product Category, Product Name, Brand |
| Transaction Information | Quantity, Unit Price, Discount %, Sales, Cost, Profit |
| Service Information | Payment Mode, Customer Rating, Delivery Status |
| Sales Responsibility | Sales Executive |

The transaction dates covered in the dataset are from **May and June 2026**.

---

## 🧹 Data Cleaning & Preparation

Before performing the analysis, the dataset was checked and prepared for analysis.

The following checks were performed:

- Total number of records
- Total number of columns
- Missing values
- Duplicate records
- Date format
- Data types
- Basic data validation
- Outlier/quality checks

The dataset contained:

- **500 records**
- **26 columns**
- **0 missing values**
- **0 duplicate records**

Additional calculated fields were also created to support business analysis.

---

## 🧮 Calculated Fields

The following fields were created for analysis:

### Customer Segment

Customers were categorized into:

- High Value
- Medium Value
- Low Value

### Order Size

Orders were categorized based on order quantity into:

- Regular Order
- Bulk Order

### Day

The day of the week was derived from the Order Date.

### Profit Margin %

Profit margin was calculated to understand profitability relative to sales.

---

## 📌 Key Performance Indicators (KPIs)

The dashboard uses the following major KPIs:

| KPI | Value |
|---|---:|
| Total Revenue | ₹12,482,584.35 |
| Total Profit | ₹2,515,406.65 |
| Total Orders | 500 |
| Average Order Value | ₹24,965.17 |
| Profit Margin | 20.15% |

These KPIs provide a quick overview of the overall business performance.

---

## 🔄 PivotTable Analysis

PivotTables were used to summarize and analyze the transaction-level data.

The project includes analysis for:

### 1. Monthly Revenue

Revenue was compared between May and June to identify monthly performance differences.

### 2. City-wise Revenue

Revenue was analyzed across different cities to identify stronger and weaker geographical markets.

### 3. Brand-wise Revenue

Revenue was compared across brands to identify the highest-performing brands.

### 4. Product-wise Revenue

Products were ranked based on their contribution to total sales.

### 5. Payment Mode

Sales were analyzed based on payment methods such as:

- UPI
- Cash
- Card
- Bank Transfer

### 6. Customer Segment

Sales performance was analyzed across:

- High Value
- Medium Value
- Low Value

### 7. Sales Executive

Sales and performance were compared across different sales executives.

---

## 📈 PivotCharts

PivotCharts were created from the PivotTable summaries to make the analysis easier to understand visually.

The visualizations include:

- Monthly Revenue Trend
- Revenue by City
- Revenue by Brand
- Revenue by Product
- Payment Mode Analysis
- Customer Segment Analysis
- Sales Executive Performance

---

## 📊 Dashboard

A final Excel dashboard was created to provide a summarized view of the business performance.

The dashboard includes KPI cards for:

- Total Revenue
- Total Profit
- Total Orders
- Average Order Value
- Profit Margin

It also includes visual analysis of sales performance across different dimensions.

### Dashboard Preview

![Dashboard Preview](Screenshots/dashboard.png)

---

## 🔍 Key Analysis Areas

The project focuses on answering business questions such as:

- How much total revenue was generated?
- How much profit was generated?
- What was the average order value?
- How did revenue change between May and June?
- Which cities generated the highest revenue?
- Which brands contributed the most revenue?
- Which products performed best?
- Which payment modes were most commonly used?
- Which customer segments contributed to sales?
- How did sales executives perform?
- What was the overall profit margin?

---

## 🛠️ Tools Used

- **Microsoft Excel**
- Excel Tables
- Excel Formulas
- PivotTables
- PivotCharts
- Dashboard Design
- Data Cleaning
- KPI Analysis

---

## 📁 Project Structure

```text
Retail-Sales-Performance-Analysis/
│
├── README.md
│
├── Excel/
│   └── Retail_Sales_Performance_Analysis.xlsx
│
├── Report/
│   └── Internship_Report.pdf
│
├── Presentation/
│   └── Internship_Presentation.pptx
│
└── Screenshots/
    ├── dashboard.png
    ├── monthly-revenue.png
    ├── revenue-by-city.png
    ├── revenue-by-brand.png
    └── revenue-by-product.png
