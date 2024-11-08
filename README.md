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

**Files**: See `https://github.com/Tibson-spec/Sample-Superstore-Dataset-Project/tree/main/Sample%20Superstore%20Project` folder for cleaned Excel files.

## SQL Analysis
- **Date Dimension Table**: Populated to support time-series analysis.
- **Relationships**: Linked `Order Details` with `Products` and `Customers`.
- **Cost Field**: Added to enable margin calculations.
  
**Key Queries**:
1. **Sales Trends**: Query to aggregate sales by month, quarter, and year.
2. **Profit Margins**: Calculation of profit by product category.
3. **Customer Segmentation**: Grouped customer behavior by region and product category.

**SQL Scripts**: Located in the `SQL` folder.

## Power BI Visualization
Built interactive dashboards to showcase trends and insights:
- **Sales Trends**: Monthly and quarterly trends.
- **Profit Margins**: Analysis by category.
- **Customer Segmentation**: Insights by region.

**Power BI File**: `.pbix` file is in the `Visualizations` folder.

## Insights and Recommendations

1. **Seasonal Promotions**  
   - Insight: Q4 sales peak; Q2 needs discounts to maintain volume.
  
2. **Profit Optimization**  
   - Insight: Improve margins on low-profit items by renegotiating or adjusting prices.
  
3. **Targeted Marketing**  
   - Insight: Regional marketing can boost customer engagement.

## How to Use this Repository
1. **Data Preparation**: Review Excel files in `Data` for the initial datasets.
2. **SQL Analysis**: Check SQL scripts in `SQL` for all analysis steps.
3. **Power BI Dashboard**: Open `.pbix` in `Visualizations` to explore interactive charts.

---

### Conclusion
This project demonstrates e-commerce data analysis with a focus on SQL and Power BI for actionable insights. By cleaning data in Excel, modeling and querying in SQL, and creating visuals in Power BI, this project showcases a well-rounded approach to data analysis for business decision-making.

--- 

This layout will make your portfolio page engaging and user-friendly, while the GitHub README serves as a technical resource for in-depth exploration of your methods. Together, they will show both the business impact and the technical depth of your work.
