---
id: 20240223215656
title: "SQL"
created: 2024-02-24T02:56:56.953Z
tags:
  - areas
  - type/litnote
---

SQL (Structured Query Language) is a powerful tool used for managing and manipulating relational databases (Example-MySQL, Oracle, PostgreSQL)

# Database:
An organized collection of structured data, usually controlled by a database management system(DBMS).
# SQL Basics:

1. **SELECT Statement:**
   - Used to retrieve data from a database.
   ```sql
   SELECT column1, column2
   FROM table_name
   WHERE condition;
   ```

2. **INSERT Statement:**
   - Used to insert new records into a table.
   ```sql
   INSERT INTO table_name (column1, column2)
   VALUES (value1, value2);
   ```

3. **UPDATE Statement:**
   - Used to modify existing records in a table.
   ```sql
   UPDATE table_name
   SET column1 = value1
   WHERE condition;
   ```

4. **DELETE Statement:**
   - Used to remove records from a table.
   ```sql
   DELETE FROM table_name
   WHERE condition;
   ```

5. **JOIN Clause:**
   - Used to combine rows from two or more tables based on a related column.
   ```sql
   SELECT column1, column2
   FROM table1
   JOIN table2 ON table1.column_name = table2.column_name;
   ```

6. **GROUP BY Clause:**
   - Used with aggregate functions to group the result set by one or more columns.
   ```sql
   SELECT column1, COUNT(*)
   FROM table_name
   GROUP BY column1;
   ```

7. **ORDER BY Clause:**
    - Used to sort the result set in ascending or descending order.
    ```sql
    SELECT column1, column2
    FROM table_name
    ORDER BY column1 ASC/DESC;
    ```

8. **WHERE Clause:**
    - Used to filter records based on specified conditions.
    ```sql
    SELECT column1, column2
    FROM table_name
    WHERE condition;
    ```
