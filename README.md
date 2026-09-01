# 🗄️ MySQL: From Basics to Advanced

Welcome to the **MySQL: From Basics to Advanced** repository! This repository contains a structured, hands-on SQL curriculum delivered via interactive Jupyter Notebooks. It covers relational database design, querying, data transformation, window functions, complex subqueries, Common Table Expressions (CTEs), query optimization, and database views.

---

## 📌 Table of Contents

- [Overview](#-overview)
- [Course Roadmap & Modules](#-course-roadmap--modules)
  - [1. Database Connection & Design Fundamentals](#1-database-connection--design-fundamentals)
  - [2. Basic Querying & Filtering](#2-basic-querying--filtering)
  - [3. Scalar & Numeric Functions](#3-scalar--numeric-functions)
  - [4. Aggregation & Summary Reports](#4-aggregation--summary-reports)
  - [5. Advanced Window Functions](#5-advanced-window-functions)
  - [6. Data Cleaning & Type Casting](#6-data-cleaning--type-casting)
  - [7. Conditional Logic & Case Studies](#7-conditional-logic--case-studies)
  - [8. Relational Schema, Keys & Joins](#8-relational-schema-keys--joins)
  - [9. Subqueries & CTEs](#9-subqueries--ctes)
  - [10. Optimization, Views & Final Assessment](#10-optimization-views--final-assessment)
- [Prerequisites & Setup](#-prerequisites--setup)
- [How to Run the Notebooks](#-how-to-run-the-notebooks)

---

## 💡 Overview

This collection provides a comprehensive path to mastering SQL and database engineering:
- **Foundations**: Establishing SQL connections, basic `SELECT` statements, logical operators, and relational database design.
- **Data Manipulation & Cleaning**: Applying string functions, date/time conversions, and scalar math functions.
- **Analytical SQL**: Leveraging window functions (`ROW_NUMBER`, `RANK`, `DENSE_RANK`, lead/lag) for Top-N ranking and running aggregations.
- **Advanced Architecture**: Designing Primary, Foreign, and Composite Keys across normalized tables.
- **Performance Tuning**: Comparing Subqueries vs. CTEs, indexing, query execution optimization, and managing database Views.

---

## 🗺️ Course Roadmap & Modules

### 1. Database Connection & Design Fundamentals
| Lesson | Topic | Notebook File |
| :--- | :--- | :--- |
| **Lesson 1** | Creating a Connection | `LESSON.1.creating a connection.ipynb` |
| **Lesson 2** | Database Design Principles | `LESSON.2.Database Design.ipynb` |

### 2. Basic Querying & Filtering
| Lesson | Topic | Notebook File |
| :--- | :--- | :--- |
| **Lesson 3** | `SELECT` and `WHERE` Clause | `LESSON.3.SELECT and WHERE.ipynb` |
| **Lesson 4** | Logical & Comparison Operators (Part I) | `LESSON.4.Using logical and comparison operators.ipynb` |
| **Lesson 5** | Logical & Comparison Operators (Part II) | `LESSON.5. Logical and comparison operators ii.ipynb` |
| **Lesson 6** | Reading Data Across Multiple Tables | `LESSON.6. Reading data across multiple tables.ipynb` |
| **Lesson 7** | Aliasing & Commenting Code | `LESSON.7. Aliasing and commenting in SQL.ipynb` |

### 3. Scalar & Numeric Functions
| Lesson | Topic | Notebook File |
| :--- | :--- | :--- |
| **Lesson 8** | Initial Data Analysis with Numeric Functions | `LESSON.8.Initial data analysis with numeric functions.ipynb` |
| **Lesson 9** | Transforming Columns Using Numeric Functions | `LESSON.9. Transform columns using numeric functions[Notebook].ipynb` |

### 4. Aggregation & Summary Reports
| Lesson | Topic | Notebook File |
| :--- | :--- | :--- |
| **Lesson 10** | Creating Summary Statistic Reports | `LESSON.10. Create a summary statistic report in SQL.ipynb` |
| **Lesson 11** | Filtering & Analyzing Summary Reports | `LESSON.11. Filtering and analysing summary statistic report [Notebook].ipynb` |

### 5. Advanced Window Functions
| Lesson | Topic | Notebook File |
| :--- | :--- | :--- |
| **Lesson 12** | Aggregation Using Window Functions | `LESSON.12. Aggregation using window functions [Notebook].ipynb` |
| **Lesson 13** | Top-N Analysis & Ranking Functions | `LESSON.13. Top-N analysis using ranking window functions [Notebook].ipynb` |
| **Lesson 14** | Value-Based Window Functions (`LEAD`/`LAG`/`FIRST_VALUE`) | `LESSON.14. Using value based window functions [Notebook].ipynb` |

### 6. Data Cleaning & Type Casting
| Lesson | Topic | Notebook File |
| :--- | :--- | :--- |
| **Lesson 15** | Converting Between Data Types (`CAST`/`CONVERT`) | `LESSON.15. Converting between data types.ipynb` |
| **Lesson 16** | Using String Functions to Clean Data | `LESSON.16. Using SQL string functions to clean data.ipynb` |
| **Lesson 17** | Creating Custom IDs with String Functions | `LESSON.17. Creating a custom ID using string functions.ipynb` |

### 7. Conditional Logic & Case Studies
| Lesson | Topic | Notebook File |
| :--- | :--- | :--- |
| **Lesson 18** | Grouping with `CASE` Statements | `LESSON.18. Grouping with a case statement.ipynb` |
| **Lesson 19** | Conditional Calculations Using `IF()` | `LESSON.19. Conditional-calculations-using-IF.ipynb` |
| **Lesson 20** | Case Study: Evaluating GDP per Capita (`CASE` & `IF`) | `LESSON.20. Evaluating GDP per Capita using CASE and IF.ipynb` |

### 8. Relational Schema, Keys & Joins
| Lesson | Topic | Notebook File |
| :--- | :--- | :--- |
| **Lesson 21** | Primary Keys: `Geographic_Location` Table | `LESSON.21. Primary keys - Create Geographic_Location table.ipynb` |
| **Lesson 22** | Composite & Foreign Keys: `Basic_Services` & `Economic_Indicators` | `LESSON.22. Composite+Foreign Keys - Basic_Services  & Economic_Indicators Table[Notebook].ipynb` |
| **Lesson 23** | `UNION`, `UNION ALL`, and `JOIN` Types | `LESSON.23. Unions and Joins.ipynb` |

### 9. Subqueries & CTEs
| Lesson | Topic | Notebook File |
| :--- | :--- | :--- |
| **Lesson 24** | Subquery in the `SELECT` Clause | `LESSON.24. Subquery in the SELECT clause [Notebook].ipynb` |
| **Lesson 25** | Subqueries in `JOIN` Clauses | `LESSON.25. Subqueries in JOIN [Notebook].ipynb` |
| **Lesson 26** | Subqueries in the `FROM` Clause | `LESSON.26. Subquery in FROM.ipynb` |
| **Lesson 27** | Subqueries in the `WHERE` Clause | `LESSON.27. Subqueries in WHERE.ipynb` |
| **Lesson 29** | Common Table Expressions (CTEs) vs Subqueries | `LESSON.29. CTE vs Subquery.ipynb` |

### 10. Optimization, Views & Final Assessment
| Lesson | Topic | Notebook File |
| :--- | :--- | :--- |
| **Lesson 28** | Optimizing SQL Queries & Execution Plans | `LESSON.28. Optimising_SQL_queries_Notebook.ipynb` |
| **Lesson 30** | Creating & Managing Database Views | `LESSON.30. Database views [Notebook].ipynb` |
| **Lesson 31** | Comprehensive SQL Exam & Practical Assessment | `LESSON.31. SQL_Exam.ipynb` |

---

## 🛠️ Prerequisites & Setup

### 1. Requirements
- **MySQL Server** (8.0+ recommended) or **MariaDB**.
- **Python 3.8+** with Jupyter installed (`jupyterlab` or `notebook`).
- `ipython-sql` or `pymysql` / `mysql-connector-python` packages for SQL execution in Jupyter.

### 2. Environment Setup
```bash
# Clone the repository
git clone <YOUR_REPOSITORY_URL>
cd "MySQL Basics to Advance"

# Install Python SQL dependencies
pip install jupyter ipython-sql pymysql mysql-connector-python pandas
```

---

## 🚀 How to Run the Notebooks

1. Start your local MySQL service (e.g. MySQL Workbench, XAMPP, or command-line server).
2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Open `LESSON.1.creating a connection.ipynb` to establish your database connection string, then proceed through the course!

---

## 📄 License

This repository is licensed under the MIT License.
