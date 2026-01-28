# Walmart_Sales_Data_Analysis

This project analyzes Walmart’s sales data to uncover insights into top-performing branches and product lines, evaluate sales and customer trends, and understand key factors influencing business performance. In addition to identifying patterns in sales behavior, this analysis translates insights into strategic recommendations aimed at improving revenue, operational efficiency, and customer satisfaction.

The dataset, sourced from a Kaggle Walmart Sales Forecasting competition, contains historical sales records across multiple Walmart branches and departments. The analysis focuses on identifying demand patterns, revenue drivers, and customer behavior while also assessing the impact of time, location, and product categories on sales performance.

# Through detailed analysis, this project aims to:

* Identify top-performing stores and departments.

* Uncover seasonal and product-based sales trends.

* Understand the influence of promotional events and holidays.

* Develop data-driven insights to optimize sales strategies.

# About the Data

The dataset was obtained from the Kaggle Walmart Sales Forecasting Competition.
It contains sales transactions from three different Walmart branches located in Mandalay, Yangon, and Naypyitaw.

Dataset Overview:
* Rows: 1000
* Columns: 17

 | Column |	Description|	Data Type|
| :-------:|:---------:|:----------|
|invoice_id |	Invoice of the sales made	|VARCHAR(30)|
|branch	|Branch at which sales were made	|VARCHAR(5)|
|city	|The location of the branch|	VARCHAR(30)|
|customer_type	|The type of the customer|	VARCHAR(30)|
|gender	|Gender of the customer making purchase	|VARCHAR(10)|
|product_line	|Product line of the product solf	|VARCHAR(100)|
|unit_price|	The price of each product	|DECIMAL(10, 2)|
|quantity	|The amount of the product sold	|INT|
|VAT	|The amount of tax on the purchase	|FLOAT(6, 4)|
|total|	The total cost of the purchase	|DECIMAL(10, 2)|
|date|	The date on which the purchase was made|	DATE|
|time	|The time at which the purchase was made	|TIMESTAMP|
|payment_method	|The total amount paid	|DECIMAL(10, 2)|
|cogs	|Cost Of Goods sold	|DECIMAL(10, 2)|
|gross_margin_percentage|	Gross margin percentage	|FLOAT(11, 9)|
|gross_income|	Gross Income|	DECIMAL(10, 2)|
|rating	|Rating	|FLOAT(2, 1)|


# Analysis Overview
1. Product Analysis

Understand different product lines.

Identify best-performing and underperforming product lines.

Suggest improvements for weaker product categories.

2. Sales Analysis

Analyze sales trends across months, cities, and departments.

Measure the effectiveness of sales strategies.

Recommend modifications to enhance future sales.

3. Customer Analysis

Identify different customer segments and their buying behavior.

Determine profitability per segment.

Understand customer demographics and preferences.

# Approach Used
1. Data Wrangling

Inspect data for NULL or missing values.

Replace or handle missing values appropriately.

Create and populate database tables with the dataset.

Ensure all fields are defined with NOT NULL constraints to avoid missing data.

2. Feature Engineering

New features were generated from existing data to provide deeper insights:

time_of_day – Categorizes sales into Morning, Afternoon, and Evening.

day_name – Extracts the weekday (Mon–Fri) of each transaction to identify busy days.

month_name – Extracts the month (Jan–Dec) to analyze monthly sales and profit trends.

3. Exploratory Data Analysis (EDA)

EDA was performed to answer the business questions and objectives listed below.

# Business Questions
# Generic Questions

* How many unique cities does the data have?

* In which city is each branch located?

# Product Analysis

* How many unique product lines exist?

* What is the most common payment method?

* What is the best-selling product line?

* What is the total revenue by month?

* Which month had the largest COGS?

* Which product line had the highest revenue?

* Which city generated the highest revenue?

* Which product line had the largest VAT?

* Fetch each product line and add a column labeled “Good” or “Bad” based on whether its sales exceed the average.

* Which branch sold more products than the average quantity sold?

* What is the most common product line by gender?

* What is the average rating of each product line?

# Sales Analysis

* Number of sales made during each time of the day per weekday.

* Which customer type generates the most revenue?

* Which city has the highest VAT percentage?

* Which customer type pays the most VAT?

# Customer Analysis

* How many unique customer types exist?

* How many unique payment methods exist?

* What is the most common customer type?

* Which customer type buys the most?

* What is the gender of most customers?

* What is the gender distribution per branch?

* During which time of the day do customers give the most ratings?

* Which time of the day receives the highest ratings per branch?

* Which day of the week has the best average ratings?

* Which day of the week has the best average ratings per branch?

# Conclusion

This project provides a comprehensive understanding of Walmart’s sales performance by analyzing product trends, customer behavior, and time-based purchasing patterns. Beyond identifying key insights, the analysis translates findings into strategic recommendations focused on improving product performance, strengthening customer loyalty, optimizing inventory planning, and enhancing operational efficiency.

The insights and recommendations derived from this analysis can support data-driven decision-making, helping Walmart improve revenue growth, customer satisfaction, and overall business performance.
