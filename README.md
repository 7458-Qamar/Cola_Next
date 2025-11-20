# Cola NEXT Analytics System MySQL to Power BI

This project is an end to end data analytics system for a fictional beverage brand, Cola NEXT.  
I designed the full database in MySQL, connected it to Power BI, and built interactive dashboards for different business areas.

## Project Overview
This repository shows how to go from raw data design to business insights using:

- MySQL for database design and data storage  
- Power BI for modeling, visualization and reporting  
- Power Query for data cleaning and transformation  
- DAX for KPIs and calculated measures  

The project covers Orders, Products, Customers, Suppliers, Employees and Order Items.

## Database Structure
The database contains the following main tables:

- customers  
- products  
- orders  
- order_items  
- suppliers  
- employees  

Each table has realistic sample data and proper primary and foreign keys.

## Entity Relationship Diagram
The ERD connects the tables as follows:
- customers to orders  
- orders to order_items  
- products to order_items  
- suppliers as a separate dimension  
- employees as a separate dimension  

This structure is suitable for analytics and reporting in Power BI.

## Dashboards Included
### Orders Insights Dashboard
- Revenue by quarter  
- Revenue by payment method  
- Order status filters  
- Total revenue, total orders and average order value cards  

### Suppliers Insights Dashboard
- Supplier distribution by city using a map visual  
- City with most suppliers and city with fewest suppliers  
- Total suppliers card and supplier list  

### Products Insights Dashboard
- Top categories by stock quantity  
- Top products by stock quantity  
- Average price by category  
- Top products by total price  
- Top categories by price  
- Total products, average price and total stock cards  

### Order Items Insights Dashboard
- Quantity sold by product id  
- Subtotal by order id  
- Total revenue, total quantity and total order items cards  

### Employees Insights Dashboard
- Top highest paid employees  
- Positions with highest salary spend  
- Total employees card  

### Customers Insights Dashboard
- Loyalty points distribution  
- Top cities by customer count  
- Total customers and total loyalty points cards  

## Tools And Technologies
- MySQL and MySQL Workbench  
- Power BI Desktop  
- Power Query  
- DAX  
- SQL for data definition and data manipulation  

## What You Can Learn
- How to design and implement a relational database in MySQL  
- How to connect Power BI to a MySQL database  
- How to build a star schema style model for reporting  
- How to create multiple dashboards from one data model  
- How to combine SQL, Power Query and DAX in one project  

## Repository Contents
- SQL scripts for table creation and data insert  
- ERD image  
- Power BI pbix file  
- Dashboard screenshots  

## Contact


For collaboration, feedback, or similar dashboard requests, you can reach out to me on LinkedIn or GitHub.
