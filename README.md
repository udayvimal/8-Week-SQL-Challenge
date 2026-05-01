# 📊 8 Week SQL Challenge — Solutions by udayvimal

![SQL](https://img.shields.io/badge/Language-SQL-blue?style=flat-square&logo=postgresql)
![PostgreSQL](https://img.shields.io/badge/Database-PostgreSQL-336791?style=flat-square&logo=postgresql)
![Status](https://img.shields.io/badge/Status-In%20Progress-yellow?style=flat-square)

This repository contains my personal solutions to the **[8 Week SQL Challenge](https://8weeksqlchallenge.com/)** by Danny Ma — a series of realistic business case studies designed to build advanced SQL skills.

Each case study simulates a real-world business problem. I worked through all questions independently, writing SQL queries from scratch and documenting my thought process and answers.

---

## 👤 About Me

**udayvimal** — Aspiring Business Analyst with a strong focus on data analysis and SQL.

- 🔗 [LinkedIn](https://www.linkedin.com/in/uday-vimal-9a1a3a253)
- 🐙 [GitHub](https://github.com/udayvimal)
- 📧 udayvimal08@gmail.com

---

## 📚 Table of Contents

| # | Case Study | Topics Covered |
|---|-----------|----------------|
| 1 | [🍜 Danny's Diner](#1--dannys-diner) | Joins, Aggregations, CTEs |
| 2 | [🍕 Pizza Runner](#2--pizza-runner) | Data Cleaning, Joins, Case Statements |
| 3 | [🥑 Foodie-Fi](#3--foodie-fi) | Subscriptions, Window Functions, Date Logic |
| 4 | [🏦 Data Bank](#4--data-bank) | Customer Metrics, Window Functions |
| 5 | [🛒 Data Mart](#5--data-mart) | Data Cleansing, Before & After Analysis |
| 6 | [🐟 Clique Bait](#6--clique-bait) | Funnel Analysis, Product Analytics |
| 7 | [👚 Balanced Tree](#7--balanced-tree) | Revenue Analysis, Transactions |
| 8 | [🔍 Fresh Segments](#8--fresh-segments) | Interest Metrics, Data Exploration |

---

## 🗂️ Case Studies

### 1. 🍜 Danny's Diner
**Folder:** [Case Study #1 - Danny's Diner](https://github.com/udayvimal/8-Week-SQL-Challenge/tree/main/Case%20Study%20%231%20-%20Danny's%20Diner)

Danny's Diner is a small restaurant that wants to understand its customers' visiting patterns, spending habits, and favourite menu items. The goal is to use the data to make informed decisions about expanding the loyalty programme.

**Key skills:** `JOIN`, `GROUP BY`, `SUM`, `COUNT`, `DENSE_RANK()`, CTEs, `CASE` statements

---

### 2. 🍕 Pizza Runner
**Folder:** [Case Study #2 - Pizza Runner](https://github.com/udayvimal/8-Week-SQL-Challenge/tree/main/Case%20Study%20%232%20-%20Pizza%20Runner)

Pizza Runner involves cleaning messy order data and analysing delivery metrics, runner performance, and ingredient optimisation for a pizza delivery startup.

**Key skills:** Data cleaning, `TRIM`, `NULLIF`, `CASE`, `DATEPART`, `JOIN`, string manipulation

---

### 3. 🥑 Foodie-Fi
**Folder:** [Case Study #3 - Foodie-Fi](https://github.com/udayvimal/8-Week-SQL-Challenge/tree/main/Case%20Study%20%233%20-%20Foodie-Fi)

Foodie-Fi is a subscription-based streaming service for food content. This case study analyses subscription plans, churn behaviour, and customer journey using time-series data.

**Key skills:** `LEAD()`, `LAG()`, `ROW_NUMBER()`, date arithmetic, churn analysis, subscription analytics

---

### 4. 🏦 Data Bank
**Folder:** [Case Study #4 - Data Bank](https://github.com/udayvimal/8-Week-SQL-Challenge/tree/main/Case%20Study%20%234%20-%20Data%20Bank)

Data Bank is a digital bank that links customer cloud storage limits to their account balances. This case study covers customer node distribution, transaction analysis, and closing balance calculations.

**Key skills:** `SUM() OVER()`, `GENERATE_SERIES`, `COALESCE`, window frames, closing balance logic

---

### 5. 🛒 Data Mart
**Folder:** [Case Study #5 - Data Mart](https://github.com/udayvimal/8-Week-SQL-Challenge/tree/main/Case%20Study%20%235%20-%20Data%20Mart)

Data Mart is an online supermarket that introduced sustainable packaging. This case study measures the sales impact of that change using before-and-after analysis across multiple dimensions.

**Key skills:** `TO_DATE`, `DATE_PART`, `WIDTH_BUCKET`, before & after analysis, `CASE` segmentation

---

### 6. 🐟 Clique Bait
**Folder:** [Case Study #6 - Clique Bait](https://github.com/udayvimal/8-Week-SQL-Challenge/tree/main/Case%20Study%20%236%20-%20Clique%20Bait)

Clique Bait is an online seafood store. This case study dives into digital analytics — analysing page views, cart adds, purchase funnels, and campaign performance.

**Key skills:** `STRING_AGG`, funnel analysis, `LEFT JOIN`, product analytics, campaign attribution

---

### 7. 👚 Balanced Tree
**Folder:** [Case Study #7 - Balanced Tree Clothing Co](https://github.com/udayvimal/8-Week-SQL-Challenge/tree/main/Case%20Study%20%237%20-%20Balanced%20Tree%20Clothing%20Co)

Balanced Tree Clothing Company needs a financial report covering total revenue, discounts, segment performance, and transaction penetration rates across its product range.

**Key skills:** `PERCENTILE_CONT`, revenue analysis, `RANK()`, product segmentation, transaction metrics

---

### 8. 🔍 Fresh Segments
**Folder:** Case Study #8 - Fresh Segments *(coming soon)*

Fresh Segments is a digital marketing agency that analyses customer interest metrics and audience composition to help clients understand their customer base.

**Key skills:** Interest analysis, data exploration, percentile calculations, composition metrics

---

## 🛠️ Tech Stack

| Tool | Usage |
|------|-------|
| **PostgreSQL** | Primary SQL dialect used for all solutions |
| **DB Fiddle** | Online SQL editor used for query testing |
| **Git & GitHub** | Version control and portfolio hosting |

---

## 💡 SQL Skills Demonstrated

- ✅ **Joins** — INNER, LEFT, CROSS joins across multiple tables
- ✅ **CTEs** — Readable multi-step query logic using `WITH` clauses
- ✅ **Window Functions** — `RANK()`, `DENSE_RANK()`, `ROW_NUMBER()`, `LEAD()`, `LAG()`, `SUM() OVER()`
- ✅ **Aggregations** — `SUM`, `COUNT`, `AVG`, `MIN`, `MAX` with `GROUP BY`
- ✅ **Data Cleaning** — Handling NULLs, type casting, string trimming
- ✅ **Date & Time Logic** — `DATE_PART`, `DATE_TRUNC`, `INTERVAL`, `GENERATE_SERIES`
- ✅ **Conditional Logic** — `CASE WHEN`, `COALESCE`, `NULLIF`
- ✅ **Subqueries** — Correlated and non-correlated subqueries
- ✅ **String Functions** — `STRING_AGG`, `TRIM`, `REGEXP_SPLIT_TO_TABLE`
- ✅ **Business Analysis** — Churn, retention, funnel, revenue, and before/after analysis

---

## 🚀 How to Use

1. Clone the repo:
   ```bash
   git clone https://github.com/udayvimal/8-Week-SQL-Challenge.git
   ```
2. Navigate to any case study folder and open the `README.md` for the full solution with SQL queries and answers.
3. Copy queries into [DB Fiddle](https://www.db-fiddle.com/) or any PostgreSQL environment to run them.

---

*Solutions written and documented by **[udayvimal](https://github.com/udayvimal)***
