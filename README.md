# SQL for Data Analysis

## INTRODUCTION

> This repo contains selected key quizzes and solutions with SQL queries for
all lessons taught in the Udacity [SQL for Data Analysis](https://classroom.udacity.com/courses/ud198) course. The database is contained in the parch-and-posey.sql file and can be explored in your local machine using the following steps -
- Open PostgreSQL psql shell
- Create a new database `CREATE DATABASE parch_and_posey;`
- Open command prompt and navigate to directory containing _pg_restore_. 
![alt text](psql.jpg)
- Import database `psql -h localhost -U postgres -d parch_and_posey -f path-to-sql-file.parch-and-posey.sql`
- Explore and run queries on the database from shell or pgAdmin.

Excepting the query on the sf_crime_data database, this Entity Relationship Diagram for the Parch and Posey database was used for all queries.
![alt text](ERD_Parch_and_Posey.png)



#### PACKAGES USED:

- PostgreSQL

_Referenced for this repository -_
- https://www.postgresql.org/docs/13/queries.html
- https://www.w3schools.com/sql/
- https://blog.sqlauthority.com/2015/11/04/sql-server-what-is-the-over-clause-notes-from-the-field-101/
- https://stackoverflow.com/
