# 📊 Executive Sales Performance Dashboard | Excel

An interactive business intelligence and sales analytics project built in Microsoft Excel. This project combines executive reporting, sales performance analysis, product and inventory monitoring, customer analytics, and operations and shipping analysis in a multi-dashboard reporting solution.

The project uses Excel dashboards, PivotTables, and a Power Pivot data model to transform business data into actionable insights. The data is based on the Northwind sample database.

---

## 📌 Project Overview

The Executive Sales Performance Dashboard provides a consolidated view of business performance across sales, products, customers, employees, inventory, and shipping operations.

The workbook includes five interactive dashboards supported by a structured data model.

### Key Business Questions

- How much revenue does the business generate?
- Which product categories contribute most to revenue?
- Which products generate the highest sales?
- How many orders are processed, and what is the average order value?
- How effectively are orders processed and delivered?
- Which customers generate the most revenue and orders?
- What is the current inventory position?
- Which products are out of stock?
- How do discounts affect revenue?
- How does performance vary across employees, shippers, and countries?

## 🎯 Project Objectives

- Develop interactive Excel dashboards for executive and operational reporting.
- Monitor key performance indicators (KPIs) across business functions.
- Analyze revenue, order volume, and product performance.
- Evaluate customer revenue contribution and ordering behavior.
- Track inventory availability and supplier-related metrics.
- Analyze order processing and shipping performance.
- Build a relational data model using Power Pivot.
- Present business metrics through clear and consistent visualizations.

## 📂 Repository Structure

```text
Executive_Sales_Performance_Dashboard_Excel/
├── Executive_Sales_Performance_Dashboard.xlsx
├── images/
│   ├── 01-executive-overview.PNG
│   ├── 02-sales-analysis.PNG
│   ├── 03-product-inventory.PNG
│   ├── 04-customer-analysis.PNG
│   ├── 05-operations-shipping.PNG
│   └── 06-data-model.PNG
└── README.md
```

## 📑 Dashboard Pages

| Dashboard | Main Focus |
|---|---|
| Executive Sales Dashboard | Revenue, orders, quantity sold, average order value, delivery rate, customer base, monthly and quarterly revenue trends, and revenue by category and product |
| Sales Analysis Dashboard | Top products by quantity sold, discount impact by category, average quantity ordered, revenue vs. quantity, and revenue before vs. after discount |
| Product & Inventory Dashboard | Product count, stock availability, out-of-stock products, suppliers, and inventory levels |
| Customer Analysis Dashboard | Customer revenue, order frequency, country distribution, and customer acquisition trends |
| Operations & Shipping Dashboard | Order processing, on-time delivery, employee performance, shipping carriers, and discount usage |

The workbook also includes a Power Pivot data model that connects the underlying business tables.

## 📊 Key Performance Indicators

| KPI | Value |
|---|---:|
| Total Revenue | $1.27M |
| Total Orders | 827 |
| Total Quantity Sold | 51.3K |
| Average Order Value | $1.53K |
| On-Time Delivery Rate | 95.53% |
| Customer Base | 91 |
| Average Fulfillment Time | 8.51 days |
| Total Products | 78 |
| Total Units in Stock | 3,159 |
| Out-of-Stock Products | 5 |
| Total Suppliers | 29 |
| Total Shippers | 3 |

## 🔍 Key Findings

- **Overall performance:** 827 orders from 91 customers generated **$1.27M in revenue**, with an average order value of $1.53K and about $13.9K revenue per customer.
- **Revenue is concentrated by country:** the USA ($244K) and Germany ($227K) together generate about **37%** of total revenue.
- **Top customers:** QUICK-Stop ($110K), Save-a-lot Markets ($104K), and Ernst Handel ($103K) each contribute over $100K.
- **Top categories:** Beverages ($268K) and Dairy Products ($235K) lead revenue, and the single best product, Côte de Blaye, generates $141K (about 11% of revenue).
- **Strong growth:** quarterly revenue rose from $70K (Q3 1996) to $298K (Q1 1998).
- **Discounts:** **39% of orders** used a discount, with a total discount amount of **$88.7K**.
- **Delivery:** the on-time delivery rate is **95.5%**, and Federal Shipping is the fastest carrier (7 days on average vs. 9 for the others).
- **Inventory:** **5 of 78 products (6%)** are out of stock, with 3,159 units in stock and 780 units on order.

## 🔎 Key Analytical Areas

### 1. Executive Sales Performance

- Monitor revenue and order volume.
- Evaluate average order value and total quantity sold.
- Analyze monthly and quarterly revenue trends.
- Compare revenue contributions across product categories.
- Identify top-performing products by revenue.

### 2. Product & Inventory Analysis

- Monitor total products and available inventory.
- Identify out-of-stock products and supplier patterns.
- Compare stock levels across categories.
- Analyze units in stock versus units on order.
- Evaluate product and supplier contributions.

### 3. Customer Analysis

- Measure total customer revenue and order volume.
- Identify customers with the highest revenue.
- Compare customers by order frequency.
- Analyze revenue distribution across countries.
- Track monthly customer acquisition trends.

### 4. Operations & Shipping Analysis

- Monitor total orders and average processing time.
- Evaluate on-time delivery performance.
- Compare order processing performance across employees.
- Analyze orders shipped by carrier.
- Compare delivery times across shipping providers.
- Examine discount usage and revenue before and after discounts.

## 🗃️ Data Model

The Power Pivot data model connects 8 business tables in a relational structure around `Orders`:

- **Orders** connects to **Customers**, **Employees**, and **Shippers**.
- **Order Details** connects to **Orders** and **Products**.
- **Products** connects to **Categories** and **Suppliers**.

The model supports analysis across related business tables and helps organize the workbook for consistent reporting.

![Power Pivot Data Model](images/Data%20Modeling.PNG)

## 🛠️ Tools & Techniques

- **Microsoft Excel:** Dashboard development and reporting.
- **Power Pivot:** Data modeling and table relationships.
- **DAX:** Measures for KPI calculations.
- **PivotTables:** Aggregation and interactive analysis.
- **Slicers and Timelines:** Interactive filtering by date.
- **Excel Charts:** KPI visualization and business performance reporting.

## 🚀 How to Use

1. Download or clone this repository.
2. Open `Executive_Sales_Performance_Dashboard.xlsx` in Microsoft Excel.
3. Enable editing if prompted and review any workbook security notifications.
4. If prompted, refresh the workbook's data connections or PivotTables as appropriate.
5. Explore the available dashboards and use the interactive filters and timelines.
6. Review the Power Pivot data model to understand the relationships between tables.

*Some Power Pivot features may require a compatible desktop version of Microsoft Excel.*

## ⚠️ Limitations & Future Improvements

- The data covers 1996 to 1998, and the last month (May 1998) is incomplete, so the final drop in the monthly revenue trend reflects the data cut-off, not a real decline.
- The dataset has no cost data, so the analysis covers revenue and discount impact but not profitability.
- Possible extensions: customer segmentation (RFM), a monthly revenue forecast, and profitability analysis if cost data becomes available.


## 🖼️ Dashboard Screenshots

### 1. Executive Sales Dashboard

![Executive Sales Dashboard](images/Overview%20report.PNG)

### 2. Sales Analysis Dashboard

![Sales Analysis Dashboard](images/Sales%20Analysis%20report%202.PNG)

### 3. Product & Inventory Dashboard

![Product and Inventory Dashboard](images/product%203.PNG)

### 4. Customer Analysis Dashboard

![Customer Analysis Dashboard](images/customer%204.PNG)

### 5. Operations & Shipping Dashboard

![Operations and Shipping Dashboard](images/operations%206.PNG)

### 6. Employee Analysis

![Employee Analysis](images/Employee%205.PNG)

### 7. Power Pivot Data Model

![Power Pivot Data Model](images/Data%20Modeling.PNG)


## 👩‍💻 Author

**Sohair Samer Yehia**: Data Analyst

- [LinkedIn](https://www.linkedin.com/in/sohair-samer)
- [GitHub](https://github.com/Sohairsamer11)
