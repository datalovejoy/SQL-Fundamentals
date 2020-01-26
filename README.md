# SQL
These are notes taken while studying SQL and performing exercises.

Here I used a correlated subquery and common table expression (CTE) to circumvent the limitations of a simple join by simultaneously combining two columns from one table with a single column from another into one final query result. Both of these techniques will retrieve the home and away team names and goals from data provided by the European Soccer Database.

One thing to be wary of when using a correlated subquery is that it can quickly become resource intensive, so use sparingly. A CTE on the otherhand, allows you to organize subqueries sequentially, and reference other CTEs declared earlier.
