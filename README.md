Super Store Sales Dashboard Using Power BI

The main objective of this dashboard is to analyse Super Store sales and profit performance across categories, regions, and customer segments. It highlights top contributors, tracks shipping trends, identifies high and low-performing markets and effect/impact of Discounts to support data-driven decisions. 

Tools and technologies:
1. Data Preparation
•	Imported the Super Store dataset into Power BI Desktop.
•	Cleaned the data by removing nulls, correcting data types, and renaming columns.
•	Created calculated columns and DAX measures (e.g., Profit Margin %, Sales Growth).
2. Data Modelling
•	Built relationships between tables for accurate analysis.
•	Normalized data where required to improve efficiency.
•	Defined key measures using DAX for KPIs like Sales, Profit, Orders, and Profit Margin vs Target.
3. Dashboard Design & Visualization
•	Added slicers (Region, Category, Year, Market) for interactivity.
•	Designed multiple visuals: bar charts, line charts, map, tree map, decomposition tree, and KPI cards.
•	Integrated navigation buttons for seamless movement between pages.
4. Techniques Applied
•	DAX Expressions – for advanced calculations and KPIs.
•	Conditional Formatting – to highlight active slicers and key insights.
•	Bookmarks & Navigation – for interactive page switching.

Data Source:

The dataset used for this dashboard is the Superstore Sales dataset, sourced from Kaggle. 
It contains over 51,000 orders, covering 4 years of sales data (2011–2014) across multiple markets, regions, and customer segments. The dataset provides rich information on order details, customers, products, categories, shipping modes, sales, profit, and discounts.

Key Questions:
1. Which segments/market and regions deliver the highest revenue and profitability, and which consistently underperform?
2. How have annual sales and profit trends evolved across different regions over the years?
3. Which product categories and sub-categories achieve the strongest profit margins, and which contribute to losses?
4. How does the discount percentage affect profitability, and is there a threshold where discounts lead to losses?
5. Who are the top 10 customers by revenue, and what is their overall profit impact?
6. How products or sub-categories vary on basis of profit?
7. What is the average shipping time for each shipping mode, and how does it influence order performance?
8. How Countries vary by revenue?

Walkthrough of Key Visuals:

Key KPIs (Top Right) Total number of customers: 51,000 Customers
Slicers (Top Centre) of Year, Region & Category
Profit by Category & Sub-category (Stacked column chart) stacked column chart ranks category & sub-categories like Copiers/Technology, Phones/Technology, Bookcases/Furniture by Profit of Superstore.
Sales by Segments & Regions (Treemap) treemap ranks segments & regions like Consumer/Central, Corporate/Central, Home Office/Central by Sales of Superstore.
Sales by Country (Filled map) Countries like Russia, Europe, Brazil by sales of Superstore.
Top 10 Customers by Revenue (Stacked column chart) stacked column chart ranks like Tom Ashbrook, Tamara Chand, Greg Tran by Revenue of Superstore.
Annual Sales & profit by Region (Line chart) it illustrates sales trends over time, enabling identification of seasonal patterns, growth trajectories, and fluctuations in Superstore performance across different periods.
Sales by Shipping time (Line chart) it shows sales distribution across different shipping modes (Same Day, First Class, Second Class, and Standard Class), helping to analyse how delivery time influences customer purchases and overall revenue contribution.
Markets & Regions by Highest/Lowest Revenue & Profitability (Decomposition tree) it compares revenue and profitability across different markets and regions, highlighting the highest and lowest performing geographies. It helps identify regions driving strong sales and profit, as well as those with low revenue or weak profitability that may require strategic attention.
Effects of discounts on Profitability (Scattered chart) scattered chart highlights how varying discount levels influence profitability, revealing that excessive discounts often erode profit, while controlled discounts can sustain both sales and margins.
Impact of Discount percentage on Profit margin (Stacked column chart) it shows how increasing discount percentages affect profit margins, showing that while small discounts may encourage sales with minimal impact, higher discounts significantly reduce overall profitability.

The purpose of this dashboard is to provide a comprehensive analysis of Super Store sales performance across different dimensions. It helps track overall sales, profit margins, and order volumes while comparing them against targets. The dashboard enables deeper insights into profitability by product categories, sub-categories, customer segments, and regions, highlighting top customers and their revenue contributions. It also evaluates shipping performance to understand delivery trends and their impact on sales. Additionally, the dashboard identifies high and low-performing markets and regions, effect/impact of discounts, empowering decision-makers to focus on growth opportunities and address areas of concern effectively.

[Dashboard Preview]
Dashboard : (https://github.com/tanaya838/Super-Store-Sales-Dashboard-Using-Power-BI/blob/main/Super%20Store%20Sales%20Dashboard.gif)

Dashboard Page 1 : (https://github.com/tanaya838/Super-Store-Sales-Dashboard-Using-Power-BI/blob/main/Page%201.gif)

Dashboard Page 2 : (https://github.com/tanaya838/Super-Store-Sales-Dashboard-Using-Power-BI/blob/main/Page%202.gif)
