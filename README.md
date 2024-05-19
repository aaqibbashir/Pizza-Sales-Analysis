# Pizza Sales Analysis

This project analyzes pizza sales data using MySQL. The analysis is based on four Excel files that were imported into a MySQL server. The files and their respective columns are as follows:

1. **order_details:** *order_details_id, order_id, pizza_id, quantity* 

2. **orders:** *order_id, date, time*

3. **pizzas:** *pizza_type_id, name, category, ingredients* 

4. **pizza_types:** *pizza_id, pizza_type_id, size, price*

The project addresses various analytical questions through MySQL queries, which are categorized into Basic, Intermediate, and Advanced levels.

### Basic Questions:

* Retrieve the total number of orders placed.
* Calculate the total revenue generated from pizza sales.
* Identify the highest-priced pizza.
* Identify the most common pizza size ordered.
* List the top 5 most ordered pizza types along with their quantities.

### Intermediate Questions:

* Join the necessary tables to find the total quantity of each pizza category ordered.
* Determine the distribution of orders by hour of the day.
* Join relevant tables to find the category-wise distribution of pizzas.
* Group the orders by date and calculate the average number of pizzas ordered per day.
* Determine the top 3 most ordered pizza types based on revenue.

### Advanced Questions:

* Calculate the percentage contribution of each pizza type to total revenue.
* Analyze the cumulative revenue generated over time.
* Determine the top 3 most ordered pizza types based on revenue for each pizza category.
* The MySQL queries addressing these questions are included in the Solutions file.


# Installation

```
Import the Excel files into your MySQL server. Ensure the database schema matches the columns specified above. ```

