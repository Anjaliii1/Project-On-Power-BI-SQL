# Project-On-Power-BI-SQL
# Pizza Sales Report

Pizza sales refer to the sale and revenue generated from selling pizzas in various formats. These sales can be influenced by factors like menu variety, best time when orders are most, promotions, customer preferences, and seasonal trends. Analyzing pizza sales helps businesses optimize operations, improve marketing strategies, and enhance customer satisfaction.

# Domain: Pizza Sales                                   
### Function: Sale

### Dashboard Link : 

## Problem Statement

* KPI'S REQUIREMENT

We need to analyze key indicators for our pizza sales data to gain insights into our business
performance. Specifically, we want to calculate the following metrics:

    1. Total Revenue: The sum of the total price of all pizza orders.
    2. Average Order Value: The average amount spent per order, calculated by dividing the total revenue by the total number of orders.
    3. Total Pizzas Sold: The sum of the quantities of all pizzas sold.
    4. Total Orders: The total number of orders placed.
    5. Average Pizzas Per Order: The average number of pizzas sold per order, calculated bythe total number of pizzas sold by the total number of orders.

* CHARTS REQUIREMENT 

We would like to visualize various aspects of our pizza sales data to gain insights and understand keytrends. We have identified the following requirements for creating charts:

    1.Daily Trend for Total Orders:Create a bar chart that displays the daily trend of total orders over a specific time period. This chart will help us identify any patterns or fluctuations in order volumes on a daily basis.
    2.Monthly Trend for Total Orders: Create a line chart that illustrates the hourly trend of total orders throughout the day. This chart will allow us to identify peak hours or periods of high order activity.
    3.Percentage of Sales by Pizza Category : Create a pie chart that shows the distribution of sales across different pizza categories. This chart willprovide insights into the popularity of various pizza categories and their contribution to overall sales.
    4.Percentage of Sales by Pizza Size : Generate a pie chart that represents the percentage of sales attributed to different pizza sizes. This chart will help us understand customer preferences for pizza sizes and their impact on sales.
    5.Total Pizzas Sold by Pizza Category : Create a funnel chart that presents the total number of pizzas sold for each pizza category. This chart will allow us to compare the sales performance of different pizza categories.
    6.Top 5 Best Sellers by Revenue, Total Quantity and Total Orders : Create a bar chart highlighting the top 5 best-selling pizzas based on the Revenue, Total Quantity, Total Orders. This chart will help us identify the most popular pizza options. 
    7. Bottom 5 Best Sellers by Revenue, Total Quantity and Total Orders : Create a bar chart showcasing the bottom 5 worst-selling pizzas based on the Revenue, Total Quantity,Total Orders. This chart will enable us to identify underperforming or less popular pizza options.

# Software Used :  

    * Excel
    * My SQL WORKBENCH
    * Power BI


### Steps followed 



-----------------------------> IMPORT THE DATA INTO MY SQL WORKBENCH THEN POWER BI-------------------------------------->


1. Create a DataBase in mysql and store all the csv files related to pizza sales.

2. After creating database, writing the queries and problem Statement given us by our client with use of that particular Statement we will firing some queries.

3. Creating the report of all the queries we run in my sql with the screenshot of output.

4. Doing all the quries , we connect the mysql with power bi for visualization, if we do not have mysql directly import the .csv file to power bi.

5. Now, doing sme Data Cleaning process in power Query tool then Data Processing and use some DAX
functionalities in power bi and gate some custom colume, conditional colume accoding to the problem statments. 

6. Apply all step the last step is to create the Data visualization on power bi in which we are bilding some charts.

-------- >>  MYSQL Query steps for tables:  << --------

        * All the queries is in file format with the output.


        
 DAX measures (Key measure):

            1. Average Order Value = [Total Revenue]/[Total Orders]
            2. Average Pizza Per Order = [Total Pizza Sold]/ [Total Orders]
            3. Total Orders = DISTINCTCOUNT(pizza_sales[order_id])
            4. Total Pizza Sold = SUM(pizza_sales[quantity])
            5. Total Revenue = SUM(pizza_sales[total_price])
           

---------- >>Following Charts on the dashboard;

        * Percentage of sales by pizza Category and Size.
        * Trend by Key Metrics - Revenue, Total orders, total Sold pizza, Avg pizza per    
           orders, Avg order value.
        * Total pizza sold abay pizza Category.
        * Daily and Monthly Trend for order pizza.
        * Sales performance
        * Best and worst pizza by Revenue, Quantity, Total order.
        * Best and Worst Sellers.


---------- >>Key Insights

        * Days rders are highest On Weekends, Friday/Saturday Evening!!
        * Monthly There are Maximum Orders from Month of July and January!!
        * Category Classic Category Contributes  to Maximum Sales & Total Orders!!
        * Size Larger Size Pizza Contributes to Maximum Sales!!
        * REVENUE The Chai Chicken Pizza Contributes the maximum Revenue!!
        * QUANTITY The Classic Deluxe Pizza Contributes to Maximum Total Quantity!! 
        * TOTAL ORDERS The Classic Deluxe Pizza Contributes to Maximum Total Orders!! 
        * REVENUE The Brie Carre Pizza Contributes Minimum Revenue!!
        * QUANTITY The Brie Carre Pizza Contributes Minimum Total Quantity!!
        * TOTAL ORDERS The Brie Carre Pizza Contributes Minimum Total orders!!

snap of DashBoard :
![pizzadashboard](https://github.com/user-attachments/assets/23aceaf8-30a5-4044-8174-9f548ad30e50)
![pizzadashboard 1](https://github.com/user-attachments/assets/939fbe01-d4af-49ba-aa26-18e90e17c48f)
