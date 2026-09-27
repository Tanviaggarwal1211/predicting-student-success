# Predicting-student-success
Data-driven exploration of student performance, providing actionable insights into how environmental and academic factors influence final outcomes.

# Student Performance Analysis

**Predicting student exam scores and analyzing key drivers of academic success using machine learning.**

## Project Overview
This repository contains an end-to-end data science project focused on identifying the primary factors that influence student academic performance. By analyzing demographic, behavioral, and academic data, this project uncovers actionable insights into what drives student success and utilizes machine learning to predict final exam scores.

## Dataset Description
The analysis is based on the **Student Performance Factors** dataset. It includes various features that capture a holistic view of a student's environment and habits:

* **Target Variable:** `Exam_Score` (Continuous)
* **Key Features:**
  * **Academic Metrics:** `Hours_Studied`, `Attendance`, `Previous_Scores`, `Tutoring_Sessions`
  * **Environment & Habits:** `Sleep_Hours`, `Extracurricular_Activities`, `Internet_Access`, `Access_to_Resources`, `Physical_Activity`
  * **Background Factors:** `Family_Income`, `Parental_Involvement`, `Parental_Education_Level`, `Distance_from_Home`

## Tech Stack
* **Language:** Python
* **Data Manipulation & Analysis:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn, Tableau
* **Machine Learning:** Scikit-Learn, XGBoost
* **Environment:** Jupyter Notebook / Google Colab

## Methodology & Approach
1. **Exploratory Data Analysis (EDA):** Investigated data distributions, handled missing values, and evaluated feature correlations (such as the linear relationship between `Attendance`, `Hours_Studied`, and `Exam_Score`).
2. **Feature Engineering & Preprocessing:** Encoded categorical features, normalized/scaled continuous variables, and partitioned data into training and test sets.
3. **Predictive Modeling:** Trained and evaluated multiple models (including tree-based algorithms like Random Forest and XGBoost) to capture non-linear relationships and feature interactions.
4. **Feature Importance & Interpretation:** Extracted feature importance metrics from the top-performing model to determine which variables drive student success.

## Key Findings
* **Top Predictors:** `Attendance` and `Previous_Scores` demonstrated the highest predictive power for final exam outcomes.
* **Study Habits:** Consistent study hours showed a clear positive relationship with exam scores, with diminishing returns beyond peak thresholds.
* **Environmental Impact:** Factors such as `Access_to_Resources` and `Parental_Involvement` served as significant secondary indicators of academic performance.
