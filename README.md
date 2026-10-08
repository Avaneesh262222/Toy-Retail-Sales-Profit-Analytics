# Toy Retail Sales & Profit Analytics

An Excel-based data analytics project analyzing 100K+ toy retail transactions to understand sales performance, profitability, products, discounts, and key business KPIs.

## 📌 Project Overview

This project analyzes a toy retailer's transactional sales data using Microsoft Excel.

The objective is to transform raw sales data into meaningful business insights through:

- Data cleaning and preparation
- Revenue and cost analysis
- Profit and profit margin analysis
- Discount analysis
- KPI calculation
- Product-level sales analysis
- Sales channel analysis
- Interactive dashboard development

The project is designed as a practical Junior Data Analyst portfolio project and demonstrates how Excel can be used to answer common business questions from large transactional datasets.

---

## 📊 Dataset

The dataset contains approximately **100,000+ retail transactions**.

Key fields include:

- Order ID
- Customer ID
- Product Name
- Category
- Quantity
- Unit Price
- Discount
- Unit Cost
- Revenue
- Sales Channel
- Customer Segment
- City
- Inventory-related information

---

## 🛠️ Tools & Skills

### Tools
- Microsoft Excel
- GitHub

### Excel Skills
- SUMIF
- SUMIFS
- UNIQUE
- COUNTIF
- Excel formulas
- KPI calculations
- Profitability analysis
- Product-level analysis
- Sales channel analysis
- Data visualization
- Dashboard development

---

## 📈 Key KPIs

The analysis calculates important business KPIs including:

| KPI | Value |
|---|---:|
| Total Revenue | ₹425,229,360 |
| Total Profit | ₹142,471,050 |
| Total Cost | ₹282,758,310 |
| Overall Profit Margin | 33.50% |
| Total Units Sold | 303,999 |
| Total Orders | 101,500 |
| Average Order Value | ₹4,189.45 |
| Total Discount Given | ₹39,731,290 |
| Total MRP | ₹464,859,755 |

### Overall Profit Margin

Overall profit margin is calculated as:

`Total Profit / Total Revenue`

This gives an overall business-level margin rather than taking a simple average of individual transaction margins.

---

## 🔍 Analysis Performed

### 1. Revenue Analysis

Revenue was analyzed at different levels to understand sales performance.

Key calculations include:

- Total Revenue
- Revenue by Product
- Revenue by Category
- Revenue by Sales Channel
- Revenue trends over time

---

### 2. Cost & Profit Analysis

Calculated:

- Total Cost
- Profit
- Profit Margin
- Overall Profit Margin

Formula:

`Total Cost = Quantity × Unit Cost`

`Profit = Revenue − Total Cost`

`Profit Margin = Profit / Revenue`

---

### 3. Discount Analysis

Discount impact was calculated from MRP and actual revenue.

Formula:

`Discount in Rupees = (Quantity × Unit Price) − Revenue`

This helps measure the monetary value of discounts provided to customers.

---

### 4. Product Analysis

Product-level revenue was calculated using Excel `SUMIF`.

Example:

```excel
=SUMIF(Sales_Data_100K!$F$2:$F$101501,A2,Sales_Data_100K!$O$2:$O$101501)