# Cafe-Espro-Sales-Analytics--Power-BI-
This project contains a Power BI dashboard for Café Espro, designed to provide insightful data analytics using KPI cards, various visualizations, and measures to track business performance. 

## Key Activities:
1.	Comprehending the dataset.   
2.	Performed data cleaning to ensure accuracy and consistency.
3.	Generated business questions to guide data-driven decision-making.
4.	Conducted data analysis using Power BI to uncover insights.
5.	Developed interactive dashboards in Power BI to visualize key findings effectively.

## Features
1. KPI Cards – Display key business metrics such as Total sales, store locations, product types, product categories, Maximum unit price, minimum unit price
2. Interactive Visuals – Various charts and graphs to analyze trends and patterns. sales, profit, and customer preferences.
3. Custom Measures – DAX-based calculations for deep insights into business performance.
4. Data-Driven Decision Making – Helps in monitoring key aspects for understanding Café trends.

## Dataset Overview
⭐ Excel file- Cafe Espro.xlsx 

⭐ The dataset used for this project includes transactional data with the following columns:
1.	transaction_id – Unique identifier for each transaction
2.	transaction_date – Date of transaction
3.	transaction_time – Time of transaction
4.	transaction_qty – Quantity of products purchased
5.	store_id – Unique store identifier
6.	store_location – Location of the store
7.	product_id – Unique product identifier
8.	unit_price – Price per unit of the product
9.	product_category – Category of the product
10.	product_type – Type of product
11.	product_detail – Additional product information

## Analysis in Power BI 
  
⭐ Add new columns
1.	Total amount of each transaction: Unit price*Transaction_qty
2.	Day_Interval: Before 12 noon as First half and remaining as second half
3.	Menu Type: For unit price<=10 ‘Classic’ otherwise ‘Gourmet’
 
⭐ Create KPI cards
1.	Total Number of transactions
2.	Total number of outlets
3.	Number of distinct product categories
4.	Number of distinct products
5.	Maximum unit price
6.	Minimum unit price 

⭐ Business Questions 
A. Product sales Analysis:
1.	What is the total sales of different outlets? 
2.	What is menu type distribution?
3.	What is product category distribution with product type?

B. Transaction Time Analysis:
1.	At what interval of day the products are sold the most?
  
C. Storewise Analysis:
1.	What is the product type distribution varied by store locations?
2.	List Max payment and Min payment done varying by stores
3.	What is the best seller product in each store?
4.	What is the least sold product in each store?

  
⭐ Table Visuals
  1.	Create a table for menu type with its MaxUnitP  and MinUnitP
  2.	Product Category with its MaxUnitP  and MinUnitP
  3.	Store id, Store locations with their total transactions 
__________________________________________________________________________________________________________________

⭐ Dashboard Overview
The Power BI dashboard consists of:
1. Product Sales Analysis: Total Sales, Product Category distribution, maximum unit price and minimum unit price of products
2. Store location based Analysis: Sales of the different store locations, the best seller and least sold products
3. Transaction Time Analysis: Analysis according to Day Interval as first half or second half 

## Tech Stack
1. Power BI for data visualization
2. DAX (Data Analysis Expressions) for measures
3. Excel/CSV Data Sources

## Dashboard
Page 1
![image](https://github.com/user-attachments/assets/04fb56c6-8a0a-4f3c-8242-daed13d29444)

Page 2
![image](https://github.com/user-attachments/assets/15935f85-f812-423e-ac61-0a1a5f4a2cff)



 

















