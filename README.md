# 🛠️ Data Preprocessing Pipeline | Machine Learning Workflow

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Scikit-Learn](https://img.shields.io/badge/Library-Scikit--Learn-orange)
![Pandas](https://img.shields.io/badge/Library-Pandas-150458)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📌 Project Overview
This repository contains a complete, step-by-step implementation of a **Data Preprocessing Pipeline** using Python and Scikit-learn. 

Data preprocessing is the critical first step in any Machine Learning project. Real-world data is often incomplete, inconsistent, and lacking in specific behaviors or trends, and is likely to contain many errors. This project demonstrates how to transform raw data into a clean, understandable format suitable for high-performance ML models.

## 🚀 Key Features & Techniques
The notebook covers the following essential preprocessing steps:

1.  **Importing Libraries:** Utilizing `pandas` for data manipulation, `numpy` for numerical operations, and `matplotlib` for visualization.
2.  **Handling Missing Data:**
    -   Implemented `SimpleImputer` (from `sklearn.impute`) to handle missing values using the **Mean Strategy**.
    -   Ensures dataset integrity without discarding valuable rows.
3.  **Encoding Categorical Data:**
    -   **Label Encoding:** Converting the target variable (dependent variable) into numeric form using `LabelEncoder`.
    -   **One-Hot Encoding:** Transforming categorical independent features into binary vectors using `ColumnTransformer` and `OneHotEncoder` to prevent the model from assuming a mathematical order.
4.  **Splitting the Dataset:**
    -   Utilized `train_test_split` to divide the data into **Training** (80%) and **Testing** (20%) sets.
    -   Ensures the model can be evaluated on unseen data to prevent overfitting.
5.  **Feature Scaling:**
    -   Applied **Standardization** (`StandardScaler`) to rescale features to have a mean of 0 and a standard deviation of 1.
    -   Crucial for distance-based algorithms (e.g., K-Means, SVM, KNN) to perform correctly.

## 🛠️ Tech Stack
-   **Language:** Python
-   **Libraries:** -   `pandas`
    -   `numpy`
    -   `scikit-learn`
    -   `matplotlib`

## 📂 Project Structure
