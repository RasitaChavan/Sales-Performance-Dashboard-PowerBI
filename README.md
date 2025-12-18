# Sales-Performance-Dashboard-PowerBI
Interactive Sales Performance Dashboard built using Power BI

# Project Overview

This project is an interactive Sales Performance Dashboard built using Power BI.
The dashboard helps analyze sales trends, customer contribution, and product performance to support business decision-making.
The focus of this project is on:
Clean data modeling using Star Schema
Creating meaningful KPIs
Building interactive and professional dashboards
Presenting business insights, not just visuals

# Dataset Description

The dataset contains sales transaction data with the following information:
Order details (Order ID, Order Date)
Product details
Customer details
Sales amount and profit
Country and year information
The data was cleaned and transformed using Power Query before modeling.

# Data Model

A Star Schema was implemented for better performance and clarity.
Tables Used:
Fact_Sales – Sales transactions (Sales, Orders)
Dim_Date – Date attributes (Year)
Dim_Product – Product information
Dim_Customer – Customer and country information
Relationships were created using one-to-many relationships from dimension tables to the fact table.

# Key KPIs

The following KPIs are displayed at the top of the dashboard:
Total Sales
Total Orders
Average Order Value
Sales YTD
Top Country Sales Contribution (%)

# Visualizations

The dashboard includes:
Line Chart – Total Sales by Year (trend analysis)
Bar Chart – Sales by Product
Donut Chart – Sales Contribution by Country
Table – Top Customers by Sales
Slicers – Year, Country, Product
Report Tooltips – Detailed sales and contribution insights on hover

# Key Business Insights

Sales peaked in one year and showed variation across years
A single country contributes the highest share of total sales
Certain product categories dominate overall revenue
Top customers contribute a significant portion of total sales

# Tools & Technologies

Power BI
Power Query
DAX
Excel (data understanding)

# Key Learnings

Implementing star schema improves model performance
Proper KPI selection helps answer business questions
Tooltips enhance user experience without cluttering visuals
Dashboard storytelling is as important as technical implementation
