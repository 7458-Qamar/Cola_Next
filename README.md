<img width="1094" height="599" alt="Screenshot 2025-11-20 201218" src="https://github.com/user-attachments/assets/61b9f4f6-5f54-4329-ba93-0f1eb2d041ab" /># Cola NEXT Analytics System MySQL to Power BI

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
<img width="982" height="668" alt="Screenshot 2025-11-20 202009" src="https://github.com/user-attachments/assets/431728fc-57d8-4d1d-8c45-4e8ccd41dc13" />

## Dashboards Included
### Customers Insights Dashboard
- Loyalty points distribution  
- Top cities by customer count  
- Total customers and total loyalty points cards  
<img width="1126" height="596" alt="Screenshot 2025-11-20 200821" src="https://github.com/user-attachments/assets/69c96b60-f37d-4b15-a1ca-efc61f70d97b" />

### Employees Insights Dashboard
- Top highest paid employees  
- Positions with highest salary spend  
- Total employees card  
<img width="1092" height="596" alt="Screenshot 2025-11-20 200918" src="https://github.com/user-attachments/assets/56e2782f-2fed-4060-98b3-d2f826698018" />

### Orders Insights Dashboard
- Revenue by quarter  
- Revenue by payment method  
- Order status filters  
- Total revenue, total orders and average order value cards  
<img width="1092" height="623" alt="Screenshot 2025-11-20 201640" src="https://github.com/user-attachments/assets/d347bb05-2f0c-40a2-97e3-ad95af2c172d" />

### Products Insights Dashboard
- Top categories by stock quantity  
- Top products by stock quantity  
- Average price by category  
- Top products by total price  
- Top categories by price  
- Total products, average price and total stock cards  
<img width="1115" height="602" alt="Screenshot 2025-11-20 201150" src="https://github.com/user-attachments/assets/f59cd44a-0257-4eac-a1b0-6d4cb31cc983" />

### Order Items Insights Dashboard
- Quantity sold by product id  
- Subtotal by order id  
- Total revenue, total quantity and total order items cards  
<img width="1119" height="604" alt="image" src="https://github.com/user-attachments/assets/0215b9da-3153-4f0e-b945-cd35a7a7936f" />

### Suppliers Insights Dashboard
- Supplier distribution by city using a map visual  
- City with most suppliers and city with fewest suppliers  
- Total suppliers card and supplier list  
![Uploading Screenshot 2025-11-20 201218.png…]()

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
