# LITA-capstone-project

## Sales Data Project Overview
The set of data here shows information about sales of various products in dierent region at dierent times. The information contained also shows the behavioral pattern of the customers in the kind of product they purchase and how it translates into revenue for the company concerned and how they meet the demands of customers
## Customer Subscription Project Overview
Here we see a set of data that projects the subscription pattern of customers, the drive in demand for subscription and revenue generated for it at dierent times
## Column Descriptions of Sales Data
Order ID: A unique number attached to each order placed.

Customer ID: This number is also unique to each customer placing an order

Product: The item purchased at every transaction.

Region: The geographical location of where the order was placed (i.e North, South, East, and West).

Order Date: The date when the order was Placed

Quantity: The number of units purchased for each product in an order.

Unit Price: The price per unit of the product.

Total Sales: The total sales value for the order. (calculated as Quantity * Unit Price)

## Column Descriptions for Customer Data

Customer ID: A unique number attached to each order placed.

Customer Name: Name of the customer.

Region: The geographical location of where the order was placed (i.e North, South, East, and West).

Subscription Type: Type of subscription plan the customer is enrolled for (e.g., Basic, Premium, Standard).

Subscription Start: commencement date of the customer's subscription.

Subscription End: Expiry date of the customer's subscription.

Canceled: this shows if the subscription was canceled (TRUE or FALSE).

Revenue: Revenue generated from the customer's subscription per time.

Subscription Duration: Duration of the subscription period (measured in days)

## Data Source
The data sources for this analysis is "Data Sales.csv" and "Customer data.csv" files. They are open-source datasets that is made available for free download in online repositories like Data squirrel, Kaggle, and other platforms where data can be gotten
## The following tools were used

Excel: this was used for cleaning the data and visualization.

SQL (Structured Query Language): used in data cleaning using queries.

Power BI: Used for both data cleaning and visualization
## Preparation and cleaning the data
The steps employed in the analysis are:

You load the data and check it

Identify missing variables

Format the data and clean it
## Exploring the data
Here you used the cleaned data to address the following issues to uncovered key insights 
## For Sales Data

Retrieve the total sales for each product category.

Find the number of sales transactions in each region.

Find the highest-selling product by total sales value.

Calculate total revenue per product.

Calculate monthly sales totals for the current year.

Find the top 5 customers by total purchase amount.

Calculate the percentage of total sales contributed by each region.

Identify products with no sales in the last quarter
## For Customer Data

Retrieve the total number of customers from each region.

Find the most popular subscription type by the number of customers.

Find customers who canceled their subscription within 6 months.

Calculate the average subscription duration for all customers.

Find customers with subscriptions longer than 12 months.

Calculate total revenue by subscription type.

Find the top 3 regions by subscription cancellations.

Find the total number of active and canceled subscriptions
## Data Analysis
This is where we include some basic lines of code or queries or even some of the DAX expressions used during your analysis;

select *
From Table Name = SalesData

select *
From Table Name = CustomerData

## Data Visualization







