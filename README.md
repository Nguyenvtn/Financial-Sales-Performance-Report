# :bar_chart: Financial & Sales Performance Analysis (Power BI Project)

## Project Overview

This project analyzes a 13-month financial and sales performance dataset covering sales, cost, profit, forecast, product, country, and customer segment data.

The objective was to transform raw sales data into an interactive executive dashboard that provides insights into revenue, profitability, sales trends, customer segments, geographic performance, and forecast accuracy.

Unlike SQL-based projects, this analysis relies on Power BI's data modeling capabilities, Power Query transformations, and DAX measures to calculate KPIs and generate business insights.

The project demonstrates how Power BI can be used to support data-driven decision-making in finance and sales environments.

---

## Dataset

The dataset contains transactional sales and financial data covering multiple products, customer segments, countries, and reporting periods.

Main fields used in the analysis include:

* Date
* Country
* Segment
* Product
* Units Sold
* Manufacturing Price
* Sale Price
* Gross Sales
* Discounts
* Actual Sales
* Forecast Sales
* Cost of Goods Sold (COGS)
* Profit

The dataset enables analysis of sales performance, profitability, forecast accuracy, and business trends across different dimensions.

---

## Data Preparation

The data preparation process was performed using **Power Query**.

### Key transformation steps

* Data cleaning and validation
* Data type formatting
* Creation of calculated fields
* Removal of unnecessary columns
* Data modeling and relationship management

### Date Table Creation

A custom Date Table was created in Power Query based on the sales transaction date range.

The Date Table includes:

* Year
* Quarter
* Month
* Month Name
* Month-Year
* Fiscal reporting attributes

This Date Table enables time intelligence analysis and supports trend reporting across multiple periods.

---

## KPI Calculations

Key business metrics were created using DAX measures.

Examples include:

* Net Sales
* COGS
* Net Profit
* Profit Margin %
* Forecast Variance
* Forecast Achievement %
* Month-over-Month Change %
* Sales Trend Analysis

These measures provide dynamic calculations that respond to user-selected filters and slicers.

---

## Project Structure

financial-sales-performance-analysis

│

├── data

│ └── Financials.xlsx

│

├── power-query

│ └── Data Cleaning & Date Table Creation

│

├── dax-measures

│ ├── Net Sales

│ ├── Net Profit

│ ├── Profit Margin

│ ├── Forecast Variance

│ ├── Forecast Achievement %

│ └── Time Intelligence Measures

│

├── dashboard

│ ├── Overview Page

│ └── Forecast & Details Page

│

└── README.md

---

## Analysis Workflow

The analysis follows a typical business intelligence process:

1. Data collection
2. Data cleaning and transformation
3. Date table creation
4. Data modeling
5. KPI development using DAX
6. Dashboard design and visualization
7. Business insight generation
8. Executive reporting

---

## Business Questions

This analysis aims to answer the following questions:

* How is the company performing in terms of sales and profitability?
* Which countries contribute the most to revenue?
* Which customer segments generate the highest sales?
* How does actual sales performance compare with forecast?
* Which products exceed or miss sales targets?
* How does profit margin evolve over time?
* Where should management focus improvement efforts?

---

## Dashboard Features

### Overview Page

* Net Sales KPI
* COGS KPI
* Net Profit KPI
* Profit Margin KPI
* Sales by Country
* Sales by Segment
* Sales vs COGS Trend
* Profit Margin Trend

### Forecast & Details Page

* Actual vs Forecast Sales
* Forecast Achievement %
* Sales by Country
* Product Performance Analysis
* Forecast Variance Analysis
* Monthly Trend Monitoring

---

## Tools Used

* Power BI Desktop
* Power Query
* DAX
* Excel

---

## Business Value

This dashboard helps management:

* Monitor financial performance
* Track profitability trends
* Evaluate forecast accuracy
* Identify high-performing products and segments
* Support strategic and operational decision-making

The project demonstrates how Power BI can transform raw business data into actionable insights through interactive reporting and KPI driven analysis.



