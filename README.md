# ics311-term-project-database-implementation-on-mysql-solved
**TO GET THIS SOLUTION VISIT:** [ICS311 Term Project-Database Implementation on MySQL Solved](https://www.ankitcodinghub.com/product/ics311-term-project-database-implementation-on-mysql-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;98932&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ICS311 Term Project-Database Implementation on MySQL Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="section">
<div class="layoutArea">
<div class="column">
Part 1:

In this part you are required to implement your database on MySQL. Your implementation should include the following:

1- Create all the tables that you specified in your relational schema (Part 2, of Step 2). Make sure to include primary keys and foreign keys.

2- Populate all tables with data of your choice. Make sure that each table includes at least 10 rows.

.SQL file was submitted for this part

</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
Part 2:

Design and clearly explain at least ten query scenarios that may be useful on your database.

Write SQL syntax to answer each query.

A query like this: select count(*) from tableOne, can only be used as one of the ten.

Strongly suggested to include some queries using Table Joins, Aggregates, Group By, Order By, and Having.

At least one query must use a view (that you created from your application tables) in the FROM clause.

Note: the SELECT used for in the creation of the view, does not count as one of the 10 queries.

Query 1

USE OF COUNT(*)

SELECT COUNT(*) FROM Movie;

Query-2

USE OF VIEW-

View-A View is a temporary table and it is same as the main table but we can perform any operation on it without modifying main table.

CREATE VIEW Count_Movie AS(SELECT MovieID,Genre FROM Movie);

Now Display data of view-

SELECT * FROM Count_Movie;

Query-4

USE OF AGGREGATE FUNCTION-

SELECT SUM(Show.ShowID) AS SUM FROM Movie INNER JOIN Show ON Show.MovieID=Movie.MovieID;

</div>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="layoutArea">
<div class="column">
Query-5

USE OF GROUP BY-

SELECT Show.ShowID FROM Show GROUP BY Show.MovieID,Show.ShowID;

Query-6

USE OF ORDER BY

SELECT Show.ShowID FROM Show ORDER BY Show.ShowID DESC;

Query-7

USE OF HAVING

SELECT Show.ShowID FROM Show GROUP BY Show.ShowID

HAVING Show.ShowID&gt;1;

Query-9

USE of GROUP BY AND ORDER BY TOGETHER- SELECT Movie.MovieID FROM Movie

GROUP BY Movie.MovieID

ORDER BY Movie.MovieID DESC;

Query-10

Use of Above all functions-

SELECT Movie.Genre,Show.ShowID FROM Movie INNER JOIN Show ON Show.MovieID=Movie.MovieID WHERE Movie.MovieID&gt;1

GROUP BY Movie.Genre,Show.ShowID

HAVING COUNT(Show.ShowID)&gt;2

</div>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="section">
<div class="layoutArea">
<div class="column">
ORDER BY Show.ShowID DESC;

ELECT is used to display all(*) or specified column/columns

COUNT( ) is used to count number of rows inside specified column.

table_name1.column_name1,Here it specifies that column_name1 is of table table_name1

INNER JOIN is used to join two tables based on a common column.

WHERE is used to specify condition.

We cannot use aggregate function directly inside where so HAVING is used.

GROUP BY is used to group result as per the column specified.

ORDER BY is used to sort result either in ascending(ASC)increasing or descending(DESC)decreasing order.

What to submit:

1- A word document to explain your query scenarios (in good detail) along with SQL syntax to answer these queries. Make sure to include at least two aggregate queries, also some doing table joins, some order by’s and group by’s (in other words have a good variety that incorporates the material we have been learning).

2- There is a dropbox folder on D2L to turn in your project code. You need to turn in the ‘.sql’ scripts that include:

a. SQL statements to create the tables (from Part 1 above).

b. SQL statements to populate tables with data (from Part 1 above).

c. SQL statements for your query scenarios (from Part 2). d. SQL used to create the view (from Part 2).

Note that you need to include all the required SQL statements in file. This could be a Word Doc. or a text file that ends in “.sql”. Make sure to test your file before you submit it.

</div>
</div>
</div>
</div>
