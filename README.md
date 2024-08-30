# SQL

Overview of SQL for Analytics
SQL (Structured Query Language) is a powerful language used for managing and querying relational databases. In the context of analytics, SQL is essential for data extraction, transformation, and analysis. It allows analysts and data scientists to manipulate and query data effectively to derive insights and make data-driven decisions.


### **Notes on SQL for Analytics**

#### **1. Basic SQL Queries**
- **SELECT Statement**: Retrieves data from one or more tables.
- **WHERE Clause**: Filters records based on specific conditions.
- **ORDER BY Clause**: Sorts the results in ascending or descending order.
- **LIMIT Clause**: Limits the number of rows returned.

#### **2. Aggregate Functions**
- **COUNT()**: Counts the number of rows.
- **SUM()**: Calculates the sum of a numeric column.
- **AVG()**: Computes the average of a numeric column.
- **MIN()** and **MAX()**: Finds the minimum and maximum values.
- **GROUP BY Clause**: Groups rows with the same values into summary rows.
- **HAVING Clause**: Filters groups based on aggregate function results.

#### **3. Joins**
- **INNER JOIN**: Returns records with matching values in both tables.
- **LEFT JOIN**: Returns all records from the left table and matched records from the right table.
- **RIGHT JOIN**: Returns all records from the right table and matched records from the left table.
- **FULL JOIN**: Returns all records when there is a match in either left or right table.

#### **4. Subqueries**
- **Definition**: A query nested inside another query.
- **Correlated Subqueries**: Subqueries that refer to columns in the outer query.

#### **5. Window Functions**
- **ROW_NUMBER()**: Assigns a unique sequential integer to rows within a partition.
- **RANK()**: Assigns ranks to rows within a partition.
- **SUM() OVER()**: Calculates cumulative or moving sums.

#### **6. Data Transformation**
- **CASE Statement**: Creates conditional logic within queries.
- **CAST() and CONVERT()**: Change data types.
- **String Functions**: Manipulate and extract information from strings.
- **Date Functions**: Handle date and time values.

#### **7. Data Aggregation and Reporting**
- **Pivot Tables**: Summarize data and transform rows into columns.
- **Common Table Expressions (CTEs)**: Temporary result sets that can be referenced within a query.

### **Best Practices**
- **Indexing**: Use indexes to improve query performance.
- **Normalization**: Structure data to minimize redundancy and improve data integrity.
- **Query Optimization**: Write efficient queries and use EXPLAIN plans for optimization.
- **Data Security**: Implement access controls and secure sensitive data.

### **Applications of SQL for Analytics**
- **Business Intelligence**: Generate reports and dashboards for KPIs and metrics.
- **Data Exploration**: Perform exploratory data analysis to identify trends and patterns.
- **Data Cleaning**: Prepare and clean data for analysis.
- **Data Integration**: Combine data from multiple sources for comprehensive analysis.
