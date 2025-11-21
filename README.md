# FreshKart-Dashboard-

📊 FreshKart Retail Sales Analysis – Basic Power BI Visuals

A complete beginner-friendly business case study demonstrating how basic charts solve real retail problems.

🧩 Project Overview

FreshKart is an Indian FMCG & Grocery retail company operating across 4 major regions.
The goal of this project is to analyze monthly sales, regional performance, product contribution, and profitability using Basic Charts in Power BI.

This project demonstrates how simple visuals—Column, Bar, Line, Area, Stacked Column, and Combo Charts—can help leadership make data-driven decisions.

🎯 Key Objectives

Identify peak and low-performing months

Compare sales across regions

Understand sales trend over time

Analyze product category contribution

Examine relationship between Sales & Profit

Generate actionable business insights

📁 Dataset Description

The project uses 3 structured tables:

1. Sales Data (Fact Table)

Contains transaction-level records:

OrderID

OrderDate

Month

Product, Category, SubCategory

Region, City

Units Sold, Unit Price

Total Sales, Discount, Profit

2. Customers (Dimension Table)

Contains customer demographics:

CustomerID

Gender

Age

Membership Level

State

3. Product Master (Dimension Table)

Contains product metadata:

Product

Category

SubCategory

Brand

Launch Year

All datasets are included in the /data folder.

📝 Business Case Study Summary
1️⃣ Monthly Sales Comparison (Column Chart)

Business Need: Identify peak & low sales months.
Decision:

High sales months → Increase stock & supply

Low sales months → Introduce discounts or marketing campaigns

2️⃣ Regional Performance (Bar Chart)

Business Need: Which region performs best?
Decision:

High-performing regions → Expand distribution

Low-performing regions → Add sales reps / targeted campaigns

3️⃣ Sales Trend Over Time (Line Chart)

Business Need: Is sales trending up or down?
Decision:

Downtrend → Launch offers

Uptrend → Increase inventory & logistics capacity

4️⃣ Sales Volume Analysis (Area Chart)

Business Need: Evaluate month-wise sales magnitude.
Decision:

High volume months → Increase warehouse planning

Low volume → Optimize supply chain

5️⃣ Category Contribution by Month (Stacked Column)

Business Need: Which product categories drive the most revenue?
Decision:

High-performing categories → Increase marketing spend

Weak categories → Strategy/Portfolio revision

6️⃣ Sales vs Profit Trend (Combo Chart)

Business Need: Understand Sales & Profit relationship.
Decision:

High Sales + Low Profit → High discounts/bad margins

Low Sales + High Profit → Premium products performing well

📊 Power BI Visuals Used

Column Chart

Bar Chart

Line Chart

Area Chart

Stacked Column Chart

Combo Chart (Column + Line)

Slicers

Cards/KPI

📈 Skills Demonstrated

Data Cleaning

Data Modelling

Creating relationships

Power BI Basic Visuals

Trend Analysis

Category Analysis

Performance Dashboards

Insight writing & business decision-making

📦 Folder Structure
FreshKart-Retail-Basic-Analysis/
│
├── README.md
├── data/
│   ├── Sales_Data.xlsx
│   ├── Customers.xlsx
│   └── Product_Master.xlsx
│    
├── powerbi/
│   └── FreshKart_Basic_Charts.pbix
│
└── screenshots/
    ├── 01_Monthly_Sales_Column.png
    ├── 02_Region_Bar.png
    └── 03_Sales_Trend_Line.png

🚀 How to Use This Project

Download the .xlsx files from the /data folder.

Import them into Power BI Desktop.

Create relationships:

Product → Category mapping

Customer → Sales linking

Build the basic charts shown in the case study.

Interpret insights and add them to a smart narrative or text box.

Export screenshots and upload to GitHub.

🧠 Business Value Delivered

This project helps FreshKart to:

Optimize inventory

Plan marketing budgets

Understand customer segments

Identify focus categories

Balance profit and sales

Improve operational efficiency

📌 Future Enhancements

Add DAX measures for YoY/MoM growth

Create advanced visuals (Key Influencer, Decomposition Tree)

Build a full interactive dashboard

Add forecasting

Add RLS (Row Level Security)

🧑‍💻 Author

Ankit R. Ray
Data Analyst | Power BI | SQL | Python
