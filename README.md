# BLINKIT-POWERBI-PROJECT
## BLINKIT GROCERY DATA ANALYSIS USING POWER BI
### **FEATURES**
- DATA CLEANING
- DATA ANALYSIS
- DASHBOARD CREATION
- DATA VISUALIZATION
## PROJECT OVERVIEW
This project analyzes blinkits sales performance, customer satisfaction,  and outlet distribution using power bi .
## TOOLS USED
- DAX
- POWER QUIERY
- POWER BI
  ## KPI REQUIREMENTS
- total sales
- average sales
- number of items
- average rating
 ## DASHBOARD ANALYSIS
 ### 1. total sales by fat content
 analyzes the impact of fat content on total sales.
 ### 2. totalsales by item type
 Analyzes the performance of different item type
### 4.total sales by outlet establishment
Analyzes how outlet establishment affects sales.
 ### 5. Sales by Outlet Size
Analyzes the relationship between outlet size and sales.
### 6. Sales by Outlet Location
Analyzes sales distribution across different outlet locations.
### 7. All Metrics by Outlet Type
Compares Total Sales, Number of Items, Average Sales,
and Average Rating across outlet types.
## KEY KPIs
- total sales : $ 1.20M
- Average sales : $141
- Number of items : 8,523
- average rating : 3.9
## DAX Functions Used
### 1. Total Sales
Total Sales = SUM('BlinkIT Grocery Data (8)'[Sales])
###  2. average sales
Average Sales = AVERAGE('BlinkIT Grocery Data (8)'[Sales])
### 3. average rating
Avg Rating = AVERAGE('BlinkIT Grocery Data (8)'[Rating])
### number of items
NoOfItems = COUNTROWS('BlinkIT Grocery Data (8)')
