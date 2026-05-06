# Data-Analysis-with-Pandas-Fundamentals-in-Banking
Exploratory Data Analysis (EDA) on a Banking Marketing Dataset using Pandas, Pivot Tables, and Data Visualization to analyze customer behavior and term deposit subscriptions.

## Project Overview

This project performs Exploratory Data Analysis (EDA) on a Banking Marketing Dataset using the Pandas framework. The analysis focuses on understanding customer behavior and identifying factors influencing term deposit subscriptions through statistical analysis, pivot tables, and visualizations.

The dataset is based on a real-world Portuguese banking institution marketing campaign from the UCI Machine Learning Repository.

---

## Objectives

The main objectives of this project are:

- Explore and understand banking customer data using Pandas
- Perform data cleaning and preprocessing
- Build pivot tables for deeper business insights
- Visualize customer trends and patterns
- Analyze factors affecting term deposit subscriptions
- Practice real-world banking data analysis workflows

---

## Dataset Information

Source: UCI Machine Learning Repository

Dataset: Bank Marketing Dataset

The dataset contains information collected from direct marketing campaigns conducted by a Portuguese banking institution.

Target Variable:

- `y` → Has the client subscribed to a term deposit?
  - Yes
  - No

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Key Analysis Performed

### 1. Dataset Exploration
- Dataset shape and structure
- Data types inspection
- Missing value analysis
- Statistical summaries

### 2. Exploratory Data Analysis (EDA)
- Customer age distribution
- Job category analysis
- Marital status analysis
- Education level insights
- Loan and credit behavior
- Campaign performance analysis

### 3. Pivot Tables
Built pivot tables to analyze:
- Average age by job category
- Average call duration
- Subscription trends
- Employment type comparisons

### 4. Data Visualization
Created various visualizations including:
- Histograms
- Count plots
- Box plots
- Correlation analysis plots

---

## Business Questions Answered

This project answers several important banking analytics questions such as:

- What percentage of clients subscribed to a term deposit?
- What are the average numerical feature values among subscribed clients?
- What is the average call duration for successful campaigns?
- What is the average age of unmarried subscribed clients?
- How do age and call duration vary across job types?

---

## Key Insights

- Longer call durations generally resulted in higher subscription rates.
- Certain job categories showed better response rates to marketing campaigns.
- Customer demographics such as age and marital status influenced deposit subscriptions.
- Previous campaign outcomes had a strong impact on future success.

---

## Project Structure

```bash
├── banking_analysis.ipynb
├── bank-additional-full.csv
├── README.md
└── images/
