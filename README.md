# ⚡ Top 50 SQL Questions with Apache Spark

> A topic-wise collection of 50 essential SQL problems solved using Apache Spark and PySpark, with a focus on query logic, data manipulation, and interview preparation.

### 📌 About the Repository

Welcome to **Top 50 SQL Questions with Apache Spark**! 🚀

This repository contains a curated collection of 50 SQL problems organized by topic and solved using the Apache Spark ecosystem.

The goal is to strengthen SQL fundamentals while learning how to apply them to distributed data processing using Spark. Each problem provides an opportunity to practice analytical thinking, understand data transformations, and develop solutions that can be applied to real-world data engineering scenarios.

Whether you're preparing for SQL interviews, learning PySpark, or strengthening your foundations in big data processing, this repository serves as a structured and practical learning resource.

#### 🎯 Objectives

- 🧠 Strengthen SQL fundamentals and problem-solving skills.
- ⚡ Learn to solve SQL problems using Spark SQL and PySpark.
- 🗂️ Organize problems by topic for structured learning and revision.
- 🔍 Understand filtering, aggregation, joins, and analytical queries.
- 🪟 Practice window functions and advanced data transformations.
- 📊 Explore how relational data operations translate into Spark workflows.
- 💼 Prepare for SQL and data engineering interviews.
- 📚 Maintain a reusable reference for future learning.

### 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| 🐍 Python | Core programming language for PySpark solutions |
| ⚡ Apache Spark | Distributed data processing engine |
| 🗄️ Spark SQL | SQL querying and relational data transformations |
| 📊 PySpark | Python API for working with Spark DataFrames |
| 🐙 Git & GitHub | Version control and repository management |

### 📂 Repository Structure

Problems are organized **topic-wise**, making it easier to learn concepts progressively, revisit specific topics, and track your progress.

```text
Top-50-SQL-Questions/
│
├── README.md
│
├── 01-select-and-filtering/
│   ├── README.md
│   ├── 01-problem-name.py
│   └── ...
│
├── 02-aggregation-and-grouping/
│   ├── README.md
│   └── ...
│
├── 03-joins/
│   ├── README.md
│   └── ...
│
├── 04-subqueries-and-cte/
│   ├── README.md
│   └── ...
│
├── 05-window-functions/
│   ├── README.md
│   └── ...
│
├── 06-string-and-date-functions/
│   ├── README.md
│   └── ...
│
└── ...
```

*The topic folders and filenames are illustrative and can be adjusted to match the final set of 50 problems.*

#### 🗂️ Why Topic-Wise Organization?

- **Better learning progression:** Master foundational concepts before moving to advanced topics.
- **Easy navigation:** Find problems by the SQL concept they exercise.
- **Focused revision:** Revisit a topic without searching through unrelated solutions.
- **Scalable structure:** Add more problems without cluttering the repository root.
- **Consistent documentation:** Give each topic its own overview and problem index.

### 🧩 Topics Covered

The repository can be organized around the following SQL concepts:

| Topic | Key Concepts |
|---|---|
| 🟢 Selection & Filtering | `SELECT`, `DISTINCT`, `WHERE`, logical operators |
| ↕️ Sorting & Limiting | `ORDER BY`, `LIMIT` |
| 🔤 String Functions | Pattern matching, substring operations, text manipulation |
| 📅 Date & Time Functions | Date extraction, date comparisons, date arithmetic |
| 📦 Aggregation & Grouping | `COUNT`, `SUM`, `AVG`, `MIN`, `MAX`, `GROUP BY`, `HAVING` |
| 🔗 Joins | Inner, left, right, and full outer joins |
| 🪆 Subqueries & CTEs | Nested queries and common table expressions |
| 🪟 Window Functions | `ROW_NUMBER`, `RANK`, `DENSE_RANK`, `LAG`, `LEAD` |
| 🔀 Conditional Logic | `CASE WHEN`, conditional expressions |
| 🧮 Advanced Queries | Multi-step transformations and complex analytical problems |

The final topic distribution will depend on the 50 selected questions.

### 📝 Solution Format

Each problem will have a dedicated Python file containing its Spark-based solution.

Where appropriate, solutions may include:

1. **📌 Problem Statement:** Define the task and expected output.
2. **🧠 Intuition:** Explain the key observation behind the solution.
3. **🪜 Approach:** Break the problem into logical steps.
4. **💻 Spark Solution:** Implement the logic using Spark SQL or PySpark.
5. **🔍 Explanation:** Describe how the query or DataFrame transformations work.
6. **⏱️ Complexity Analysis:** Discuss time and space considerations where meaningful.
7. **🧪 Examples & Edge Cases:** Validate the solution with representative inputs.

The aim is to understand both the problem-solving logic and the Spark-specific implementation.

### ⚡ Spark SQL vs. PySpark

This repository focuses on solving SQL problems in the Apache Spark ecosystem.

- **Spark SQL:** Express data transformations using SQL syntax through Spark.
- **PySpark DataFrame API:** Express equivalent transformations using Python methods and Spark DataFrames.

For example, a filtering operation can be expressed in Spark SQL:

```sql
SELECT *
FROM employees
WHERE salary > 50000;
```

Or using PySpark:

```python
from pyspark.sql import functions as F

result = employees.filter(F.col("salary") > 50000)
```

Both approaches can use Spark's execution engine. The choice depends on the problem and the implementation style being practiced.

### 🚀 How to Use This Repository

1. Choose a topic folder.
2. Read the problem statement and identify the expected result.
3. Attempt the problem independently.
4. Implement the solution using Spark SQL or PySpark.
5. Review the explanation and test edge cases.
6. Compare alternative implementations when appropriate.
7. Mark the problem as completed in the main README.

---
