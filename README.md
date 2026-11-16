# D2C Skincare E-Commerce Analytics

## Project Overview
This project features a comprehensive Power BI analytics dashboard built for a Direct-to-Consumer (D2C) skincare brand. The objective is to analyze transaction data, customer demographics, and product performance to generate actionable insights for inventory planning, sales channel optimization, and marketing strategies.

## Tech Stack & Concepts Used
- **Business Intelligence:** Power BI
- **Data Modeling:** Star Schema (Fact and Dimension tables), Relationship mapping, Cross-filtering
- **Calculations:** DAX (Data Analysis Expressions), Time Intelligence functions

## Data Architecture
The project utilizes a relational database structure transformed into a Star Schema within Power BI. 
- **Fact Tables:** Orders, Order Items, Returns, Reviews
- **Dimension Tables:** Customers, Products, Master Calendar (Custom DAX Date Table)

## Dashboard Features
The interactive dark-mode dashboard tracks the core health of the D2C business:
- **Executive KPIs:** Real-time tracking of Total Revenue (₹1.12M), Total Orders (1.25K), and Average Order Value (₹897.63).
- **Time-Series Analysis:** A dynamic line chart mapping monthly revenue trends across 2024 and 2025 to identify seasonal peaks.
- **Product Performance:** A Treemap visualizing order volume across skincare categories (Serum, Moisturizer, Sunscreen, etc.).
- **Customer Behavior & Channels:** Donut and Column charts breaking down orders by demographic, sales channel (Website, App, Marketplace), and payment method.

## Key Business Insights
1. **Sales Channel Dominance:** The brand's proprietary website is the strongest acquisition channel, driving 55.84% of total orders, minimizing marketplace commission dependencies.
2. **Payment Preferences:** UPI is overwhelmingly the most used payment method, highlighting the need for a frictionless mobile checkout experience for Indian consumers.
3. **Inventory Focus:** Serums and Moisturizers generate the highest order counts, indicating these should be prioritized for stock forecasting and targeted ad spend.
4. **Seasonality:** Revenue saw a significant spike in October 2024, aligning with major regional festive shopping behaviors.

## How to View the Project
1. Download the `D2C_Skincare_Dashboard.pbix` file from this repository.
2. Open the file in Power BI Desktop to interact with the slicers and visuals.
