<div align="center">

# SQL Practice Portfolio

**Hands-on SQL exercises using MySQL to build practical database and data analysis skills.**

![MySQL](https://img.shields.io/badge/Database-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![SQL](https://img.shields.io/badge/Language-SQL-336791?style=flat-square)
![Portfolio](https://img.shields.io/badge/Project-Learning%20Portfolio-5B6EE1?style=flat-square)
![Status](https://img.shields.io/badge/Status-In%20Progress-orange?style=flat-square)

</div>

---

## Overview

This repository contains SQL practice materials covering foundational database concepts and commonly used SQL queries. The exercises are intended to strengthen practical skills with **MySQL** and provide a foundation for larger, real-world data analysis projects.

## Learning Objectives

- Retrieve data using `SELECT`.
- Filter and sort records using `WHERE`, `ORDER BY`, and `LIMIT`.
- Create and manage databases, tables, and records.
- Combine related tables using SQL joins.
- Summarize data with aggregate functions such as `COUNT()`, `SUM()`, and `AVG()`.
- Group results using `GROUP BY`.
- Practice updating and deleting records safely.

## Practice Sets

| No. | Topic | Focus |
|:---:|---|---|
| 01 | SQL Fundamentals | Basic SQL syntax and database concepts |
| 02 | SQL Queries | Retrieving, filtering, and sorting data |
| 03 | SQL Joins | Combining information from related tables |
| 04 | Aggregate Functions & `GROUP BY` | Summarizing and grouping records |

> **Note:** Update the practice-set titles and filenames below to match the exact files included in your repository.

## Tools & Technologies

- **MySQL** — relational database management system
- **MySQL Workbench** — SQL development and query execution
- **SQL** — querying and managing relational data

## Repository Structure

```text
SQL/
├── README.md
├── Practice-Set-01-SQL-Fundamentals.pdf
├── Practice-Set-02-SQL-Queries.pdf
├── Practice-Set-03-SQL-Joins.pdf
└── Practice-Set-04-SQL-Aggregate-Functions-and-GROUP-BY.pdf
```

*The filenames above are examples. Keep only the folders and files that actually exist in your repository.*

## Getting Started

1. Install MySQL Server and MySQL Workbench.
2. Download or clone this repository.
3. Open a practice set and review the exercise requirements.
4. Create the required database and tables in MySQL Workbench.
5. Write and execute each query.
6. Save completed solutions as `.sql` files and document useful results.

## Example Query

The following example returns products in the Electronics category, ordered from highest to lowest price:

```sql
SELECT product_id, pname, price
FROM products
WHERE category = 'Electronics'
ORDER BY price DESC;
```

*Run the query against a database that contains a `products` table with the listed columns.*

## Project Development Roadmap

- [ ] Add `.sql` files containing completed exercise solutions.
- [ ] Include sample schemas or datasets where appropriate.
- [ ] Add screenshots of selected queries and their results.
- [ ] Build an end-to-end SQL analysis project using a realistic dataset.
- [ ] Summarize key findings and explain the decisions supported by the analysis.

## Purpose

This project is part of my ongoing SQL learning journey. It is designed to demonstrate consistent practice, improve problem-solving skills, and build a foundation for data analysis work.

## Connect

Thank you for visiting this repository. Feedback and suggestions for improving the exercises and project structure are welcome.

---

<div align="center">

**Learning SQL one query at a time.**

</div>
