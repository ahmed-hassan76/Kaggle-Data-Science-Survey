# Kaggle-Data-Science-Survey
# 📊 Elevvo Task 4: Data Cleaning & Insight Generation from Survey Data

This project is part of the **Elevvo Data Analytics Track**, focusing on real-world data preparation and insight generation using a large-scale survey dataset from Kaggle’s Data Science & Machine Learning Survey (2017–2021).

## 📝 Objective

To clean, prepare, and extract meaningful insights from messy survey data, especially focusing on how data professionals interact with programming languages.

---

## 📂 Dataset

- **Rows:** 10,000+
- **Features:** Multi-part survey responses, respondent roles, experience, and tool usage.

---

## 🔧 Project Workflow

### 1. **Data Cleaning**
- Merged multi-part responses for programming language usage.
- Removed duplicates and cleaned text data.
- Handled missing values and inconsistent formatting.
- Applied binary encoding to language columns (`Q7_Part_1` to `Q7_Part_12` + `Q7_OTHER`).

### 2. **Exploratory Data Analysis**
Used `pandas`, `seaborn`, and `matplotlib` to explore key trends:

#### 🔍 Key Insights:
- **Top 5 Programming Languages** used by respondents.
- **Number of languages known per respondent.**
- **Language usage trends** by experience level (`Q6`).
- **Top 5 job titles** (`Q5`) in the dataset.
- **Preferred languages among Data Scientists**.

---

## 📊 Dashboard

A multi-panel visualization was created to summarize all findings in one view.

> **Tools Used:**  
> - `pandas` for data manipulation  
> - `matplotlib` & `seaborn` for visualization  
> - `Jupyter Notebook` for experimentation  
