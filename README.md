# Dairy Business Analytics Dashboard

## Executive Summary

The **Dairy Business Analytics Dashboard** is an interactive **Power BI Business Intelligence project** developed to analyze dairy business performance and generate actionable insights from transactional data.

The dashboard provides a consolidated view of key business metrics including **Total Revenue, Quantity Sold, Total Production, and Current Stock**. It also enables detailed analysis of revenue across **products, brands, locations, sales channels, and time periods**, along with production and inventory performance.

The project follows an end-to-end data analytics workflow, starting from data cleaning and transformation to data modeling, DAX-based calculations, and interactive visualization.

---

## Key Performance Indicators

| KPI                  |   Value |
| -------------------- | ------: |
| **Total Revenue**    | ₹58.73M |
| **Quantity Sold**    |   1.07M |
| **Total Production** |   2.17M |
| **Current Stock**    |   1.09M |

These KPIs provide a high-level overview of overall revenue performance, sales volume, production capacity, and inventory position.

---

## Dashboard Analysis

### Revenue Trend

The dashboard analyzes revenue performance over time using historical data from **2019 to 2022**.

The revenue trend helps identify:

* Growth and decline periods
* Seasonal sales patterns
* High-revenue periods
* Changes in customer demand
* Long-term business trends

These insights can support sales planning, demand forecasting, and resource allocation.

### Revenue by Product

Revenue is analyzed across different dairy products to identify the strongest contributors to overall sales.

The top revenue-generating products include:

| Product    | Approx. Revenue |
| ---------- | --------------: |
| **Curd**   |          ₹6.74M |
| **Butter** |          ₹6.28M |
| **Lassi**  |          ₹6.13M |
| **Milk**   |          ₹6.02M |
| **Paneer** |          ₹5.96M |

**Curd** is the highest revenue-generating product in the analyzed dataset.

This analysis can help with:

* Production planning
* Inventory management
* Product promotion
* Demand analysis
* Product portfolio optimization

### Revenue by Sales Channel

The dashboard evaluates revenue contribution across three major sales channels:

| Sales Channel | Revenue Share |
| ------------- | ------------: |
| **Retail**    |        35.52% |
| **Wholesale** |        34.42% |
| **Online**    |        30.06% |

**Retail** contributes the largest share of revenue, followed closely by Wholesale and Online channels.

The relatively balanced contribution across the three channels indicates a diversified sales-channel mix.

This analysis can support:

* Channel-specific marketing
* Retail and wholesale strategy
* Online sales expansion
* Promotional planning
* Channel performance comparison

### Production vs Quantity Sold

The dashboard compares **Total Production** with **Quantity Sold** to understand the relationship between production volume and customer demand.

The overall figures are:

* **Total Production:** 2.17M
* **Quantity Sold:** 1.07M
* **Current Stock:** 1.09M

This analysis helps identify:

* Products with excess production
* High-demand products
* Inventory accumulation
* Production planning requirements
* Potential wastage

This is particularly important for dairy products due to their limited shelf life.

### Inventory Analysis

The dashboard tracks approximately **1.09M units of current stock** and provides visibility into inventory levels.

The dataset also contains inventory-related attributes such as:

* Minimum Stock Threshold
* Reorder Quantity
* Shelf Life
* Storage Condition
* Production Date
* Expiration Date

These attributes provide opportunities for developing more advanced inventory monitoring and replenishment strategies.

Inventory analysis can help with:

* Preventing stockouts
* Identifying overstocked products
* Optimizing reorder quantities
* Reducing product wastage
* Improving warehouse planning

### Brand Performance

The dashboard enables revenue analysis across different dairy brands.

The leading brands by revenue include:

| Brand            | Approx. Revenue |
| ---------------- | --------------: |
| **Amul**         |         ₹14.61M |
| **Mother Dairy** |         ₹13.77M |
| **Raj**          |          ₹9.56M |
| **Sudha**        |          ₹8.37M |

**Amul** and **Mother Dairy** are among the strongest revenue contributors in the analyzed dataset.

Brand-level analysis helps evaluate brand contribution, product distribution, and opportunities for improving portfolio performance.

### Geographic Analysis

The dataset contains business information across multiple locations in India, including:

* Telangana
* Uttar Pradesh
* Tamil Nadu
* Maharashtra
* Karnataka
* Bihar
* West Bengal
* Madhya Pradesh
* Chandigarh
* Delhi
* Gujarat
* Kerala
* Jharkhand
* Rajasthan
* Haryana

The analysis indicates that **Chandigarh and Delhi** are among the stronger revenue-generating locations in the dataset.

Geographic analysis can support:

* Regional marketing
* Distribution planning
* Supply-chain optimization
* Warehouse planning
* Market expansion

---

## Data Preparation & Modeling

### Power Query

**Power Query** was used for data preparation and transformation, including:

* Importing source data
* Cleaning and transforming datasets
* Handling data inconsistencies
* Preparing fields for analysis
* Structuring data for reporting

### Power Pivot

**Power Pivot** was used to create the analytical data model and establish the required relationships for reporting and analysis.

The model supports analysis across:

* Products
* Brands
* Locations
* Dates
* Sales
* Production
* Inventory
* Sales Channels

### DAX Measures

Custom **DAX measures** were created to calculate key business metrics, including:

* Total Revenue
* Total Quantity Sold
* Total Production
* Total Stock
* Average Selling Price
* Product Count
* Revenue-based calculations
* Time-based revenue analysis

These measures allow dashboard visuals and KPIs to dynamically update when users interact with filters.

---

## Interactive Features

The dashboard includes interactive controls that allow users to perform dynamic business analysis.

### Slicers

The dashboard includes slicers such as:

* **Year**
* **Product Name**
* **Location**
* **Brand**

These slicers allow users to filter the dashboard and analyze specific products, brands, locations, or time periods.

### Interactive Visualizations

Users can interact with dashboard visuals to compare:

* Revenue performance
* Product performance
* Brand contribution
* Geographic performance
* Sales-channel contribution
* Production and sales
* Inventory levels

These interactive features enable users to move from a high-level business overview to detailed analysis without modifying the underlying data.

---

## Key Business Insights

* Generated approximately **₹58.73M in total revenue**.
* Approximately **1.07M units** of products were sold.
* Total production was approximately **2.17M units**.
* Current stock stands at approximately **1.09M units**.
* **Curd** is the highest revenue-generating product at approximately **₹6.74M**.
* **Retail** is the largest sales channel, contributing approximately **35.52%** of revenue.
* Wholesale and Online channels also contribute significantly to overall revenue.
* **Amul and Mother Dairy** are among the strongest revenue-generating brands.
* **Chandigarh and Delhi** are among the stronger revenue-generating locations.
* The difference between production and quantity sold highlights the importance of effective inventory management.
* Historical data from **2019–2022** enables analysis of long-term revenue trends and seasonal patterns.
* Shelf life, expiration dates, stock thresholds, and reorder quantities provide opportunities for advanced inventory optimization.

---

## Business Recommendations

Based on the analysis, the following strategies can be considered:

1. Align production more closely with historical demand to reduce excess inventory.
2. Prioritize high-performing products such as **Curd, Butter, Lassi, Milk, and Paneer**.
3. Strengthen Retail and Wholesale channels while identifying opportunities for Online sales growth.
4. Use minimum stock thresholds and reorder quantities to improve inventory planning.
5. Incorporate shelf-life and expiration-date information to reduce potential dairy wastage.
6. Optimize distribution and marketing efforts toward high-performing regions.
7. Monitor brand-level performance to identify growth and improvement opportunities.
8. Use historical revenue trends to support future demand forecasting and production planning.

---

## Skills & Technologies

| Area                    | Tools / Techniques                          |
| ----------------------- | ------------------------------------------- |
| **Data Visualization**  | Power BI                                    |
| **Data Transformation** | Power Query                                 |
| **Data Modeling**       | Power Pivot                                 |
| **Calculations**        | DAX Measures                                |
| **Data Analysis**       | Sales, Production & Inventory Analytics     |
| **Interactivity**       | Slicers, Interactive Visuals                |
| **Reporting**           | Interactive Business Intelligence Dashboard |

---

## Project Outcome

This project demonstrates an end-to-end **Business Intelligence and Data Analytics workflow**, transforming raw dairy business data into an interactive dashboard that provides meaningful business insights.

Through this project, I gained practical experience in:

* Data Cleaning & Transformation
* Data Modeling
* DAX
* KPI Development
* Data Visualization
* Business Intelligence
* Interactive Dashboard Development
* Sales Performance Analysis
* Production Analysis
* Inventory Analysis
* Business-oriented Data Analysis

The project demonstrates how **Power BI can be used to transform raw business data into actionable insights that support data-driven decision-making across sales, production, inventory, and distribution**.
