# sql-indian-sales-project
SQL Data Analysis Project on Indian Sales Data using MySQL

# Indian Sales Data - SQL Portfolio Project

## About This Project
I built this project to practice and showcase my SQL skills.
I used 500 rows of Indian sales data and wrote 10 SQL queries
to answer real business questions that companies actually ask.

The data includes sales from 4 categories:
- Electronics (Mobiles, Laptops, Tablets)
- Furniture (Chairs, Tables, Sofas)
- Clothing (Shirts, Sarees, Kurtas)
- Food (Snacks, Beverages, Sweets)

Cities covered: Mumbai, Delhi, Bangalore, Chennai, Hyderabad,
Kolkata, Ahmedabad, Jaipur and more.

## Tools I Used
- MySQL Workbench to write and run queries
- SQL for all data analysis

## What Business Problems I Solved

Query 1 - Top Products
I found which products make the most revenue for the business.
SQL used: GROUP BY and ORDER BY

Query 2 - Regional Performance
I identified which regions in India are performing above
100k revenue and which regions need more focus.
SQL used: GROUP BY and HAVING

Query 3 - Customer Lifetime Value
I found the top 10 most valuable customers based on
how much they spent in total across all their orders.
SQL used: GROUP BY and MAX

Query 4 - Monthly Trends
I tracked whether the business is growing or declining
every month by comparing this month vs last month sales.
SQL used: LAG Window Function

Query 5 - Top Product Per Category
I found the single best selling product in each category
like Electronics, Furniture, Clothing and Food.
SQL used: ROW_NUMBER and CTE

Query 6 - City wise Sales Ranking
I ranked all Indian cities from highest to lowest sales
to find which city contributes most to the business.
SQL used: DENSE_RANK Window Function

Query 7 - Customer Segmentation
I grouped all customers into 4 segments based on how
often they buy and how much they spend.
Champion - Buys a lot and spends the most
Loyal - Regular buyers with good spending
Potential - Occasional buyers
New Customer - Just started buying
SQL used: CASE WHEN

Query 8 - Category Growth by Month
I compared month over month growth for each category
separately to see which category is growing the fastest.
SQL used: LAG with PARTITION BY

## Key Findings
- Electronics is the highest revenue category
- West region (Mumbai and Ahmedabad) leads all regions in sales
- Some Food products are making very low profit
- October and November show highest sales due to festive season

## What I Learned
- How to use GROUP BY and HAVING for business filtering
- How to use Window Functions like LAG, ROW_NUMBER, DENSE_RANK
- How to segment customers using CASE WHEN
- How to calculate running totals and month over month growth
- How to find business insights from raw data using SQL
