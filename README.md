🛒 Walmart Sales Data Analysis

📖 Overview:

This project analyzes Walmart’s sales data using Python and SQL to uncover key business insights related to sales performance, customer behavior, and operational patterns across multiple branches.

🧰 Tools & Technologies Used:

Python 

Libraries: numpy, pandas, sqlalchemy, pymysql

MySQL for data storage and querying

Jupyter Notebook 

🗂️ Dataset:

The dataset used is Walmart.csv, containing transaction-level data with the following key columns:

invoice_id — Unique ID for each transaction

branch — Store branch 

city — Location of the branch

category — Product category

unit_price, quantity — Pricing and sales details

payment_method — Payment type (e.g., Cash, Ewallet, Credit card)

rating — Customer satisfaction rating

profit margin

date, time — Transaction date and time

📊 Key Analyses & Insights:

1️⃣ Payment Method Analysis
Found different payment methods used by customers.
Determined the number of transactions and quantity sold by each payment method.

2️⃣ Highest-Rated Category per Branch
Identified the top-rated product category for each branch based on average customer ratings.
Displayed branch, category, and avg_rating.

3️⃣ Busiest Day by Transactions
Determined the busiest day of the week for each branch by analyzing the number of transactions per day.

4️⃣ Quantity Sold per Payment Method
Calculated the total quantity of items sold for each payment method.
Helped understand customer preferences for payment options.

5️⃣ Ratings by City and Category
Calculated the average, minimum, and maximum rating for each category per city.
Provided insights into regional performance and customer satisfaction.

6️⃣ Profit by Category
Computed the total profit for each category using a calculated profit margin.
Highlighted which product categories contribute most to branch profitability.

7️⃣ Preferred Payment Method per Branch
Identified the most common payment method in each branch using SQL ranking/window functions.

8️⃣ Sales by Time of Day
Categorized transactions into Morning, Afternoon, and Evening shifts.
Determined which shift generates the most sales.



