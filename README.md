# SQL Exercises Repository

**About:** In this repository I have added some notebooks with queries that helped me practice SQL

**SQL Flavor:** I am using PostgreSQL.

**Content:**
<ol>
  <li><a href=https://nbviewer.jupyter.org/github/DSJourney/SQL/blob/master/1.%20MOMA/1.%20SQL_Exercise_MOMA.ipynb>Museum of Modern Art (MoMA)</a></li>
  <li>Coding Website Exercises: <a href=https://nbviewer.jupyter.org/github/DSJourney/SQL/blob/master/2.%20Coding%20Exercise%20Websites/HackerRank_Exercises.ipynb#easy>HackerRank</a>, <a href=https://nbviewer.jupyter.org/github/DSJourney/SQL/blob/master/2.%20Coding%20Exercise%20Websites/Leetcode_Exercises.ipynb>Leetcode</a></li>
  <li><a href=https://nbviewer.jupyter.org/github/DSJourney/SQL/blob/master/3.%20Dvd%20Rental/dvd.ipynb>DVD Rental Company</a></li>
  <li><a href=https://nbviewer.jupyter.org/github/DSJourney/SQL/blob/master/4.%20DataCamp%20/DataCamp.ipynb>Datacamp Exercises</a></li>  
</ol>

<br>
<br>

## 1. Museum of Modern Art (MoMA)

<img src="https://github.com/DSJourney/SQL-Practice/blob/master/img/MoMA.jpg" width="500">


**Picture:** [Arquitectural Digest](https://www.architecturaldigest.com/story/new-york-iconic-museum-of-modern-art-completed-450-million-makeover)

**Dataset:** For this exercise I used the two dataset shared by the MoMA [1]. They can be found [here](https://github.com/MuseumofModernArt/collection) <br> 
**Edited Dataset:** I made some edits to the "Artworks" dataset to practice JOIN commands. This dataset is in the "data" folder.

<br>

The markdown on the jupyter notebooks does not show well on GitHub. To see the document with the correct markdown you have two options:<br>
1) See it on [NBviewer](https://nbviewer.jupyter.org/github/DSJourney/SQL/blob/master/1.%20MOMA/1.%20SQL_Exercise_MOMA.ipynb)<br>
2) Download it and open it with Jupyter Lab or Jupyter Notebook<br>

<br>

With this first exercise I went over the following commands (the levels are completely made up by me):

Level | Commands
------------ | -------------
L1| `SELECT` / `FROM` / `COUNT` / `LIMIT` / `DISTINCT` / `WHERE` / `AND` / `BETWEEEN` / `IN` / `NULL` or `NOT NULL` / `LIKE` or `NOT LIKE`
L2| Aggregate Functions (`AVG`, `SUM`, `MIN`, `MAX`) / `ROUND` / Aliases / `ORDER BY` / `GROUP BY` / `HAVING`
L3| `JOIN`, Arithmetic, `CASE`, `COALESCE`, `OFFSET`
L4| Nested queries, CTEs, `LENGTH`, `CUBE`, `UPDATE`, `SET`, `RETURNING`
L5| Window functions (`OVER`, `PARTITION BY`), Random number of rows, Datatypes

The idea is to continue improving and adding new commands and datasets. Any recommendation on exercises or in improving the queries in this exercise will be welcomed.
<br>
<br>
<br>

**References**
###### 1. Robot, Open Data. (2020). MoMA Collection - Automatic Monthly Update [Data set]. Zenodo. http://doi.org/10.5281/zenodo.3924816 <br>

------------------
<br>
<br>

## 2. Coding Website Exercises

<img src="https://github.com/DSJourney/SQL/blob/master/2.%20Coding%20Exercise%20Websites/img/HackerRank.png" width="150"> <img src="https://github.com/DSJourney/SQL/blob/master/2.%20Coding%20Exercise%20Websites/img/LeetCode.png" width="150">

**Disclaimer:** the exercises in these notebooks come from coding websites. Currently from two main websites: <a href=https://www.hackerrank.com/domains/sql> Hackerrank</a> and <a href=https://leetcode.com/>Leetcode</a>. These two website are great to practice coding interviews. I sincerely recommend anyone trying to learn to use those. Their GUI are very intuitive and you learn a lot from other people doing the same exercises.
<br>

HackerRank Exercises on [NBviewer](https://nbviewer.jupyter.org/github/DSJourney/SQL/blob/master/2.%20Coding%20Exercise%20Websites/HackerRank_Exercises.ipynb#easy)<br>
Leetcode Exercises on [NBviewer](https://nbviewer.jupyter.org/github/DSJourney/SQL/blob/master/2.%20Coding%20Exercise%20Websites/Leetcode_Exercises.ipynb)<br>

------------------
<br>
<br>

## 3. DVD Rental Company

<img src="https://github.com/DSJourney/SQL/blob/master/3.%20Dvd%20Rental/img/schema.png" width="600"> 

**Dataset:** I have downloaded the dataset from <a href=https://www.postgresqltutorial.com/postgresql-sample-database/> Postgresqltutorial.com</a>. That website has great resources to learn Postgresql. The queries came from questions I found on Zachary Thomas' great document <a href=https://quip.com/2gwZArKuWk7W>The Best Medium-Hard Data Analyst SQL Interview Questions</a> or from questions I wanted answered for myself.

DVD Rental Company Exercises on [NBviewer](https://nbviewer.jupyter.org/github/DSJourney/SQL/blob/master/3.%20Dvd%20Rental/dvd.ipynb)<br>

Some of the interesting exercises and the critical commands used were:

**Calculations** | **Commands**
------------ | -------------
Median |  `PERCENTILE_CONT(0.5) WITHIN GROUP`
Month over Month Calculations| Self-join with `DATE_TRUNC`
MAU, retained users, churned users| Self-joins, `DATE_TRUC`, ctes
Cummulative Sum | cte with `OVER (ROWS BETWEEN UNBOUNDED PRECEDENT AND CURRENT ROW`
7 day Moving Avg | `AVG(count) OVER (ROWS BETWEEN 6 PRECEDING AND CURRENT ROW)`

------------------
<br>
<br>

## 4. DataCamp Exercises

<img src="https://github.com/DSJourney/SQL/blob/master/4.%20DataCamp%20/img/datacamp-vector-logo.png" width="600"> 

**Dataset:** [DataCamp is a website](datacamp.com) with courses on different programming languages. It includes several courses on SQ ranging from beginner to advanced. I have been doing some of them lately and they are great. I took the opportunity and wrote down they queries I found more interesting in these notebooks to keep them close for the future. Here I will be adding a list of the most interesting exercises I came across while doing the courses. Needless to say, I really recommend [DataCamp](datacamp.com) for anyone who is trying to learn programming. 

DataCamp Exercises on [NBviewer](https://nbviewer.jupyter.org/github/DSJourney/SQL/blob/master/4.%20DataCamp%20/DataCamp.ipynb)<br>

Some of the interesting exercises were:

**Delivr Company**
<ol>
  <li>Revenue, Cost, Profit</li>
  <li>Registration and Active Users</li>
  <li>Running Total</li>
  <li>Monthly Active Userst</li>
  <li>Growth Over Time</li>
  <li>Unit Economics
    <ul>
      <li>Average Revenue per User (ARPU)</li>
      <li>Weekly Average Revenue per User</li>
    </ul>
    </li>
  <li>Histograms</li>
  <li>Percentiles</li>
  <li>Working with Dates</li>
  <li>Ranking</li>
  <li>Pivoting (using Crosstab)</li>
</ol>
