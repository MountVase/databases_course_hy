# Tietokantojen Perusteet 2020

### Part 1
Working with the sqlite3 database file kurssit.db. Contains information about courses, participants, teachers, credits etc... Jupyter notebook provides functions to:

1. Print sum of student credits given per year
2. Print all courses and grades for one student
3. Print average grade (1-5) from given course
4. Print top x teachers by given credits

kurssit.db contains other interesting information aswell, worth checking out.

### Part 3
Creating a file testi.db, and testing performance of sql with and/or without indexing. 
Each command contains the following actions with varying use of indexing:

1. Creates table Elokuvat with columns
2. Creates 1 000 000 random movies with release year between 1900-2000
3. Selects count of movies from a random year 1000 times

Demonstrates the usage of indexing in a database, when it's useful, and when it can reduce performance/take up extra space.
