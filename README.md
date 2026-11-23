# Supply Chain & Inventory Optimization Analytics

## Project Overview

I worked on this project to understand how data analytics can help businesses monitor sales, manage inventory, improve order fulfillment, and evaluate supplier performance.

I used Excel and Power Query for data preparation, Power BI for building the data model and interactive reports, and DAX for calculating business KPIs.

The goal was to bring different supply chain activities together into one reporting solution and make the results easier to explore.

## Tools and Technologies

- Microsoft Excel — working with and reviewing the source datasets
- Power Query — cleaning, transforming, and preparing data
- Power BI Desktop — data modeling, interactive dashboards, and visualization
- DAX — creating calculated measures and performance indicators

## Dataset Information

This project uses six related datasets containing **16,560 records** in total.

| Dataset | Records |
|---|---:|
| Products | 500 |
| Suppliers | 50 |
| Warehouses | 10 |
| Purchase Orders | 4,000 |
| Inventory | 2,000 |
| Sales Orders | 10,000 |
| **Total** | **16,560** |

**Data source:** The dataset is synthetic and was generated using ChatGPT/OpenAI on November 17, 2026, for educational and portfolio purposes. It does not represent actual company transactions.

## Data Preparation

I worked with the datasets in Excel and used Power Query to prepare them for analysis.

The preparation process included checking column data types, reviewing data quality, examining missing values, and validating important numerical fields.

After preparing the data, I loaded the six tables into Power BI and created relationships using ProductID, SupplierID, and WarehouseID.

## Data Modeling and DAX

I created a relational data model with seven one-to-many relationships.

I also developed DAX measures to analyze:

- Sales revenue and order volume
- Ordered, fulfilled, and unfulfilled quantities
- Order fill rate
- Inventory value and available stock
- Purchase order quantities and procurement spending
- On-time and delayed supplier deliveries
- Average delivery delay
- Stock availability

Some of the DAX functions I used include `SUM`, `SUMX`, `COUNTROWS`, `DIVIDE`, `CALCULATE`, `FILTER`, `RELATED`, `AVERAGEX`, and `DATEDIFF`.

## Power BI Reports

### 1. Executive Dashboard

An overview of key supply chain performance indicators, with navigation to the detailed analysis pages.

### 2. Sales Performance Analysis

Analyzes revenue trends, product categories, warehouse performance, and top-selling products.

### 3. Order Fulfillment Analysis

Compares ordered and fulfilled quantities, measures fulfillment rates, and highlights unfulfilled demand.

### 4. Inventory Optimization Analysis

Examines stock levels, available inventory, inventory value, and replenishment-related indicators.

### 5. Supplier & Procurement Analysis

Tracks procurement spending, purchase orders, supplier delivery performance, and delivery delays.

## Key Observations

In the overall dataset, the order fill rate was approximately 91.26%, while the supplier on-time delivery rate was approximately 29.15%.

These results highlight why it is useful to analyze customer order fulfillment and supplier delivery reliability separately.

The dashboard also makes it possible to explore revenue, inventory, and procurement metrics through interactive visuals and filters.

Because the dataset is synthetic, these observations demonstrate analytical techniques rather than verified performance at a real business.

## What I Learned

This project helped me gain practical experience in preparing related datasets, building a Power BI data model, writing DAX measures, and presenting business KPIs.

I also learned the importance of validating calculations and making dashboards easy to navigate and understand.

## Project Files

- **PowerBI:** Power BI report file
- **Dataset:** Source datasets
- **Screenshots:** Dashboard and report images
- **Documentation:** KPI calculations and interview preparation notes
- **DAX:** DAX measures and explanations, where provided

## Future Improvements

I would like to extend this project with more detailed inventory forecasting, supplier scorecards, and automated refreshes.

---

**Project type:** Data Analytics Portfolio Project  
**Tools:** Excel | Power Query | Power BI | DAX  
**Data:** Synthetic, generated for learning and demonstration
