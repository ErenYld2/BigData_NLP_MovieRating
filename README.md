MovieLens Big Data Analysis & Movie Recommendation System 🚀

This project focuses on big data analysis, text preprocessing, and a collaborative filtering-based movie recommendation system built on top of the MovieLens dataset. 
It implements the Alternating Least Squares (ALS) algorithm using the Apache Spark (PySpark) ecosystem to handle large-scale data efficiently.

---

📌 Project Overview

* Big Data Processing: Implemented robust and optimized data manipulation operations on massive MovieLens data files (ratings, metadata, keywords) using PySpark's `SparkSession`.
* Data Cleaning & Engineering: Handled missing values, checked schemas, and filtered outdated or corrupt entries across multi-table datasets.
* Statistical Analysis: Converted Unix timestamps to readable ISO formats to track data timeline distributions (ranging from 1995 to 2016).
* Data Visualization: Generated localized exploratory data analysis (EDA) plots including "Rating Distributions" and historical histograms of "Film Counts per Release Year" using `matplotlib` and `pandas`.
* Machine Learning (ALS Model): Trained an industrial-standard recommendation engine via PySpark MLlib’s ALS (Alternating Least Squares) matrix factorization.
* The model learns latent factors to predict how a user would rate an unseen movie.

---

## 🛠️ Technologies Used

* Core Language: Python.
* Big Data Engine: Apache Spark (PySpark SQL & PySpark MLlib).
* Data Manipulation: Pandas, NumPy.
* Plotting & Visualization: Matplotlib.
* Environment Handler: findspark, Jupyter Notebook.

---

🚀 How to Run

1. Prerequisites
Make sure you have Java (JDK), Apache Spark, and Hadoop binaries correctly installed and configured in your local environment variables.

2. Clone the Repository
```bash
git clone [https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git](https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git)
cd YOUR-REPO-NAME
