# Sales-Analysis-Project <a href="https://public.tableau.com/app/profile/shashwat.sungh/viz/BooK5_17555197042170/CustomerRegion?publish=yes" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/mrankitgupta/mrankitgupta/a768d6bf0a001f03327578ae12f8867e4056cbaf/tableau-software.svg" alt="tableau" width="55" height="40"/><a href="notebook/Regional Sales Analysis.ipynb" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="45" height="50"/><a href="https://www.notion.so/Sales-Analysis-Project-247123ae0dc780ee8c8ffa4e5353f193" target="_blank" rel="noreferrer"><img src="" alt="notion" width="55" height="40"/><br /><p align="center"><a href="https://github.com/ivankahl/drawio-notion-embed"> <img src="images/Drawio_Notion.png" alt="Logo" width="55" height="40">
  </a>
</a>

</a>


## About
This project focuses on analyzing sales data to identify high-performing regions, evaluate product performance, and understand customer purchasing behavior. The primary objective is to provide actionable insights through an **interactive Tableau dashboard**, enabling better decision-making for sales strategies and business growth.  

The dataset utilized in this project is a publicly available **dummy dataset sourced from Kaggle**. It simulates transactions across different regions, products, and customer segments, making it suitable for practicing data cleaning, exploratory analysis, and dashboard building.


## Purposes of the Project
The main goal of this project is to explore sales data across **products, customers, and regions** and present findings in an interactive way using Tableau.  
By analyzing revenue, profit, and customer behavior, this project helps uncover **patterns, trends, and opportunities** to optimize sales and profitability.


## About Data
This project’s data is sourced from Kaggle and contains sales transactions with attributes like product details, customer segments, revenue, and regional information.  

<img src= "https://github.com/ShashwatAnalyst/Regional-Sales-Analysis/blob/main/docs/ER_Diagram_Screenshot.png?raw=true">

## Analysis List

  
1. **Sales Analysis**  
   > Understand sales patterns across different time periods and regions, evaluate revenue and profit contribution, and identify growth opportunities.
2. **Product Analysis**  
   > Analyze sales by product category, identify top-performing products, and highlight underperforming ones.  

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

## Important Links

- [View Live Dashboard](https://public.tableau.com/app/profile/shashwat.sungh/viz/BooK5_17555197042170/CustomerRegion?publish=yes)  
- [View Notion Project Template](https://www.notion.so/Sales-Analysis-Project-247123ae0dc780ee8c8ffa4e5353f193)
- [Open Main Jupyter Notebook](notebook)

## Project Structure
```
├── data
│ ├── processed
│ │ ├── file.csv
│ │ └── final.csv
│ └── raw
│ └── Sales Dataset.xlsx
│
├── docs
│ ├── ER_Diagram.drawio
│ ├── ER_Diagram_Screenshot.png
│ ├── Total_Sales_by_State.png
│ └── notebook
│ └── Sales Analysis.ipynb
│
├── dashboard
│ └── Sales_Dashboard.twbx # Tableau dashboard file
│
└── README.md
```
## Author
**Shashwat Singh**  
Passionate about **Data Analytics, Visualization, and Storytelling with Data**.<br>
| 💼 [LinkedIn](https://www.linkedin.com/in/shashwat-singh-bb2730357/) | 👤 [Portfolio](https://www.shashwatanalyst.online/)  

