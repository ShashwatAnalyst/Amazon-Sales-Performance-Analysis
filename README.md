# Regional-Sales-Analysis--Tableau-Project

## About
This project focuses on analyzing regional sales data to identify high-performing regions, evaluate product performance, and understand customer purchasing behavior. The primary objective is to provide actionable insights through an **interactive Tableau dashboard**, enabling better decision-making for sales strategies and business growth.  

The dataset utilized in this project is a publicly available **dummy dataset sourced from Kaggle**. It simulates transactions across different regions, products, and customer segments, making it suitable for practicing data cleaning, exploratory analysis, and dashboard building.


## Purposes of the Project
The main goal of this project is to explore sales data across **products, customers, and regions** and present findings in an interactive way using Tableau.  
By analyzing revenue, profit, and customer behavior, this project helps uncover **patterns, trends, and opportunities** to optimize sales and profitability.


## About Data
This project’s data is sourced from Kaggle and contains sales transactions with attributes like product details, customer segments, revenue, and regional information.  

| Column        | Description                                       | Data Type        |
|---------------|---------------------------------------------------|------------------|
| Order ID      | Unique ID for each transaction                    | VARCHAR(20)      |
| Product       | Product sold (Product 1, Product 2, etc.)         | VARCHAR(50)      |
| Category      | Category of product                               | VARCHAR(50)      |
| Region        | Geographical region of the sale                   | VARCHAR(30)      |
| Customer      | Customer identifier                               | VARCHAR(50)      |
| Segment       | Customer segment (Retail, Corporate, etc.)        | VARCHAR(30)      |
| Quantity      | Number of units sold                              | INT              |
| Sales         | Total sales value                                 | DECIMAL(10,2)    |
| Profit        | Profit earned from the sale                       | DECIMAL(10,2)    |
| Order Date    | Date of transaction                               | DATE             |


## Analysis List

1. **Product Analysis**  
   > Analyze sales by product category, identify top-performing products, and highlight underperforming ones.  

2. **Sales Analysis**  
   > Understand sales patterns across different time periods and regions, evaluate revenue and profit contribution, and identify growth opportunities.  

3. **Customer & Regional Analysis**  
   > Study customer segments, purchasing trends, and profitability across regions to uncover behavioral insights.  


## Approach Used

***1. Data Wrangling***  
- Used **Pandas** for cleaning and integration.  
- Handled missing values, corrected data types, and standardized categories.  
- Ensured data was properly structured for Tableau import.  

***2. Exploratory Data Analysis (EDA)***  
- Conducted **trend analysis** using Matplotlib & Seaborn.  
- Plotted product-level, customer-level, and region-level distributions.  
- Identified key revenue drivers and anomalies.  

***3. Dashboard Creation (Tableau)***  
Designed an interactive dashboard with the following features:  
- **Donut expansion on hover** → Revenue → Profit Margin  
- **Regional filters** with parameter-driven highlights  
- **Profit vs. Revenue segmentation** in pie charts  
- **Map visualization** with circle size = Revenue and color = Profit  
- **Custom tooltips & hover-expansion** for deeper insights  


## Business Questions to Answer

### Product Analysis
1. Which product categories generate the highest revenue?  
2. What are the top-performing products?  
3. Which products yield the highest profit margins?  
4. Are there products underperforming compared to average sales?  

### Sales Analysis
1. What is the monthly sales trend?  
2. Which regions generate the highest sales and profits?  
3. What is the profit-to-revenue ratio across regions?  
4. Which segment contributes the most to overall sales?  

### Customer & Regional Analysis
1. Which customer segments generate the most revenue?  
2. Which region contributes the most to sales vs. profit?  
3. What is the sales distribution by customer type?  
4. Which region has the highest average profit margin?  


## Insights from Dashboard
- Identified top-performing regions driving majority of sales.  
- Segmented **revenue vs. profit** to spot high-revenue but low-profit categories.  
- Highlighted customer segments with **higher-than-average contribution**.  
- Used map visualizations to detect geographical sales patterns.  



## Author
**Shashwat Singh**  
📈 Data Analyst | BI Developer  
💼 [LinkedIn](#) | [Portfolio](#)  

