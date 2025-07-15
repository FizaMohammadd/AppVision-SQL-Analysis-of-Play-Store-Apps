# AppVision-SQL-Analysis-of-Play-Store-Apps

---

## 📌 Project Overview

**AppVision** explores app trends, developer behavior, ratings, installs, and more using SQL. The project is built to highlight intermediate-to-advanced SQL skills including joins, CTEs, and window functions.

---

## 📂 Dataset Used

Two CSV files combined:

* `apps.csv` – Contains general app metadata (title, installs, score, ratings, reviews, developer, content rating, etc.)
* `apps_details.csv` – Contains additional details like updated timestamp, version, and Android requirements

### 🔑 Key Columns:

* `title`
* `developer`
* `installs`
* `score`
* `ratings`, `reviews`
* `android_version`, `version`, `size`
* `updated`
* `released`

---

## 🎯 Project Objectives

* Clean and prepare real-world messy data
* Write performant SQL queries to answer meaningful questions
* Practice SQL joins, CTEs, CASE, aggregation, and window functions
* Derive actionable insights from app data

---

## 🧠 Key SQL Concepts Demonstrated

* **INNER JOINs** across multiple tables
* **CTEs** for step-wise logic separation
* **Window functions**: `RANK()`
* **CASE WHEN** logic for bucketing install ranges
* **Aggregate queries**: `COUNT()`, `AVG()`, `MAX()`

---

## 🚀 Features

* Categorized install range bucketing using CASE statements
* App performance scoring by content rating and developer
* Ranking within developer or install group using window functions
* Developer-level insights with review, install, and rating analysis
* Support for real-time analysis after data refresh

---

## 💡 Use Cases

* Analyzing performance of apps based on install counts and ratings
* Identifying under-rated apps with potential
* Understanding developer trends and publishing strategies
* Building dashboards or reports from SQL outputs
* Practicing interview-ready SQL use cases on public data

---

## 📊 Sample Questions Answered

1. &#x20;Find the Top-Rated App Per Category of Install Count
2. Most common content ratings and their average scores
3. Label apps as 'Hit', 'Average', 'Low' based on score
4. Which developers have the most highly-rated apps?
5. Most used Android versions
6. Rank all apps by score within each developer

\>>  More questions and queries inside the SQL folder.

---

## 🧪 Sample Insights

* Some lesser-known developers outperform top brands in app ratings
* Android 4.4 and 5.0 are still supported by many active apps

---

## 🛠 Tech Stack

* **SQL (MySQL 8.0)**
* **Excel** (for data cleaning and conversion)
* **MySQL Workbench**

---

## 🔗 GitHub Repo Usage

* Clone this repo

* Download and extract AppVision_SQL_Project.zip

* Open the extracted folders:

   * Load apps.csv and apps_details.csv into your SQL database

   * /queries/ – contains SQL scripts with corresponding questions in comments

   * /outputs/ – contains result screenshots 

Run queries one by one

Explore and customize insights further!
