# SQL Exercises Repository

**About:** In this repository I add some code related to SQL. In the notebooks found here I practice SQL queries. I try to take interesting datasets to make the learning more interesting. Currently there is only 1 dataset (see below).

**SQL Flavor:** I am using PostgreSQL in these exercises.

<br>
<br>

## 1. Museum of Modern Art (MoMA)

![Image of MoMA](https://github.com/DSJourney/SQL-Practice/blob/master/img/MoMA.jpg)

**Picture:** [Arquitectural Digest](https://www.architecturaldigest.com/story/new-york-iconic-museum-of-modern-art-completed-450-million-makeover)

**Dataset:** For this exercise I used the two dataset shared by the MoMA [1]. They can be found [here](https://github.com/MuseumofModernArt/collection) <br> 
**Edited Dataset:** I made some edits to the "Artworks" dataset to practice JOIN commands. This dataset is in the "data" folder.

<br>

The markdown on the jupyter notebooks does not show well on GitHub. To see the document with the correct markdown you have several options:<br>
1) See it on [NBviewer](https://nbviewer.jupyter.org/github/DSJourney/SQL-Practice/blob/master/1.%20SQL_Exercise_MOMA.ipynb)<br>
2) See it as [HTML](https://htmlpreview.github.io/?https://github.com/DSJourney/SQL-Practice/blob/master/1.%20SQL_Exercise_MOMA.html)<br>
3) Download it and open it with Jupyter Lab<br>

<br>

With this first exercise I went over the following commands (the levels are completely made up by me to provide myself a sense of accomplishment):

Level | Commands
------------ | -------------
L1|  SELECT / FROM / COUNT / LIMIT / DISTINCT / WHERE / AND / BETWEEEN / IN / NULL or NOT NULL / LIKE or NOT LIKE
L2| Aggregate Functions (AVG, SUM, MIN, MAX) / ROUND / Aliases / ORDER BY / GROUP BY / HAVING
L3| JOIN, Arithmetic, CASE statements, COALESCE, OFFSET
L4| Nested queries, CTEs, LENGTH, CUBE, UPDATE, SET, RETURNING
L5| Window functions (OVER, PARTITION), Random number of rows, Datatypes

The idea is to continue improving and adding new commands and datasets. Any recommendation on exercises or in improving the queries in this exercise will be welcomed.
<br>
<br>
<br>

**References**
###### 1. Robot, Open Data. (2020). MoMA Collection - Automatic Monthly Update [Data set]. Zenodo. http://doi.org/10.5281/zenodo.3924816 <br>
