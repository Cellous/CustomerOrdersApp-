# Customer Orders CRUD Application

This is a Java console application that connects to a MySQL database to manage customers and their orders. It supports full CRUD operations and generates spending reports with input validation.

## Features

- Insert, update, delete customers.
- Insert, update, delete orders linked to customers.
- Generate spending reports by customer, date range, or both.
- Input validation for date format and customer existence.

## Tech Stack

- Java
- MySQL
- JDBC (MySQL Connector/J)

## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Cellous/CustomerOrdersApp.git

## Setup

### 1. Configure MySQL Connection
In `CustomerOrdersApp.java`, update the following lines with your MySQL credentials:

```java
static final String URL = "jdbc:mysql://localhost:3306/customer_orders_db";
static final String USER = "root";

## Sample Data

This project includes a sample SQL script to populate the `orders` table with 15 test orders.

### How to Import Test Data

1. Make sure your MySQL server is running.
2. Ensure your `customer_orders_db` database and `orders` table exist.
3. From your project folder (where `test_orders_insert.sql` is located), run the following command:

```bash
mysql -u root -p customer_orders_db < test_orders_insert.sql

static final String PASSWORD = "devry123";


