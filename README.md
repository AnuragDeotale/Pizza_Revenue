# PizzaHut Database Analysis

This project involves creating a database for PizzaHut, populating it with schema and data, and performing SQL queries for analysis. The project focuses on calculating metrics like total revenue, top-selling pizzas, and order patterns.

## Database Schema

### Tables
1. **`orders`**: Stores details about orders placed.
   - `order_id`: Unique identifier for each order.
   - `order_date`: The date of the order.
   - `order_time`: The time of the order.

2. **`order_details`**: Contains details of items in each order.
   - `order_details_id`: Unique identifier for each order detail.
   - `order_id`: References the `orders` table.
   - `pizza_id`: References the `pizzas` table.
   - `quantity`: Number of pizzas ordered.

3. **`pizzas`**: Stores details of each pizza type.
   - `pizza_id`: Unique identifier for each pizza.
   - `price`: Price of the pizza.
   - `size`: Size of the pizza.

4. **`pizza_types`**: Details about pizza categories and names.
   - `pizza_type_id`: Unique identifier for each type.
   - `name`: Name of the pizza type.
   - `category`: Category to which the pizza belongs.

## SQL Queries

### Basic Queries
- Retrieve the total number of orders placed.
- Calculate total revenue generated from pizza sales.
- Identify the highest-priced pizza.
- Find the most common pizza size ordered.
- List the top 5 most ordered pizza types and their quantities.

### Intermediate Queries
- Total quantity of pizzas ordered by category.
- Distribution of orders by hour of the day.
- Average number of pizzas ordered per day.
- Top 3 most ordered pizza types by revenue.

### Advanced Queries
- Percentage contribution of each pizza type to total revenue.
- Cumulative revenue generated over time.
- Top 3 most ordered pizza types by revenue for each category.

## How to Use
1. **Create the Database**: Run the SQL script to create the `PizzaHut` database and its schema.
2. **Populate Data**: Insert sample data into the tables.
3. **Run Queries**: Execute the provided queries to analyze data and generate insights.

## Sample Insights
- The most profitable pizza categories.
- The busiest hours for orders.
- The most popular pizza types and sizes.
- Revenue trends over time.

## Requirements
- MySQL or any compatible SQL database.
- A SQL client to execute the script (e.g., MySQL Workbench, DBeaver).


