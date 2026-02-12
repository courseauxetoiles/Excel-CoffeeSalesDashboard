# ☕ Coffee Sales Analysis Dashboard (Excel)
## 📌 Project Overview

The Coffee Sales Analysis Dashboard is an interactive Microsoft Excel project designed to analyze coffee sales performance across customers, countries, and products.

The dashboard transforms raw transactional data into meaningful insights, enabling users to:
- Track total sales trends
- Identify top customers
- Compare sales by country
- Understand product performance
-  Make data-driven business decisions
This project demonstrates practical skills in **data cleaning, modeling, analysis, and dashboard design using Excel.**

------------------------------------------------------------------------

## 🎯 Project Purpose
The main objectives of this project are to:
- Centralize coffee sales data from multiple tables
- Create a structured data model using lookups and calculated fields
- Analyze sales performance across multiple dimensions
- Present insights through a clean, interactive Excel dashboard

------------------------------------------------------------------------

## 📂 File Structure

CoffeeOrders.xlsx\
coffeeOrdersData.xlsx\
coffeeOrdersProject.xlsx (Main file)


**Main File**
- **coffeeOrdersProject.xlsx** → Contains the full data model, analysis, and dashboard.\

------------------------------------------------------------------------

## 🗂 Workbook & Worksheet Description

  Worksheet  Description
  ----------------- -----------------------
  Dashboard  	      Interactive visual dashboard with slicers and charts
  TotalSales      	Pivot table and analysis of total sales over time
  CountryBarChart	  Pivot analysis of sales by country
  Top5Customers	    Top 5 customers based on total sales
  orders	          Raw transactional order data
  customers	        Customer master data
  products	        Product and pricing details
  
🧾 Data Structure
1. orders Sheet
Column	Description
Order ID	Unique identifier for each order
Order Date	Date of purchase
Customer ID	Foreign key to customers
Product ID	Foreign key to products
Sales	Total sales value per order
Coffee Type Name	Coffee type (e.g., Arabica, Robusta)
Roast Type Name	Roast level (Light, Medium, Dark)
Loyalty Card	Indicates loyalty membership
2. customers Sheet
Column	Description
Customer ID	Unique customer identifier
Customer Name	Full name
Email	Email address
Phone Number	Contact number
Address Line 1	Street address
City	Customer city
Country	Customer country
Postcode	Postal code
Loyalty Card	Loyalty membership flag
3. products Sheet
Column	Description
Product ID	Unique product identifier
Coffee Type	Type of coffee
Roast Type	Roast level
Size	Package size
Unit Price	Selling price
Price per 100g	Standardized price metric
Profit	Profit per unit
🔍 Analysis Process

Data Cleaning

Ensured consistent IDs across tables

Removed blanks and formatting errors

Standardized coffee and roast names

Data Modeling

Used XLOOKUP / VLOOKUP to combine product and customer data into orders

Created calculated columns for sales metrics

Pivot Table Creation

Total sales by date

Sales by country

Top 5 customers

Sales by coffee type and roast type

Dashboard Design

Built charts linked to PivotTables

Added slicers for interactivity

Applied consistent formatting and layout

📊 Dashboard Features

Total Sales Trend
Line chart showing overall revenue over time.

Sales by Country
Bar chart comparing total sales per country.

Top 5 Customers
Ranked customer performance based on total spending.

Interactive Filters (Slicers)
Filter by:

Coffee Type

Roast Type

Loyalty Card

All visuals update dynamically when slicers are changed.

🧠 Key Insights You Can Extract

Which country generates the highest revenue

Which coffee type and roast sells best

Who the top customers are

How loyalty card members impact revenue

Sales trends across time

🛠 Tools & Techniques Used

Microsoft Excel

PivotTables & PivotCharts

XLOOKUP / VLOOKUP

IF & calculated fields

Slicers

Data validation & formatting

Dashboard layout and chart design

▶ How to Use the Dashboard

Open coffeeOrdersProject.xlsx

Go to the Dashboard sheet

Use the slicers to filter by:

Coffee Type

Roast Type

Loyalty Card

Explore how charts and KPIs update automatically

🚀 Future Improvements

Add monthly and yearly trend analysis

Include profit margin visualizations

Create customer segmentation

Add geographic map visualization

Automate data refresh using Power Query

📌 Author

Raihan Ahmad Abiyyu
Aspiring Data Analyst / Business Intelligence
GitHub: courseauxetoiles
