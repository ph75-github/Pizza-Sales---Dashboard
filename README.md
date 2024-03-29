
# Pizza Sales - Dashboard

### Dashboard Link : https://app.powerbi.com/groups/me/reports/1678e001-726c-4169-a9c0-c71934d4af9f/ReportSection?experience=power-bi

## Problem Statement

### KPI'S REQUIREMENT 

We need to analyze key indicators for the pizza sales data to gain insights into the business performance. Specifically, we need to calculate the following metrics:

##### 1. Total Revenue
##### 2. Average Order Value
##### 3. Total Pizzas Sold
##### 4. Total Orders
##### 5. Average Pizzas Per Order

### CHARTS REQUIREMENT

We need to visualize various aspects of the pizza sales data to gain insights and understand key trends. We need to identify the following requirements for creating charts:

#### 1. Daily Trend for Total Orders:

Create a bar chart that displays the daily trend of total orders over a specific time period. This chart will help identify any patterns or fluctuations in order volumes on a daily basis.

#### 2. Monthly Trend for Total Orders:
Create a line chart that illustrates the hourly trend of total orders throughout the day. This chart will allow us to identify peak hours or periods of high-order activity.

#### 3. Percentage of sales by Pizza Category:
Create a pie chart that shows the distribution of sales across different pizza categories. This chart will provide insights into the popularity of various pizza categories and their contribution to overall sales. 

#### 4. Percentage of sales by Pizza Size:
Generate a pie chart that represents the percentage of sales attributed to different pizza sizes. This chart will help us understand customer preferences for pizza sizes and their impact on sales.

#### 5. Total Pizzas sold by Pizza Category:
Create a funnel chart that presents the total number of pizzas sold for each pizza category. This chart will allow us to compare the sales performance of different pizza categories.

#### 6. Top 5 Best Sellers by Revenue, Total Quantity and Total Orders:
Create a bar chart highlighting the top 5 best-selling pizzas based on revenue, total quantity, and total orders. This chart will help us identify the most popular pizza options.

#### 7. Bottom 5 Sellers by Revenue, Total Quantity and Total Orders:
Create a bar chart showcasing the bottom 5 selling pizzas based on revenue, total quantity, and total orders. This chart will enable us to identify underperforming or less popular pizza options.

### Steps Followed
- Step 1: The csv file is imported into a SQL database. 
- Step 2: SQL queries are utilized to extract relevant information and derive insights from the dataset. 
- Step 3: Load the csv file in Power BI, calculate the necessary measures using DAX queries, and use Power BI as the visualization tool to create interactive and visually appealing reports. 

Note: This repository showcases the Pizza Sales Analysis project, which aims to analyze and visualize the sales data. The project utilizes a combination of SQL, and Power BI to perform exploratory analysis, and create interactive reports.

# Insights

A double-page dashboard was created on Power BI Desktop, and it was then published to Power BI Service.

The following inferences can be drawn from PostgreSQL :

### [1] Total revenue from sales

  - The total revenue generated by selling pizzas is $817.86K
  - SQL Query : <img width="271" alt="KPI_1 1" src="https://github.com/ph75-github/Pizza-Sales---Dashboard/assets/161227830/87034a22-d751-419f-a420-d36a791b5a82">
  - SQL output : <img width="148" alt="KPI_1 2" src="https://github.com/ph75-github/Pizza-Sales---Dashboard/assets/161227830/36cf0a40-c9c2-4ddd-a380-65cd09b22521">


           
### [2] Average order value

 - The average order value of pizzas is $38.31
 - SQL Query : <img width="441" alt="KPI_2 1" src="https://github.com/ph75-github/Pizza-Sales---Dashboard/assets/161227830/b97257e3-1ae7-4f7d-a76c-0b8271e48b95">
 - SQL output : <img width="148" alt="KPI_2 2" src="https://github.com/ph75-github/Pizza-Sales---Dashboard/assets/161227830/ebc30fe1-c454-4d94-8d95-a49c564cdc62">


  
  ### [3] Total Pizzas Sold 
  
 - Total pizzas sold : 49574
 - SQL Query : <img width="270" alt="KPI_3 1" src="https://github.com/ph75-github/Pizza-Sales---Dashboard/assets/161227830/54d7b1a3-56d6-42da-9e25-30bc05866819">
 - SQL output : <img width="148" alt="KPI_3 2" src="https://github.com/ph75-github/Pizza-Sales---Dashboard/assets/161227830/8ae2c429-3fa6-44bd-b3e6-3fa59595864f">


 ### [4] Total orders made
 - Total orders made : 21350
 - SQL Query : <img width="305" alt="KPI_4 1" src="https://github.com/ph75-github/Pizza-Sales---Dashboard/assets/161227830/6feb9728-2b29-442f-a8c2-fcecbcb19dd5">
 - SQL output : <img width="146" alt="KPI_4 2" src="https://github.com/ph75-github/Pizza-Sales---Dashboard/assets/161227830/6a640ee9-c9bf-4916-ad30-fbf6a60be338">


### [5] Average pizzas per order

- Average pizzas per order are 2.32
- SQL Query : <img width="303" alt="KPI_5 1" src="https://github.com/ph75-github/Pizza-Sales---Dashboard/assets/161227830/ddfefaef-39f6-4bca-af99-ffbd11e07f65">
- SQL output : <img width="147" alt="KPI_5 2" src="https://github.com/ph75-github/Pizza-Sales---Dashboard/assets/161227830/20c7909c-1d4e-42dc-8160-fd2f9cfcd531">

### [6] Daily trend of Total Orders
- The busiest day of the year is FRIDAY.
- SQL Query : <img width="393" alt="PS_1 1" src="https://github.com/ph75-github/Pizza-Sales---Dashboard/assets/161227830/0f9b31d6-6766-4903-a09c-ac69ee3d1795">
- SQL output : <img width="149" alt="PS_1 2" src="https://github.com/ph75-github/Pizza-Sales---Dashboard/assets/161227830/300b38c2-63f5-40cf-befd-870eaa4fcf31">

### [7] Monthly trend of Total Orders
- The busiest month of the year is JULY.
- SQL Query : <img width="416" alt="PS_2 1" src="https://github.com/ph75-github/Pizza-Sales---Dashboard/assets/161227830/dcc70cbd-3023-4738-a65e-8066610171e9">
- SQL output : <img width="151" alt="PS_2 2" src="https://github.com/ph75-github/Pizza-Sales---Dashboard/assets/161227830/57117a7c-c6fa-42dc-b6b7-a4ac0518a657">

### [8] Highest revenue by Pizza Category
- Classic pizza made the highest revenue of $220,053
- SQL Query : <img width="755" alt="PS_3 1" src="https://github.com/ph75-github/Pizza-Sales---Dashboard/assets/161227830/3e3da12a-8aa8-4c48-bcf4-c66e6bccba5b">
- SQL output : <img width="233" alt="PS_3 2" src="https://github.com/ph75-github/Pizza-Sales---Dashboard/assets/161227830/f9f9f4ec-88c3-4c49-8e1c-8c142b66777d">

### [9] Highest revenue by Size of the Pizza 
- Large size pizza made the highest revenue of $375,318
- SQL Query : <img width="744" alt="PS_4 1" src="https://github.com/ph75-github/Pizza-Sales---Dashboard/assets/161227830/1fb3001c-8816-435c-8672-9b1b2b657a89">
- SQL output : <img width="231" alt="PS_4 2" src="https://github.com/ph75-github/Pizza-Sales---Dashboard/assets/161227830/fec97afb-8c58-4b78-b695-951bc03b2274">

### [10] Highest and Lowest Pizza Sold by Pizza Category 
- Classic pizza is ordered the most, with total orders of 14,888.
- Chicken pizza had the fewest orders, with total orders of 11,050.
- SQL Query : <img width="320" alt="PS_5 1" src="https://github.com/ph75-github/Pizza-Sales---Dashboard/assets/161227830/de73c3de-45e9-4e88-85b9-3afd28f94c31">
- SQL output : <img width="155" alt="PS_5 2" src="https://github.com/ph75-github/Pizza-Sales---Dashboard/assets/161227830/709d0636-85fc-4bb3-b4de-4c8610bbc24b">

### [11] Top 5 Best Sellers by Revenue, Total Quantity, and Total Orders

#### 1. The Thai Chicken Pizza
#### 2. The Barbecue Chicken Pizza
#### 3. The California Chicken Pizza
#### 4. The Classic Deluxe Pizza
#### 5. The Spicy Italian Pizza

- SQL Query : <img width="608" alt="PS_6 1" src="https://github.com/ph75-github/Pizza-Sales---Dashboard/assets/161227830/81cf0144-b0cf-4544-97ef-aa0d728a378b">
- SQL output : <img width="262" alt="PS_6 2" src="https://github.com/ph75-github/Pizza-Sales---Dashboard/assets/161227830/efc6b902-b82f-4f31-b588-21eb8ca5cd58">

### [12] Bottom 5 Sellers by Revenue, Total Quantity, and Total Orders

#### 1. The Brie Carre Pizza
#### 2. The Green Garden Pizza
#### 3. The Spinach Supreme Pizza
#### 4. The Mediterranean Pizza
#### 5. The Spinach Pesto Pizza

- SQL Query : <img width="607" alt="PS_7 1" src="https://github.com/ph75-github/Pizza-Sales---Dashboard/assets/161227830/d1593925-85d5-40d5-9328-c603ef9cd332">
- SQL output : <img width="258" alt="PS_7 2" src="https://github.com/ph75-github/Pizza-Sales---Dashboard/assets/161227830/99e16a6d-9b9f-4a68-bbc0-0cff9b595696">


