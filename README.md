# Walmart-sales-analysis
Using python and visualization tools to perform a simple analysis on a Walmart CSV


## Analysis description
- This analysis aims to explore the Walmart Sales data to understand top performing branches and products, sales trend of different products, customer behavior. The aims is to study how sales strategies can be improved and optimized. The dataset was obtained from the Kaggle Walmart Sales Forecasting Competition.

- "In this recruiting competition, job-seekers are provided with historical sales data for 45 Walmart stores located in different regions. Each store contains many departments, and participants must project the sales for each department in each store. To add to the challenge, selected holiday markdown events are included in the dataset. These markdowns are known to affect sales, but it is challenging to predict which departments are affected and the extent of the impact." source

- Purposes Of The Project
The major aim of this project is to gain insight into the sales data of Walmart to understand the different factors that affect sales of the different branches.

### About Data
- This dataset contains sales transactions from a three different branches of Walmart, respectively located in Mandalay, Yangon and Naypyitaw. The data contains 17 columns and 1000 rows:

**Column include:**

invoice_id		
branch	
city	
customer_type	
gender	
product_line	
unit_price		
quantity	 
VAT	
total	
date	
time	
payment_method	
cogs	
gross_margin_percentage	
gross_income	
rating	


**Product Analysis**
Conduct analysis on the data to understand the different product lines, the products lines performing best and the product lines that need to be improved.

**Sales Analysis**
This analysis aims to answer the question of the sales trends of product. The result of this can help use measure the effectiveness of each sales strategy the business applies and what modifications are needed to gain more sales.

**Customer Analysis**
This analysis aims to uncover the different customers segments, purchase trends and the profitability of each customer segment.

- Create a time_of_day column: to give insight of sales in the Morning, Afternoon and Evening. This will help answer the question on which part of the day most sales are made.
- Create a day_name : that contains the extracted days of the week on which the given transaction took place (Mon, Tue, Wed, Thur, Fri). This will help answer the question on which week of the day each branch is busiest.
- Create a new column named month_name: that contains the extracted months of the year on which the given transaction took place (Jan, Feb, Mar). Help determine which month of the year has the most sales and profit.

