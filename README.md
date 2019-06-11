# bamazon_prime.com
Node.js & MySQL
(the README is the project, scroll down)


Overview
Creating an Amazon-like storefront with MySQL

Take in orders from customers and deplete stock from the store's inventory

Bonus:

Track product sales
Summarize the highest-grossing departments
Save and require the MySQL and Inquirer npm packages

Submission Guide
Deploy to GitHub

CLI App, so no Heroku

Include screenshots of working app with no bugs in a README.md file

Instructions
Challenge: Customer View
Create a MySQL Database: bamazon

Create a Table inside of that database: products

Create the following columns in the products table:

item_id (unique id for each product)

product_name (name of product)

department_name

price (cost to customer)

stock_quantity (how much of the product is available in stores)

Populate database around 10 different products (i.e. Insert "mock" data rows into this database and table)

Create Node app: bamazonCustomer.js

Make app prompt users with two messages:

The first should ask them the ID of the product they would like to buy

The second message should ask how many units of the product they would like to buy

After customer pays:

Make app check selected product inventory

If no inventory, log phrase and prevent the order

If inventory is available, then fulfill order; this means, update SQL database and reflect remaining quantity

After updates, display total cost of purchase

If this activity took you between 8-10 hours, then you've put enough time into this assignment. Feel free to stop here -- unless you want to take on the next challenge.