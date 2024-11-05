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




![power BI insight for sales data](https://github.com/user-attachments/assets/950a1d7d-6be1-4351-8d4d-c19b47242f26)


![capston SQL sales data](https://github.com/user-attachments/assets/853302bf-eabb-4963-84c4-f9876a074782)

![capstone SQL for customer data](https://github.com/user-attachments/assets/f987ed6b-0dc4-4aef-962a-7bf6e9de368f)

## Outcome
### For Sales Data
The star product are shoes with a total sales of 613,380 this means our customer love to buy shoes. This is also a pointer to the fact that our customers love trendy shoes and so we concentrate our energy on being abreast with the shoes trend. Socks appeared last on the table, which means we need to work on increasing the demand for socks. Here a promotion sales can help drive its demand especially during the cold season and when schools resumes.
Looking at the sales on a monthly basis, we can see that most sales was done in February and July which happens to be the 1st and 3rd quarter of the year and by year end the sales nosedived to less than 50%.
The sales by region showed that more sales was done in the south region toping the table with over 900,000 sales and the west region with the least sales.
Overall, each of the product and region recorded its own unique success at different time of the year across the country showing the customers committed to our brand and pointing us to areas where we need to push for more sales to record more revenue.

### For Customer Data
Our analysis on the customer data showed that most pf our customers are on the basic subscription which speaks to the fact that it is very affordable and a whole lot of the customers are living within their budget as we can see that the average subscription period is 365 days.
At the region we can see that the east region recorded no cancellation unlike the other regions where customers sometimes canceled their plan. This again shows the level of loyalty that our customers have towards the brand
