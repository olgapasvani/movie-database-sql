# Movie Database SQL Queries

This repository contains a collection of advanced SQL queries designed for a relational movie database. It demonstrates the use of complex joins, subqueries, aggregation, and set operations.

**Database Schema**
* actor: Stores actor details (ID, name, gender, film count).
* director: Stores director details (ID, name).
* genre: Stores movie genres (ID, name).
* movie: Stores movie details (ID, title, year, rank).
* role: Links actors to movies and defines their specific roles.
* movie_has_genre: Links movies to their corresponding genres.
* movie_has_director: Links movies to their directors.

**Queries Included**
The SQL script includes solutions for 7 distinct data retrieval tasks:
1. Finding movies by specific actor surnames and genres.
2. Identifying actors based on complex shared-director and genre conditions.
3. Checking the existence of specific movie genres in a given year.
4. Aggregating data for actors with exact movie counts.
5. Counting directors for single-genre movies.
6. Finding actors who have participated in all available movie genres (relational division).
7. Calculating the number of common directors for every pair of movie genres.