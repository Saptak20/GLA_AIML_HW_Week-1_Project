# 🛒 Week 1 - E-commerce EDA Scenario Challenge

## 📌 Overview

This repository contains my submission for the **Week 1 Data Science Assignment**, focused on **Exploratory Data Analysis (EDA)** and **Feature Engineering** using a large-scale e-commerce dataset.

The objective of this assignment is to analyze the dataset, identify important business insights, investigate data quality issues, and prepare the data for future machine learning models.

---

## 📂 Repository Structure

```text
├── customer-churn-prediction.ipynb    # Jupyter Notebook containing EDA and preprocessing
├── ecommerce_500k.csv                 # Dataset used for analysis
├── answers.pdf                        # Written answers to all assignment questions
└── README.md                          # Project documentation
```

---

## 📊 Dataset Information

* **Dataset:** E-commerce Transactions
* **Rows:** 500,000
* **Columns:** 30
* **Target Variable:** `is_returned`

The dataset contains customer information, product details, pricing, discounts, shipping information, loyalty tiers, session metrics, and return status.

---

# ✅ Assignment Tasks Completed

## Phase 1 – Data Audit

* Loaded and inspected the dataset
* Analyzed data types
* Checked missing values
* Verified duplicate records
* Generated descriptive statistics

## Phase 2 – Pricing Distribution Analysis

* Visualized pricing columns
* Measured skewness
* Identified positively skewed distributions

## Phase 3 – Categorical Feature Analysis

* Identified categorical variables
* Examined cardinality
* Determined suitable encoding strategies

## Phase 4 – Return Pattern Analysis

* Explored product return behavior
* Investigated business factors affecting returns
* Analyzed relationships between customer and transaction features

## Phase 5 – Feature Engineering

Built preprocessing pipelines using:

* Median imputation
* Standard Scaling
* Robust Scaling
* One-Hot Encoding
* Ordinal Encoding
* `ColumnTransformer`

## Phase 6 – Correlation Analysis

* Examined relationships among numerical features
* Identified potentially predictive variables
* Investigated multicollinearity

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook

---

## 🚀 Key Learning Outcomes

* Exploratory Data Analysis (EDA)
* Data Cleaning
* Missing Value Handling
* Feature Engineering
* Encoding Categorical Variables
* Data Scaling
* Correlation Analysis
* Building Machine Learning Preprocessing Pipelines

---
