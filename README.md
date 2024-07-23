# Grocery-Store-Sales-Analysis

FoodYum is a fiction grocery store chain that is based in the United States.
FoodYum sells items such as produce, meat, dairy, baked goods, snacks, and other household food staples.


I dove in to do in-depth analysis of this fake data to test my SQL skills in practise.

Data description:
Column Name	Criteria
product_id - Nominal. The unique identifier of the product. Missing values are not possible due to the database structure.
product_type - Nominal. The product category type of the product, one of 5 values (Produce, Meat, Dairy, Bakery, Snacks). Missing values should be replaced with “Unknown”.
brand	- Nominal. The brand of the product. One of 7 possible values. Missing values should be replaced with “Unknown”.
weight - Continuous. The weight of the product in grams. This can be any positive value, rounded to 2 decimal places. Missing values should be replaced with the overall median weight.
price - Continuous. The price the product is sold at, in US dollars. This can be any positive value, rounded to 2 decimal places. Missing values should be replaced with the overall median price.
average_units_sold - Discrete. The average number of units sold each month. This can be any positive integer value. Missing values should be replaced with 0.
year_added - Nominal. The year the product was first added to FoodYum stock. Missing values should be replaced with last year (2022).
stock_location - Nominal. The location that stock originates. This can be one of four warehouse locations, A, B, C or D. Missing values should be replaced with “Unknown”.
