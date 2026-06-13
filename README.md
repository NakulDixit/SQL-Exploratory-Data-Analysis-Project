# Structured Exploratory Data Analysis (EDA) in SQL
This project demonstrates a systematic, step-by-step approach to **Exploratory Data Analysis (EDA)** using SQL. Instead of running random queries, this analysis follows a logical sequence to thoroughly understand a dataset from the ground up, moving from database blueprints to rankings.

### Analysis Steps
1. **`01_Database_Exploration.sql` (Database Exploration)**
   * Initial schema blueprinting, table profiling, and row counts to understand the dataset's footprint.
2. **`02_Dimensions_Exploration.sql` (Dimensions Exploration)**
   * Deep dive into categorical data, analyzing high-cardinality fields, distributions, and data quality.
3. **`03_Date_Exploration.sql` (Date Exploration)**
   * Identifying time-based boundaries, and uncovering temporal trends.
4. **`04_Measures_Exploration.sql` (Measures Exploration)**
   * Calculating statistical distributions, averages, min/max boundaries, and summary metrics for numerical data.
5. **`05_Magnitude_Analysis.sql` (Magnitude Analysis)**
   * Identifying outliers, evaluating scale, and isolating the "heavy-hitters" driving the metrics.
6. **`06_Ranking_Analysis.sql` (Ranking & Segmentation)**
   * Leveraging `TOP` and `ORDER BY` clauses to isolate and segment top-performing data points (with bonus examples of SQL Window Functions included as commented-out reference code).

### 🛠️ Tech Stack
* **Language:** SQL
* **Environment:** SQL Server Management Studio (SSMS 22)
* **Database Engine:** Microsoft SQL Server
