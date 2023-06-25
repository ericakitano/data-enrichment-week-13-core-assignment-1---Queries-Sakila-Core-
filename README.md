# data enrichment week 13 
## Core Assignment #1 - Queries: Sakila (Core)
 Queries: Sakila (Core)

## Assignment:
- Create a new repository and notebook for this assignment.
- Using the Sakila database, complete the below queries with Python in your Jupyter Notebook.
      - You can use MySQL Workbench to test your queries and then copy and paste them into your notebook to perform with Pandas and SQLAlchemy.
- You can get the Sakila database and ERD here (sakila-data.sql and sakila-db-model.png), please use these for reference.
      - Tip: you can insert the ERD into your notebook in a Markdown cell using: "![png](IMAGE_URL_HERE)"
      - Replace "IMAGE_URL_HERE" with the link to the ERD above.

## Queries
1. What query would you run to get all the customers inside city_id = 312? Your query should return the customers' first name, last name, email, address, and city.

2. What query would you run to get all comedy films? Note that the genre is called the category in this schema. Your query should return film title, description, release year, rating, and special features.

3. What query would you run to get all the films that Johnny Lollobrigida was in? Your query should return the actor's last name, film title, and release year.

4. What query would you run to get the first and last names of all the actors in the movie titled "Bingo Talented"?

5. What query would you run to get the customer_id associated with all payments greater than twice the average payment amount? (HINT: use 2* in your query to get twice the amount). Your result should include the customer id and the amount.

6. What query would you run to list the first and last names of the 5 customers who have the highest number(count) of payments? You can title the number of payments as num_payments.

