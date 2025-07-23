## Introduction
The purpose of this study is to clean up the data and provide insights on the shopping behaviors of Instacart's customers. The main steps of the project are as follows:

Open data files to examine their contents.
Clean up the data by verifying data types, find and fill in missing values, find and remove duplicates.
Analyze the data by examining shopping patterns incliuding: a.Most popular time of day to shop b.Most popular day to show c.How long between order placements d.Distribution of order e. Top 20 products ordered f. How many items purchased in one order and the distribution g. Top 20 most reordered items The visualizations of the data will provide useful insights for Instacart to better serve their customers. 

## Data 
Description of the data:

instacart_orders.csv: each row corresponds to one order on the Instacart app

'order_id': ID number that uniquely identifies each order

'user_id': ID number that uniquely identifies each customer account

'order_number': the number of times this customer has placed an order

'order_dow': day of the week that the order placed (which day is 0 is uncertain)

'order_hour_of_day': hour of the day that the order was placed

'days_since_prior_order': number of days since this customer placed their previous order

products.csv: each row corresponds to a unique product that customers can buy

'product_id': ID number that uniquely identifies each product

'product_name': name of the product

'aisle_id': ID number that uniquely identifies each grocery aisle category

'department_id': ID number that uniquely identifies each grocery department category

order_products.csv: each row corresponds to one item placed in an order

'order_id': ID number that uniquely identifies each order

'product_id': ID number that uniquely identifies each product

'add_to_cart_order': the sequential order in which each item was placed in the cart

'reordered': 0 if the customer has never ordered this product before, 1 if they have

aisles.csv
'aisle_id': ID number that uniquely identifies each grocery aisle category

'aisle': name of the aisle

departments.csv
'department_id': ID number that uniquely identifies each grocery department category

'department': name of the department

## Libraries Used 
pandas

## Table of Contents 
1. Introduction
2. Data Preprocessing
3. EDA
4. Conclusion 
