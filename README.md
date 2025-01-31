# SQL Music Store Analysis
## Project Overview
This project involves analyzing a music store database using SQL. It covers various queries, ranging from beginner to advanced levels, to extract insights related to customers, purchases, invoices, music genres, and top artists.
## Dataset Description
The database consists of multiple tables, including:
* Employee – Stores employee details.
* Customer – Stores customer details.
* Invoice – Contains invoice records for music purchases.
* Invoice_Line – Provides details of each invoice transaction.
* Track – Stores track details like duration and genre.
* Album – Contains album information.
* Artist – Stores artist details.
* Genre – Categorizes music into different genres.
##  Technologies Used
*Database: PostgreSQL
*SQL Concepts Used:
 * JOIN operations
 * Aggregate functions (SUM(), COUNT(), AVG())
 * Subqueries and Common Table Expressions (CTEs)
 * Window functions (ROW_NUMBER(), PARTITION BY)
 * Sorting and filtering
## Project Structure
* Basic SQL queries for initial insights.
* Intermediate-level queries covering more complex joins and conditions.
* Advanced SQL queries using CTEs, window functions, and ranking.
## Key Queries & Insights
* Easy Level Queries
 * Identify the senior-most employee with the highest job titles.
 * Determine the country with the most invoices.
 * Find the top 3 invoice amounts.
 * Identify the city generating the most revenue.
 * Find the best customer based on total spending.

* Moderate Level Queries
 * List emails of all customers who listen to rock music.
 * Identify the top 10 artists producing the most rock music.
 * Retrieve all songs longer than the average song length.

* Advanced Level Queries
 * Calculate total spending by customers on a specific artist.
 * Identify the most popular music genre in each country.
* Determine the highest-spending customer in each country.
## How to Run the Queries
* Clone the repository:
 *git clone (https://github.com/MohanSaiPandeti/mohansaipandeti.github.io)
* Load the database into PostgreSQL
* Run the .sql scripts in your database client.
## Contributing
Contributions are welcome! If you find a bug or have an improvement, feel free to open an issue or submit a pull request.
