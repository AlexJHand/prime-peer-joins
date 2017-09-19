#Week 4: SQL Joins

In this challenge, we’re going to practice performing SQL queries with multiple tables. This should help better solidify some concepts that were covered during lecture.

# Setup
Follow the instructions below before continuing with this challenge.

## Create your database, table, and data

We are creating a database with a multiple tables and records. Please follow the instructions below to create a new database with this table and data.

1. Open Postico and connect to `localhost` db server
2. Click the elephant in the upper left.
3. Create a new database using the button near the bottom.
4. Double click on your newly created database.
4. In the SQL query window, run the queries in the [database.sql](database.sql) file to set up your database.

## Entity Relationship Diagram (ERD)
See a diagram of the available entities and their relationships. [https://docs.google.com/drawings/d/1AyIEFz6pvTtVZJ8M9GCJD38WNZ3ylJT0Pc1YB9P5sX8/edit?usp=sharing](https://docs.google.com/drawings/d/1AyIEFz6pvTtVZJ8M9GCJD38WNZ3ylJT0Pc1YB9P5sX8/edit?usp=sharing)

NOTE: Remember that a many-to-many relationship requires a join table, so the entities in the diagram may be missing some actual tables. Explore the tables in your database.

## GitHub repo
1. Create a GitHub repo named “prime-peer-joins”. 
2. Create a file called “joins-solution.sql”. You will store your responses to the exercise questions here. NOTE: This is merely a text file with a .sql extension.

# Exercise

For each of the following questions

* Write a comment that specifies which question you are answering. (SQL comments are two dashes, followed by text.)
* Write the SQL query that answers the question, below that comment.
* Once one person writes half of the queries, switch off.

## Example question and answer
```
-- 0. Get all the users
SELECT * FROM customers;
```

# Tasks
1. Get all customers and their addresses.
2. Get all orders and their line items.
3. Which warehouses have cheetos?
4. Which warehouses have diet pepsi?
5. Get the number of orders for each customer. NOTE: It is OK if those without orders are not included in results.
6. How many customers do we have?
7. How many products do we carry?
8. What is the total available on-hand quantity of diet pepsi?
