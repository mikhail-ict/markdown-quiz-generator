### SQL and Database Quiz Questions (Day 2)

---
1. What is the role of the `COUNT()` function in **SQL**?
    - [ ] To sum the values of a column
    - [ ] To return the highest value in a column
    - [x] To count the number of rows in a result set
    - [ ] To group rows based on a column

2. What is the purpose of `ROLLUP`?
    - [ ] To join multiple tables
    - [x] To produce summary reports using aggregate functions
    - [ ] To filter results
    - [ ] To sort data

3. Which **SQL** keyword is used to eliminate duplicate rows in a result set?
    - [ ] WHERE
    - [ ] JOIN
    - [ ] GROUP BY
    - [x] DISTINCT

4. Can the `HAVING` clause be used without the `GROUP BY` clause in **SQL**?
    - [ ] Yes, in all cases
    - [x] No, it must be used with `GROUP BY`
    - [ ] Yes, but only with aggregate functions
    - [ ] No, it's used instead of `WHERE`

5. What does the `GROUP BY` clause do in combination with aggregate functions?
    - [ ] Joins multiple tables
    - [ ] Sorts the result set
    - [ ] Filters the result set
    - [x] Groups the result set by one or more columns

6. The `LIKE` operator in **SQL** is used for exact string matching.
    - ( ) True
    - (x) False

7. Name the **SQL** function that returns the current database system date and time. The answer should be written in CAPITAL LETTERS and include `()` at the end.
    - R:= GETDATE()

8. In SQL, the `GROUP BY` clause must come after the `SELECT` clause but before the `WHERE` clause.
    - ( ) True
    - (x) False

9. Which **SQL** keyword is used to sort the query result set in descending order?
    - [ ] ASC
    - [ ] SORT
    - [ ] DOWN
    - [x] DESC

10. The `RIGHT JOIN` in **SQL** returns all rows from the right table and the matched rows from the left table.
     - (x) True
     - ( ) False

11. Which of the following is not an aggregate function in **SQL**?
     - [ ] AVG
     - [x] ISNULL
     - [ ] COUNT
     - [ ] SUM

12. What is the function of an `INNER JOIN` in **SQL**?
     - [x] To return rows when there is a match in both tables
     - [ ] To return all rows from the right table, and matched rows from the left table
     - [ ] To combine rows from two or more tables
     - [ ] To return all rows from both tables, with `NULL` in place of unmatched rows

13. Which **SQL** functions are used to manipulate text strings?
     - [ ] SUM
     - [x] LEFT
     - [x] UPPER
     - [x] SUBSTRING

14. What are the purposes of the **SQL** `DATEPART()` and `DATENAME()` functions?
     - [ ] To convert date to a string
     - [ ] To sort dates in order
     - [x] To extract the part of the date
     - [x] To get the name of the part of the date

15. You can use column aliases in both `HAVING` and `ORDER BY` clauses
     - ( ) True
     - (x) False