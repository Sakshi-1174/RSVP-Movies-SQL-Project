# RSVP Movies Data Analysis Using SQL

## Project Introduction

This project is based on the RSVP Movies case study. I worked on an IMDb movie dataset and used MySQL to solve 29 business questions related to the movie industry.

The purpose of this project was to understand the data, explore different aspects of movies, and find useful information about movie genres, ratings, directors, actors, and production companies.

While working on this case study, I got the opportunity to practice SQL queries and understand how data can be used to answer business-related questions.

## Project Objectives

The main objectives of this project were:

- To understand the structure of the IMDb database.
- To explore movie-related information stored in different tables.
- To analyze movie genres, ratings, and votes.
- To identify top-rated movies and popular genres.
- To analyze the performance of directors and actors.
- To understand movie production trends.
- To solve business questions using SQL queries.

## Tools & Technologies Used

- **Database:** MySQL
- **SQL Editor:** MySQL Workbench
- **Language:** SQL

## Database Structure

The project database contains six tables. Each table stores different information about movies and the people associated with them.

| Table Name | Description |
|---|---|
| movie | Stores movie details such as title, year, and duration |
| genre | Stores information about movie genres |
| director_mapping | Connects movies with their directors |
| role_mapping | Connects movies with actors and other roles |
| names | Stores information about people |
| ratings | Contains movie ratings and votes |

These tables are connected through common columns, which helped me retrieve information from multiple tables using SQL joins.

## SQL Concepts Used

During this project, I practiced the following SQL concepts:

**Basic SQL**
- SELECT
- WHERE
- DISTINCT
- ORDER BY
- LIMIT

**Data Aggregation**
- COUNT()
- SUM()
- AVG()
- MIN()
- MAX()
- GROUP BY
- HAVING

**Advanced SQL**
- INNER JOIN
- LEFT JOIN
- Subqueries
- Common Table Expressions (CTEs)
- Window Functions
- CASE Statements
- Date Functions
- Ranking Functions

I used these concepts according to the requirements of different business questions.

## Business Questions Solved

I worked on 29 business questions as part of this case study. Some of the important areas covered were:

1. Exploring the database and understanding the available tables.
2. Finding the total number of movies in the dataset.
3. Analyzing the distribution of movies across different genres.
4. Finding the average movie duration.
5. Identifying movies based on their ratings.
6. Finding the top-rated movies.
7. Analyzing movie releases across different years.
8. Studying the performance of production companies.
9. Analyzing movie ratings and votes.
10. Identifying popular movie genres.
11. Finding directors based on their movie contributions.
12. Analyzing the performance of directors.
13. Studying actors and their roles in movies.
14. Comparing movie performance across different categories.
15. Analyzing movies released in different time periods.
16. Studying Indian movies in the dataset.
17. Identifying successful movies based on ratings and other conditions.
18. Comparing ratings across different genres.
19. Ranking directors based on their performance.
20. Solving additional business problems using SQL.

*The complete set of 29 questions and their SQL solutions is available in the solution file.*

## Project Files

This repository contains the following two SQL files:

### 1. IMDB+dataset+import.sql
This file contains the SQL script used to create the IMDb database, create the required tables, and import the dataset.

### 2. RSVP_moives_solution.sql
This file contains my SQL queries and solutions for the 29 business questions included in the RSVP Movies case study.

## Key Learnings

While completing this project, I learned how to:

- Work with a relational database in MySQL.
- Retrieve and filter data using SQL queries.
- Combine information from multiple tables using joins.
- Group and summarize data using aggregate functions.
- Use subqueries and CTEs to solve complex questions.
- Apply window functions for ranking and analysis.
- Understand business questions and convert them into SQL queries.

This project also helped me improve my logical thinking and become more comfortable working with SQL.

## Conclusion

Overall, this case study gave me practical experience in working with a movie dataset and solving different business questions using SQL.

It helped me understand how SQL is used in data analysis and how information from a database can be used to answer real-world business questions.

---

**Project Name:** RSVP Movies Data Analysis   
**Domain:** Data Analytics  
**Database:** MySQL
