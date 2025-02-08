# Pizza Sales Management System (SQL-based)

This project is a database-driven system designed to manage and track pizza sales efficiently using SQL. It enables pizza restaurants or businesses to keep track of their sales transactions, customer orders, inventory, and financial data with ease. By leveraging SQL databases, this project focuses on providing a reliable and scalable solution for managing pizza sales.

### Key Features:
- **Sales Tracking**: Store and query sales data, including pizza types, order quantities, and total sales.
- **Inventory Tracking**: Track ingredient stock levels and usage, making it easier to reorder supplies based on sales trends.
- **Reports and Analytics**: Generate detailed reports on sales performance, popular pizzas, and revenue over specific time periods (daily, weekly, monthly).
- **Order History**: Maintain an order history table for easy tracking of completed or canceled orders.

### Technologies Used:
- **Database**: MySQL, PostgreSQL, or SQLite for storing all the data related to sales, customers, inventory, and orders.
- **SQL Queries**: Use SQL to insert, update, delete, and select data from the database. Implement complex queries for generating reports and managing relationships between tables.
- **Data Modeling**: Design the database schema with tables such as `Orders`, `Pizzas`, `Pizza_types`, and `Order_details`.

### Database Schema:
- **Pizzas Table**: Contains details of available pizzas (e.g., pizza name, ingredients, price).
- **Orders Table**: Stores order information (e.g., order date, customer ID, pizza IDs, quantity, total price).
- **Pizza_types Table**: Tracks ingredients used for pizzas (e.g., tomato sauce, cheese, toppings) and their stock levels.
- **Orders_details Table**: Records completed transactions, linking order IDs with payment status and revenue.

### Benefits of the Project:
- **Efficient Data Management**: Use SQL to organize, store, and retrieve sales and customer data quickly.
- **Scalable**: Easily expand the database as the pizza business grows, adding more features like delivery tracking or promotions.
- **Data-Driven Insights**: Generate sales reports and analyze customer preferences to optimize menu offerings and improve sales strategies.
