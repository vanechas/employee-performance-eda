# 📊 Employee Workplace & Performance Analytics (EDA)

This project focuses on **Data Cleaning** and **Exploratory Data Analysis (EDA)** on employee workplace data to uncover patterns and relationships across productivity, job satisfaction, job roles, departments, and compensation.

---

## 📌 Project Overview

Analyzing employee performance and retention is critical for strategic decision-making in Human Resources (HR). This project covers an end-to-end data science workflow:
1. **Initial Inspection & Deduplication:** Examining dataset structure and removing duplicate/redundant records.
2. **Outlier Detection & Missing Value Imputation:** Using boxplots to detect outliers before deciding on imputation strategies (Mean for normally distributed numericals, Mode for categoricals/discrete years).
3. **Categorical Standardization:** Resolving inconsistent labels across `Gender`, `Department`, and `Position`.
4. **Feature Engineering / Salary Binning:** Grouping continuous `Salary` figures into defined categorical brackets for cleaner visualization and reporting.
5. **Data Visualization & Correlation Analysis:** Analyzing the distribution of numerical features and exploring interactions between productivity, completed projects, gender, and salary.

---

## 📁 Directory Structure

```text
├── dataset/
│   └── dataset aol itds.csv       # Raw employee dataset
├── notebook/
│   └── code aol itds.ipynb        # Comprehensive analysis Jupyter Notebook
├── assets/
│   └── poster aol itds.png        # Infographic / project poster
├── README.md                      # Project documentation
```
