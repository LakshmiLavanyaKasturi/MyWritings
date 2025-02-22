# Understanding Data Science & SQL

## Introduction to Data Science
Data Science is an interdisciplinary field that combines **statistics, programming, and domain expertise** to extract insights from structured and unstructured data. It leverages techniques from fields such as **machine learning, data mining, and big data analytics** to make data-driven decisions.

### Key Components of Data Science:
1. **Data Collection** – Gathering raw data from various sources like databases, APIs, web scraping, etc.
2. **Data Cleaning** – Removing inconsistencies and handling missing values.
3. **Exploratory Data Analysis (EDA)** – Understanding data distributions and trends.
4. **Machine Learning & Modeling** – Applying algorithms to predict outcomes.
5. **Data Visualization** – Representing data insights using graphs and charts.

---

## SQL in Data Science
SQL (Structured Query Language) is a powerful tool used in **data extraction, manipulation, and analysis**. It helps data scientists interact with relational databases efficiently.

### Why SQL is Important in Data Science?
- Helps **retrieve and manipulate** data from large databases.
- Supports **data wrangling** and preprocessing for machine learning.
- Enables efficient **aggregation and filtering** of data.
- Used in **ETL (Extract, Transform, Load) processes** for big data handling.

### Basic SQL Commands for Data Science
```sql
SELECT column_name FROM table_name WHERE condition;
```
### Example: Using SQL for Data Analysis
Let's assume we have a dataset employees with the following sample data:

# Example: Using SQL for Data Analysis

Let's assume we have a dataset `employees` with the following sample data:

| EmployeeID | Name   | Department | Salary | JoinDate   |
|------------|--------|------------|--------|------------|
| 101        | Alice  | IT         | 80000  | 2020-05-10 |
| 102        | Bob    | HR         | 60000  | 2019-08-21 |
| 103        | Charlie| IT         | 75000  | 2021-01-15 |
| 104        | David  | Finance    | 90000  | 2018-11-03 |

## Query 1: Retrieve all IT department employees

```sql
SELECT * FROM employees WHERE Department = 'IT';
```
