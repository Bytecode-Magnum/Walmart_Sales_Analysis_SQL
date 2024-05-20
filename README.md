SQL_Walmart_Sales_Analysis
The primary objective of this project is to gain insights into Walmart's Sales data in order to understand the various factors influencing the sales of its different branches.

Data Normalization:
Build a database
Create table and insert the data.
Select columns with null values in them - There are no null values in our database as in creating the table we set NOT NULL for each field, hence null values are filtered out.
Add a new column named "time_of_day" to give insight of sales in the Morning, Afternoon and Evening. This will help answer the question on which part of the day most sales are made.
Add a new column named "day_name" that contains the extracted days of the week on which the given transaction took place (Mon, Tue, Wed, Thur, Fri). This will help answer the question on which week of the day each branch is busiest.
Add a new column named "month_name" that contains the extracted months of the year on which the given transaction took place (Jan, Feb, Mar..). This helps to determine which month of the year has the most sales and profit.
Data Analysis:
Product
How many unique product lines does the data have?
What is the most common payment method?
Which is the most selling product line?
What is the total revenue by month?
Which month had the largest COGS?
Which product line had the largest revenue?
City with the largest revenue?
Which product line had the largest VAT?
Fetch each product line and add a column to those product line showing "Good", "Bad". Good if its greater than average sales
Which branch sold more products than average product sold?
Which is the most common product line by gender?
What is the average rating of each product line?
Customer
How many unique customer types does the data have?
How many unique payment methods does the data have?
Which is the most common customer type?
Which customer type buys the most?
What is the gender of most of the customers?
What is the gender distribution for branch C?
Which time of the day do customers give most ratings?
Which time of the day do customers give most ratings for branch A?
Which day fo the week has the best avg ratings?
Which day of the week has the best average ratings for branch C?
Sales
Number of sales made in each time of the day day on Sunday?
Which of the customer types brings the most revenue?
Which city has the largest tax percent/ VAT (Value Added Tax)?
Which customer type pays the most in VAT?
