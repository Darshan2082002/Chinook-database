# 🎵 Chinook Digital Music Store – SQL & Python Data Analysis

An end-to-end data analysis project connecting Python to the **Chinook SQLite Database** to explore retail music store data. This project utilizes structured SQL queries executed directly within a Jupyter Notebook to answer critical business questions, loading the resulting datasets into Pandas DataFrames for quick exploration and visualization.

Because SQLite runs serverless and requires zero configuration, this project demonstrates an efficient approach to merging standard relational database querying (SQL) with automated Python data pipelines.

---

## 🚀 Project Overview & Requirements

The goal of this analysis is to evaluate business performance indicators for a digital music store across three distinct vectors: track sales popularity, global market revenue distribution, and internal sales team performance.

### Key Business Metrics Answered:
1. **Top Sellers:** Which are the 10 best-selling tracks in the store?
2. **Global Markets:** Which country generates the highest total revenue?
3. **Team Performance:** Who is the top-performing sales support employee?

---

## 🛠️ Tech Stack & Dependencies

The project environment is configured locally using Python and the standard data science ecosystem:

* **Data Source:** SQLite (`Chinook_Sqlite.sqlite` downloaded and tracked as `chinook.db`)
* **Environment:** Jupyter Notebook
* **Database Interface:** `sqlite3` (Python Standard Library)
* **Data Manipulation:** `pandas`
* **Data Visualization:** `matplotlib`

---

## 📁 Repository Directory Structure

To keep the repository clean and optimized for GitHub, raw database files and local notebook cache states are explicitly ignored using a `.gitignore` configuration.

```text
chinook-sql-analysis/
│
├── 📓 chinook_analysis.ipynb   # Main Jupyter Notebook containing all queries & plots
├── 📝 README.md                # Project documentation and setup guide
└── 📄 .gitignore               # Excludes raw data (chinook.db) from version control