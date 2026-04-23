  Blinkit Sales & Customer Analytics  Report

1. Project Overview

This project focuses on analyzing Blinkit's grocery sales data using Power BI.
The objective is to evaluate sales performance, customer satisfaction, and outlet distribution to support better business decision‑making. An interactive dashboard was developed to provide stakeholders with a clear view of product performance, outlet contribution, and customer ratings.

2. Project Objective

The main objective of this project is to analyze Blinkit's sales data and generate actionable insights using Power BI visualizations and key performance indicators (KPIs).
The dashboard helps stakeholders understand which products, outlet types, and locations contribute the most to overall sales and customer satisfaction.

3. Business Requirements

The business wanted to answer the following questions:
●	What is the total sales generated across all outlets?
●	Which product categories generate the highest revenue?
●	Which outlet locations perform the best?
●	How satisfied are customers based on ratings?
●	What is the distribution of sales across outlet sizes and types?

4. Data Source

The dataset used in this project is the Blinkit Grocery Dataset containing transactional and outlet information.
Key fields in the dataset include:
●	Item Identifier
●	Item Type
●	Item Fat Content
●	Item Weight
●	Item Visibility
●	Outlet Identifier
●	Outlet Establishment Year
●	Outlet Location Type
●	Outlet Size
●	Outlet Type
●	Sales
●	Rating

5. Data Preparation and Cleaning

Data cleaning was performed in Power Query before building the data model.
The following steps were performed:
●	Standardized Item Fat Content values (Low Fat / Regular)
●	Checked and corrected data types for numeric and categorical fields
●	Removed duplicate records
●	Trimmed unnecessary spaces in text fields
●	Verified missing values and ensured data consistency

6. Data Modeling

We have the required data presented in only one table which is not required to make any changes or relationships.
BlinkIT Grocery Data – contains Sales, Rating, and Item Visibility metrics, Item Identifier, Item Type, Fat Content, and Item Weight,Outlet Identifier, Outlet Type, Outlet Size, Location Type, and Establishment Year

7. Key DAX Measures

The following measures were created using DAX:
●	Total Sales = SUM(Sales)
●	Average Sales = AVERAGE(Sales)
●	Number of Items = COUNT(Item Identifier)
●	Average Rating = AVERAGE(Rating)
These measures were used to create KPI cards and visualizations across the dashboard.

8. Dashboard Development

The Power BI dashboard was designed to provide a comprehensive view of Blinkit's operations.
Main sections include:
●	KPI Cards showing Total Sales, Average Sales, Number of Items Sold, and Average Customer Rating
●	Sales distribution by Item Type
●	Fat Content analysis of products
●	Outlet size distribution
●	Outlet location performance (Tier 1, Tier 2, Tier 3)
●	Sales trends based on outlet establishment year
●	Outlet type performance table
●	A filter panel was also created to allow users to filter by outlet location, outlet size, outlet type, and metrics.

9. Key Insights

The analysis generated several business insights:
●	Tier 3 outlets generated the highest sales compared to Tier 1 and Tier 2.
●	Low Fat products contributed more to overall sales than Regular products.
●	Supermarket Type 1 outlets generated the highest revenue among all outlet types.
●	Fruits and Snacks categories are among the top performing item types.
●	The overall average customer rating is around 3.9, indicating good customer satisfaction.

10. Conclusion

The Blinkit Sales Dashboard provides a 360‑degree view of product performance, outlet performance, and customer satisfaction.
The interactive report enables stakeholders to monitor business performance and make data‑driven decisions regarding inventory management, outlet expansion, and product strategy.

11.Screenshots
<img width="1366" height="768" alt="Index" src="https://github.com/user-attachments/assets/2f17749a-1889-471f-b2b2-eb60d3d844a3" />
<img width="1366" height="768" alt="Executive Overview" src="https://github.com/user-attachments/assets/4bb6ff97-e19d-4370-a5f3-fb9f672882ec" />



  
