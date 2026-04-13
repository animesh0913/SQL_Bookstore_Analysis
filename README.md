# SQL_Bookstore_Analysis
This SQL project focuses on analyzing performance and sales data from a book catalog using
relational databases. The objective is to build a structured database, insert data from two CSV files, and run SQL
queries to derive insights related to book popularity, author performance, publisher
revenue, and trends across genres and years. 

**Objective**
To create a normalized bookstore database using SQL. 
To insert data from two sources: books.csv and ratings.csv. 
To perform SQL queries for commercial, literary, and publisher analysis. 
To use SQL subqueries, CTEs, and window functions for advanced insight generation. 

**Why This Project**
Understanding trends in the publishing industry helps businesses and publishers make data
driven decisions. This project simulates a simplified version of real-world publishing analytics,
useful for data analysts, market researchers, and business professionals in the literary domain. 

**Tools Used**
MySQL Workbench 

**Database Schema**
Two tables were created: books and ratings.

**Key features / Data types:** 
*books*
book_id: INT, Primary Key 
book_name, author, publisher, genre: VARCHAR
publishing_year: YEAR
language_code: VARCHAR 

*ratings*
book_id: INT 
author_rating: VARCHAR
book_average_rating: FLOAT
book_ratings_count: INT
gross_sales, publisher_revenue, sale_price: FLOAT
units_sold: INT 

**Understanding Dataset**

*books.csv *
Contains book metadata (title, author, publisher, year, genre, language). 

*ratings.csv*
Contains performance metrics (ratings, reviews, revenue, sales).

**Key Queries and Insights**
1. Top-Selling Books by Gross Sales
2. Average Rating by Genre
3. Publishers with Highest Revenue
4. High-Rated Books Published in 2012
5. Prolific Authors and Their Ratings
6. Hidden Gems: High Rating, Low Sales
7. Profit Margin per Book
8. Most Rated English Books
9. Sales by Publishing Year
10. Author Rating > Book Rating

**Key Learnings**
Implemented CTEs, subqueries, and window functions for detailed analysis. 
Practiced creating and importing relational datasets from CSVs. 
Gained insights into publishing, reader behavior, and book trends. 
Understood the balance between commercial success and reader satisfaction. 


