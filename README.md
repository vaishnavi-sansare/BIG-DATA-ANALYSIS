# Pyspark_netflix_dataset_project
# 📊 Netflix Dataset Big Data Analysis with PySpark

This project demonstrates **scalable big data processing and analysis** using **Apache Spark (PySpark)** on a real-world Netflix dataset. The goal is to showcase how to handle large datasets, perform robust data cleaning, and extract valuable insights efficiently.

---

## 📁 Dataset

- **Source:** [Netflix Movies and TV Shows dataset](https://www.kaggle.com/shivamb/netflix-shows)
- Contains metadata for thousands of Netflix Movies and TV Shows, including:
  - Title
  - Director
  - Cast
  - Country
  - Date added to Netflix
  - Release year
  - Rating
  - Duration
  - Genres (`listed_in`)
  - Description

---

## ✅ Objectives

- Perform **end-to-end data analysis** on a large dataset using PySpark.
- Clean the dataset by:
  - Identifying and handling missing or null values.
  - Using `fillna` and `dropna` strategies for robust preprocessing.
  - Parsing string columns (e.g., extracting numeric durations, parsing `date_added` safely).
- Generate **insights** such as:
  - Distribution of Movies vs TV Shows.
  - Top contributing countries.
  - Most frequent ratings
  - Year-wise trend of new content additions.
  - Average movie durations.
- Demonstrate **scalability** using Spark DataFrames.

---

## ⚙️ Tools & Technologies

- **Apache Spark (PySpark)** – for distributed big data processing.
- **Python** – as the main programming language.
- **Jupyter Notebook** – for interactive analysis and visual exploration.
---

## 🔍 Key Steps

1. **Load** the dataset into a Spark DataFrame.
2. **Inspect** for missing values and data quality issues.
3. **Clean**:
   - Fill missing values with defaults where applicable.
   - Drop rows where critical data is missing.
   - Use `try_to_date` and regex parsing to safely handle dirty string columns.
4. **Analyze**:
   - Use Spark transformations (`groupBy`, `agg`, `withColumn`, `filter`) to extract trends.
   - Derive additional features like numeric duration for movies.
   - Aggregate data for clear insights.
5. **Output**:
   - Display results in the notebook.
   - Optionally, save results to CSV/Parquet for further use.

---

