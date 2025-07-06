# BIG DATA ANALYSIS
*COMPANY* : CODTECH IT SOLUTION

*NAME*: VAISHNAVI SUDHIR SANSARE

*INTERN ID*: CITS0D56

*DOMAIN*: DATA ANALYTICS

*DURATION* : 4 WEEKS

*MENTOR*: NEELA SANTOSH

This project demonstrates **scalable big data processing and analysis** using **Apache Spark (PySpark)** on a real-world Netflix dataset. The goal is to showcase how to handle large datasets, perform robust data cleaning, and extract valuable insights efficiently.

---

## Dataset

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

## Objectives

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

##  Tools & Technologies

- **Apache Spark (PySpark)** – for distributed big data processing.
- **Python** – as the main programming language.
- **Jupyter Notebook** – for interactive analysis and visual exploration.
---

## Key Steps

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

<img width="1429" height="865" alt="Image" src="https://github.com/user-attachments/assets/596e2e4e-84dd-4271-aef6-8fcbf055c655" />
<img width="1424" height="864" alt="Image" src="https://github.com/user-attachments/assets/f52a5a58-53d7-4a4c-bcd0-dc731525ee94" />
<img width="1420" height="865" alt="Image" src="https://github.com/user-attachments/assets/12503613-a09a-4665-a36e-c052c6e8233d" />
<img width="1441" height="869" alt="Image" src="https://github.com/user-attachments/assets/e9445455-4d1f-4d15-b3e4-054157f62f1d" />
<img width="1451" height="814" alt="Image" src="https://github.com/user-attachments/assets/2a40239e-8266-46a0-b9f6-679f58b81398" />

