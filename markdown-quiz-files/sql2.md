### SQL and Database Quiz Questions (Day 1)

---
1. In **SQL**, what is the command used to retrieve data from a database table? The answer should be written in **CAPITAL LETTERS**.
    - R:= SELECT

2. In **SQL**, the `DELETE` command is used to remove entire tables from a database.
    - ( ) True
    - (x) False

3. What is the **SQL** command used to remove a whole database? The answer should be written in **CAPITAL LETTERS**.
    - R:= DROP DATABASE

4. Identify the correct statements about **RDBMS**.
    - [x] RDBMS uses a table-based structure.
    - [ ] RDBMS cannot handle large amounts of data.
    - [x] RDBMS supports SQL for querying and managing data.
    - [ ] RDBMS data is stored in a hierarchical manner.

5. In the `CREATE TABLE Product` statement, what does `ProductID INT NOT NULL` signify?
    - [ ] `ProductID` is the primary key of the `Product` table
    - [x] `ProductID` is a column of integer type that cannot have null values
    - [ ] `ProductID` is a default value for the `Product` table
    - [ ] `ProductID` is a column that will automatically generate values

6. What does a 'Table' represent in relational database terminology?
    - [x] A specific set of data organised in rows and columns
    - [ ] A set of SQL commands
    - [ ] A connection between two databases
    - [ ] A backup of the database

7. In the context of a surrogate primary key, what is the purpose of `IDENTITY(1,1)`?
    - [ ] It sets the default value of `ProductID` to `1`
    - [ ] It limits the `ProductID` values to a range starting from `1`
    - [x] It auto-generates unique values for `ProductID`, starting at `1` and incrementing by `1`
    - [ ] It defines `ProductID` as a foreign key

8. Which of the following statements are true regarding database **Normalisation**?
    - [ ] It increases the complexity of queries.
    - [x] It involves dividing a database into two or more tables and defining relationships between the tables.
    - [ ] It is a process to backup data.
    - [x] It helps in reducing data redundancy.

9. What are **ACID** properties in a database?
    - [ ] Types of database schemas
    - [ ] Data encryption methods
    - [ ] Database backup techniques
    - [x] Rules ensuring reliable transactions

10. In **SQL**, the `CREATE` command is used only to create tables.
     - ( ) True
     - (x) False

11. Which of the following are types of **SQL**?
     - [x] DDL (Data Definition Language)
     - [ ] DSL (Data Specification Language)
     - [x] DCL (Data Control Language)
     - [ ] DTL (Data Transformation Language)
     - [x] DML (Data Manipulation Language)

12. What is the result of executing the **SQL** command to insert values `'Hamlet', 1, 9.99` into the `Product` table?
     - [ ] The table `Product` is created with one row
     - [ ] A new column is added to the `Product` table
     - [x] A new row is added with `'Hamlet', 1, 9.99`, and default values for `ProductID` and `DateCreated`
     - [ ] The values `'Hamlet', 1, 9.99` are updated in all rows of the `Product` table

13. In the statement `DateCreated DATE DEFAULT getdate()`, what is the role of `DEFAULT getdate()`?
     - [ ] It creates a new date every time the table is accessed
     - [x] It sets the default value of DateCreated to the current date
     - [ ] It prevents the DateCreated column from having null values
     - [ ] It links the DateCreated column to the system date

14. **T-SQL** is an open source (not proprietary) extension to **SQL** used by **Microsoft** in **SQL Server**.
     - ( ) True
     - (x) False

15. **SQL Server Management Studio (SSMS)** is a tool used for configuring, managing and administering all components within **Microsoft SQL Server**.
     - (x) True
     - ( ) False