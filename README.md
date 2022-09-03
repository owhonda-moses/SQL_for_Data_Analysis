# SQL for Data Analysis

## INTRODUCTION

> This repo contains some key quizzes and their solutions using SQL queries for
lessons in the Udacity [SQL for Data Analysis](https://classroom.udacity.com/courses/ud198) course. The database is contained in the parch-and-posey.sql file and can be explored in your local machine using the following steps -
- Open PostgreSQL _psql_ shell
- Create a new database `CREATE DATABASE parch_and_posey;`
- Open command prompt and navigate to directory containing _pg_restore_ <img src="psql.png" width="260" height="26" />
- Import database `psql -h localhost -U postgres -d parch_and_posey -f path-to-sql-file.parch-and-posey.sql`
- Explore and run queries on the database from shell or pgAdmin.

Excepting the query on the sf_crime_data database, this Entity Relationship Diagram for the Parch and Posey database was used for all queries.
![alt text](ERD_Parch_and_Posey.png)



#### PACKAGES USED:

- PostgreSQL

_Referenced for this repository:_
- https://www.postgresql.org/docs/13/queries.html
- https://www.w3schools.com/sql/
- https://blog.sqlauthority.com/
- https://stackoverflow.com/
