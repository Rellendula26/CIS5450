# CIS 5450 — Big Data Analytics

Coursework, projects, and applied machine learning pipelines developed for **CIS 5450: Big Data Analytics** at the University of Pennsylvania.

This repository explores large-scale data processing, statistical modeling, distributed computation concepts, and machine learning workflows using tools such as **Pandas, DuckDB, SQL, Scikit-learn, XGBoost, PCA, and Spark-inspired paradigms**. The assignments emphasize both the theoretical foundations of scalable analytics and their practical implementation on real-world datasets.

---

## Topics Explored

- Large-scale data processing and analytics
- SQL-based querying with DuckDB
- Data wrangling and transformation with Pandas
- Feature engineering and preprocessing pipelines
- Dimensionality reduction using PCA and IncrementalPCA
- Supervised machine learning models
- Ensemble learning methods:
  - Decision Trees
  - Random Forests
  - XGBoost
- Model evaluation using:
  - Cross-validation
  - ROC AUC
  - Statistical hypothesis testing
  - Bootstrapping and permutation testing
- Distributed systems concepts:
  - MapReduce
  - Spark-style computation
  - Parallelized data workflows
- Efficient parquet-based data storage and querying

---

## Technical Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- DuckDB
- PyArrow
- Matplotlib
- Jupyter Notebook

---

## Repository Structure

```bash
.
├── homework1.ipynb
├── homework2.ipynb
├── homework3.ipynb
├── homework4.ipynb
└── README.md
```

Each notebook focuses on different aspects of scalable analytics, machine learning experimentation, and data engineering workflows.

---

## Highlights

- Built end-to-end machine learning pipelines for structured and large-scale datasets
- Applied ensemble learning techniques to improve predictive performance and reduce variance
- Implemented PCA-based dimensionality reduction workflows on high-dimensional datasets
- Used DuckDB and parquet files for efficient analytical querying over large datasets
- Evaluated model performance using statistically rigorous validation techniques
- Explored the tradeoffs between scalability, interpretability, and computational efficiency in modern data systems

---

## Example Concepts Covered

### Ensemble Learning

Compared interpretable nonlinear baselines such as Decision Trees with variance-reducing bagging methods like Random Forests and sequential boosting methods such as XGBoost.

### Statistical Evaluation

Used repeated sampling, bootstrapping, and permutation-based hypothesis testing to determine whether observed model improvements were statistically significant.

### Scalable Data Pipelines

Worked with parquet-backed datasets and incremental batch processing techniques to simulate real-world large-scale machine learning workflows.

---

## About

This repository reflects my work in applying scalable data analytics and machine learning techniques to practical problems while developing a deeper understanding of modern data systems and computational tradeoffs.
