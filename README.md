# Shopify-Analysis

This project analyzes Shopify sales data in Power BI to generate actionable insights around transactional performance, customer behavior, and long-term value. Through interactive dashboards and DAX-based metrics, stakeholders can easily explore revenue patterns, retention trends, and product-level performance to inform strategic decisions.

🧩 Project Workflow

The project followed this structured workflow:

1. **Requirement Gathering & Business Requirements**
2. **Data Walkthrough**
3. **Data Connection** (Shopify to Power BI)
4. **Data Cleaning & Quality Check**
5. **Data Modeling**
6. **Data Processing**
7. **DAX Calculations** (KPIs and custom logic)
8. **Dashboard Layout Design**
9. **Chart Development & Formatting**
10. **Report Development**
11. **Insights Generation**

🎯 Business Objective

Analyze Shopify transaction data to uncover patterns in:

  * Revenue performance
  * Customer acquisition vs retention
  * Purchasing behavior
Build an interactive executive dashboard to support data-driven business decisions.

📊 Key KPIs

Metrics tracked with DAX:

1. Transactions Performance

**Net Sales** – Revenue excluding tax
**Total Quantity** – Number of products sold
**Net Average Order Value** – Average revenue per order (before tax)

2. Customer Purchase Behavior

**Total Customers** – Unique buyers
**Single Order Customers** – Customers with exactly one order
**Repeat Customers** – Customers with more than one order (loyalty indicators)

3. Retention & Value

**Lifetime Value (LTV)** – Total revenue per customer over time
**Repeat Rate** – Percentage of returning customers
**Purchase Frequency** – Average number of orders per customer

📈 Dashboard Pages & Visuals

Measure Selector

* Enables dynamic switching between **Net Sales**, **Total Quantity**, **Total Customers**, and **Repeat Customers**

Shopify Analysis – Regional Overview

**Province-Level Fill Map**: Color-coded by measure
**City-Level Bubble / Heat Map**: Bubble size or heat intensity reflects the measure; tooltips show all KPIs
**City Bar Chart**: Top-performing cities sorted in descending order of the selected KPI

Shopify Analysis – Sales Trend Over Time

**Daily Trend Area Chart**: Daily performance of the selected metric
**Hourly Activity Chart**: Bar or line chart by hour (0–23), showing time-of-day peaks

Additional Analyses

**Gateway Payment Methods**

  * Breakdown of payment methods (highest vs lowest usage)
  * Region or campaign-level preferences
  
**Product Type Performance**

  * Revenue and order volume by product category
  * Engagement variation across categories

Drill-through / Detail Page

* Displays transaction-level data
* Enables drill-through from summary visuals to raw records for deeper analysis

## 🧑‍💻 Tools & Tech Stack

**Power BI Desktop** – data modeling, visualization, and dashboard development

**DAX** – calculation engine for KPI metrics

**Source data files** – raw and processed Shopify exports (CSV/Excel)
