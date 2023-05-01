This dataset contains information about food orders from a restaurant, including order ID, date, product, price, quantity, purchase type, payment method, manager, and city. 
Here is an overview of each column:
* Order ID: a unique identifier for each order
* Date: the date the order was made
* Product: the item(s) ordered
* Price: the price of each unit of the item(s) ordered
* Quantity: the quantity of the item(s) ordered
* Purchase Type: whether the order was made in-store or online
* Payment Method: the payment method used for the order
* Manager: the manager responsible for the location where the order was made
* City: the city where the order was made

Transforming and analyzing data

After cleaning up data which involves trimming extra spaces, rounding up decimal values, adding country column based on city location, adding revenue column based on price and quantity columns, below are the primary analysis data points :
1. The dataset contains orders made between November 7, 2022, and December 29, 2022, in four different cities: Paris, London, Madrid, Lisbon, and Berlin. 
2. The majority of orders were made in London, with 76 out of 258 orders. 
3. The popularity for all the food order items appears to be same.
4. The dataset also shows that most of the orders were made online and paid for using a credit card. 
5. In terms of managers, Jaoa Silva and Tom Jackson made were responsible for the most orders, with 153 out of 257 orders

Performing statistics on data
Found the Mean, Median, Mode, Standard Deviation, Sample Variance, Kurtosis, Skewness, Range, Minimum, Maximum, Sum, Count for columns Count and Quantity. Performed analysis on outliers for using box/whisker chart.

Performing data analysis
We answer various data driven questions and displayed them using pivot charts:
1. What is best selling product?
2. What is our total revenue?
3. What is revenue breakdown by payment method?

Data visualisation
We can visualize and present data using dynamic drop down lists and use formulas like SUMIFS and XLOOKUP to present data like calculate the total revenue sales  for each product and manager.
