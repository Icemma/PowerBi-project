## Mavin Toy Store Business Analysis

### Introduction 
This business intelligence analysis focuses on Maven Toy Store, a leading toy retail chain in 
Mexico. The dataset encompasses extensive sales and inventory data, including product details, 
store locations, daily sales transactions, and stock levels across multiple outlets. 

### Project Overview 
This analysis aims to uncover significant trends and patterns within Maven Toy Store data, support the company's expansion strategy, providing actionable insights for informed decision-making. 

 
### Objectives
The primary goal of this analysis is to generate actionable insights into Maven Toy Store's overall sales 
performance and profitability by evaluating: 
- Store location performance 
- Seasonal sales trends 
- Product profitability and sales effectiveness 
- Provide recommendations to optimize business strategies.

 
### Key Business Questions 
1. Which product categories yield the highest profits, and how do these trends vary across different store locations?
2. Are there identifiable seasonal sales patterns?
3. What is the company's current market reach in terms of store distribution and geographic presence?
4. What is the total inventory value, and how long can it sustain current sales levels?
5. Which stores perform best and worst in terms of revenue and profitability? 


### Tools and Methodologies 
Tool Used: Microsoft Power BI 

#### Techniques
1. Data Cleaning & Transformation using Power Query
2. Data Modeling to establish structured relationships between tables
3. DAX Implementation for advanced calculations and metrics
4. Data Visualization for interactive and insightful dashboards
5. Comprehensive Project Documentation for clear reporting of insights


### Data Processing 
#### Data Importation and Cleaning 
Importation Process: Data was ingested using Power BI’s Excel connector. 

#### Cleaning Steps: 
- Promoted headers for consistent column naming. 
- Converted ID columns from whole numbers to text (as they serve as unique identifiers rather than numerical values). 
- Added calculated fields for total product cost, total product price, and profit in the sales dataset. 
- Corrected data types to ensure consistency. 
- Trimmed redundant store names in the Stores Table for clarity. 
- Created a Dates Table using CALENDARAUTO() to facilitate temporal analysis, extracting year, quarter, month, and day attributes.


### Data Modeling 
Effective data modeling structures raw data into an analytical framework, allowing seamless 
relationship-building between tables. In this project, Power BI automatically identified table 
relationships, forming a star schema model: 
1. Fact Table: Sales Table, Inventory
2. Dimension Tables: Products, Stores, and Dates
