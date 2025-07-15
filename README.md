# Pizza_DB Mini Project
This is a mini project based on the Pizza_DB database.

# Pizza Sales SQL Analysis

## Project Overview

This project explores sales and performance metrics of a fictional pizza store using a MySQL database. The dataset includes details on orders, pizza types, sizes, categories, prices, and quantities. The goal is to answer a series of business questions using SQL — ranging from basic aggregations to advanced analytics.

---

## Files

* **`pizza_db.sql`**: Contains the schema and sample data for the pizza store database.
* **`PizzaDB_solutions.sql`**: Contains SQL queries categorized by difficulty (Basic, Intermediate, Advanced) to analyze business performance metrics.

---

## Database Schema

The database includes the following key tables:

* `orders` - Order ID, date, and time of purchase.
* `order_details` - Detailed list of pizzas ordered per order.
* `pizzas` - Individual pizza details including size and price.
* `pizza_types` - Metadata about pizza types (name, category, ingredients).

---

## Key Analyses

### Basic Level

1. Total number of orders.
2. Total revenue generated.
3. Highest priced pizza.
4. Most common pizza size.
5. Top 5 most ordered pizza types.

### Intermediate Level

6. Total quantity of pizzas by category.
7. Hourly distribution of orders.
8. Category-wise distribution of pizzas.
9. Average number of pizzas ordered per day.
10. Top 3 pizza types by revenue.

### Advanced Level

11. Revenue contribution by pizza category.
12. Cumulative revenue over time.
13. Top 3 pizzas by revenue within each category.

---

## How to Use

1. Import the database:

   ```bash
   mysql -u your_username -p pizza_db < pizza_db.sql
   ```

2. Run the analysis queries:

   ```bash
   mysql -u your_username -p pizza_db < PizzaDB_solutions.sql
   ```

You can also run individual queries from the `.sql` file in any MySQL client or interface (e.g., MySQL Workbench, DBeaver).

---

## Requirements

* MySQL 8.0 or above
* SQL client (optional but recommended)

---

## Sample Insights

* The **most popular pizza** is likely from the "Italian Supreme" family.
* **Large-sized pizzas** are ordered more frequently than other sizes.
* **Evening hours** see the highest spike in pizza orders.
* A small number of pizza types contribute to the **majority of revenue**.

