# Sample-Superstore-Dataset-Project
## E-commerce Sales Analysis Project

# Project Summary
An analysis of e-commerce sales data using SQL, Power BI, and Excel, focusing on uncovering sales trends, profitability insights, and customer behavior. Key findings support strategic recommendations for promotions, inventory planning, and cost control.

## Table of Contents
•	Project Objectives

•	Datasets

•	Technologies

•	Data Preparation in Excel

•	SQL Analysis

•	Power BI Visualization

•	Insights and Recommendations

•	How to Use this Repository

---

## Project Objectives
- **Identify Sales Trends**: Track monthly, quarterly, and yearly patterns for inventory and marketing decisions.
- **Profitability Analysis**: Calculate profit margins by category and region for cost-control insights.
- **Customer Segmentation**: Examine regional customer behaviors to inform targeted marketing.

## Datasets
- **Order Details**: Includes order date, sales, ship mode, ship date, Quantity, Discount and customer/product IDs.
- **Products**: Contains product category, Product_Name, Sub_category information.
- **Customers**: Provides demographic information and segmentation.
- **Region**: Provides information on location, State, City_id and City

## Technologies
- **SQL Server**: Data modeling and queries.
- **Power BI**: Dashboard visualizations.
- **Excel**: Data cleaning and normalization.

## Data Preparation in Excel
1. **Cleaned Data**:
   - Removed duplicates, standardized columns, and handled missing values.
2. **Normalization**:
   - Split data into distinct tables for Orders, Products, Region and Customers.

**Files**: Click 👉[here](https://docs.google.com/spreadsheets/d/1zhJcE2nSJrCERH4MOQ4pmXq_e6hNHVt3/edit?usp=sharing&ouid=114563417088593971734&rtpof=true&sd=true)👈 for cleaned Excel files.

## SQL Analysis
- **Date Dimension Table**: Populated to support time-series analysis.
- **Relationships**: Linked `Order Details` with `Products`, `Region`and `Customers`.
- **Cost Field**: Added to enable margin calculations.
  
**Key Queries**:
1. **Sales Trends**: Query to aggregate sales by month, quarter, and year.
2. **Profit Margins**: Calculation of profit by product category, profit by region and customer segments,
3. **Customer Segmentation**: Determined sales by each customer, Average Order Value by Customer Segment, how often customers make repeat purchases and customer segments with highest purchase frequency

**SQL Scripts**: Click 👉[here](https://drive.google.com/file/d/1uIO7j8wKBYpNeZq6XTf_AGe7_B3NbxvM/view?usp=sharing)👈.

## Power BI Visualization
Built interactive dashboards to showcase trends and insights:
- **Sales Trends**: Monthly and quarterly trends.
- **Profit Margins**: Analysis by category, Profit Performance by region, Profits by Sub-category.
- **Customer Segmentation**: Insights by region, customer segment sales performance, top 10 best performing customers,customer segment with highest purchase frequency and average order by customer segment.

**Power BI File**: `.pbix` file Download 👉[here](https://drive.google.com/file/d/1TmBDHX8B5GFZKp-y7unGjYVibrXIVyQn/view?usp=sharing)👈.

## Insights and Recommendations

1. **Seasonal Promotions**  
   - Insight: Q4 sales peak; Q2 needs discounts to maintain volume.
  
2. **Profit Optimization**  
   - Insight: Improve margins on low-profit items by renegotiating or adjusting prices.
  
3. **Targeted Marketing**  
   - Insight: Regional marketing and campaigns can boost customer engagement.

## How to Use this Repository
1. **Data Preparation**: Review Excel files in `Sample Superstore Dataset Project` for the initial datasets.
2. **SQL Analysis**: Check SQL scripts in `Sample Superstore Dataset Project` for all analysis steps.
3. **Power BI Dashboard**: Open `.pbix` in `Sample Superstore Dataset Project` to explore interactive charts.

---

### Conclusion
This project demonstrates e-commerce data analysis with a focus on SQL and Power BI for actionable insights. By cleaning data in Excel, modeling and querying in SQL, and creating visuals in Power BI, this project showcases a well-rounded approach to data analysis for business decision-making.

--- 
