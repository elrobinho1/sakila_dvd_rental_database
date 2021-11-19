17th September 2021

# Explore Sakila DVD Rental database

## Description
In this project, I will use SQL to explore a database related to movie rentals. I will write SQL code to run SQL queries and answer interesting questions about the database. As part of my project submission, I will **run SQL queries and build visualizations** to showcase the output of my queries.

## The Datasets
The dataset is the **Sakila DVD Rental database.** The Sakila Database holds information about a company that rents movie DVDs.
The database contains 14 tables that are connected together via foreign keys. The table in the database are:

* category
* film_category
* film
* film_actor
* inventory
* rental
* payment
* staff
* actor
* customer
* address
* city
* country
* store

Each table has 2 or more columns including the primary key

## Statistics Computed

1. Create a query that;
    - Lists each movie
    - The film category each movie is classified in
    - The number of times each movie has been rented out:

2. Provide a table with the movie titles and divide them into 4 levels:

 - first_quarter
 - second_quarter
 - third_quarter
 - final_quarter

 based on the quartiles (25%, 50%, 75%) of the rental duration for movies across all categories? indicating the category that these family-friendly movies fall into.

3. Provide a table with the family-friendly film category, each of the quartiles, and the corresponding count of movies within each combination of film category for each corresponding rental duration category. The resulting table having three columns:

- Category
- Rental length category
- Count

4. Write a query that returns;
- the store ID for the store
- the year and month
- the number of rental orders each store has fulfilled for that month.

## Softwares needed
To complete this project, I used the following softwares:

* SQL
* A text editor, I used Atom
* A terminal application
* Microsoft Excel

## Interactive Environment
This project explores Sakila DVD Rental database. It uses data from the database tables compute statistics from those 14 tables, also makes visualization of my results and save them in .csv files.
