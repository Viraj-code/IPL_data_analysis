# 🏏 IPL Data Analysis using PySpark

This is a beginner-level data analysis project where I explored Indian Premier League (IPL) cricket datasets using **Apache Spark** and **PySpark**. The main goal of the project was to get hands-on experience with distributed data processing and to understand how Spark handles large-scale structured data.

## 🔧 Technologies Used
- Apache Spark
- PySpark
- Python
- Jupyter Notebook

## 📂 Datasets Used
- `matches.csv`: Contains information about each IPL match (teams, toss, results, etc.)
- `deliveries.csv`: Ball-by-ball delivery-level data for every match

## 🧠 What I Did
As a beginner in Spark, I explored various Spark DataFrame operations and Spark SQL queries. Here’s what I covered:

- Loaded CSV datasets into Spark DataFrames
- Inspected schema and performed basic filtering and selection
- Grouped and aggregated data to find:
  - Most successful teams
  - Top batsmen and bowlers
  - Matches won by batting or fielding first
  - Extra runs given by teams in 2016
  - Most economical bowlers in 2015
- Joined `matches` and `deliveries` data for richer insights
- Wrote basic SQL queries using temporary views in Spark SQL

## 📌 Why I Built This
I'm new to Spark and big data tools, and this project helped me:
- Understand the structure of distributed data
- Practice DataFrame transformations and aggregations
- Explore Spark SQL and window functions
- Apply basic analytics to a real-world sports dataset

## ⚠️ Note
This is an **exploratory project** meant for learning purposes. I'm still in the early stages of learning Spark, so the focus was more on understanding the fundamentals rather than building a production-level pipeline.

## 📷 Screenshots
*(Add images of output tables or spark jobs here if you want)*

## 📁 How to Run
1. Install Jupyter and PySpark
2. Open the notebook: `IPL_DATA_ANALYSIS_SPARK.ipynb`
3. Run cells in order to see the results

---

## 📬 Contact
If you have suggestions, feel free to open an issue or connect with me on [LinkedIn](#)!

