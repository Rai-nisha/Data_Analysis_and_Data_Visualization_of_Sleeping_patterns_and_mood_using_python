# Data_Analysis_and_Data_Visualization_of_Sleeping_patterns_and_mood_using_python
Sleep &amp; Mood Analysis project using Exploratory Data Analysis (EDA) and correlation techniques to examine how sleep duration, screen exposure, and bedtime habits impact sleep quality, mood, and overall sleep hygiene.

# 💤 Sleep Patterns & Mood Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-orange?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-blue?logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-green)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-teal)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)

---

## 📌 Project Overview

This project performs end-to-end **Exploratory Data Analysis (EDA)** and **multivariate correlation analysis** on sleep behavior data to understand how sleep duration, screen exposure, and bedtime habits impact sleep quality and emotional well-being.

The objective is to identify behavioral predictors of **Poor Sleep Hygiene** and generate data-driven insights.

---

## 🎯 Objectives

- Analyze sleep duration distribution
- Examine relationship between sleep duration and mood rating
- Measure impact of screen exposure before bedtime
- Identify strongest contributors to poor sleep hygiene
- Perform correlation and feature influence analysis

---

## 📂 Dataset Features

The dataset includes survey-based behavioral attributes such as:

- Sleep Duration  
- Bedtime Range  
- Mood Rating  
- Morning Refresh Score  
- Difficulty Falling Asleep  
- Sleep Aids Usage  
- Daily Nap Count  
- Pre-Sleep Screen Time Category  

---

## 🧹 Data Preprocessing

- Handled missing and inconsistent values  
- Standardized categorical labels  
- Converted categorical variables to numerical format  
- Removed redundant features  
- Validated data types  

---

## ⚙️ Feature Engineering

Created derived features to quantify sleep behavior:

- **Sleep_Hours**
- **Sleep_Quality_Score**
- **Insufficient_Sleep** (Sleep < 6 hours)
- **High_Screen_Exposure**
- **Bedtime_Category**
- **Poor_Sleep_Hygiene** (Combined behavioral risk indicator)

---

## 📊 Exploratory Data Analysis

### 🔹 Univariate Analysis
- Sleep duration distribution
- Bedtime pattern distribution
- Screen exposure distribution
- Mood rating distribution

### 🔹 Bivariate Analysis
- Sleep Duration vs Mood Rating
- Sleep Duration vs Sleep Quality
- Screen Exposure vs Sleep Quality
- Bedtime Category vs Mood Rating

### 🔹 Multivariate Analysis
- Pearson Correlation Matrix
- Correlation Heatmap
- Feature Influence on Poor Sleep Hygiene
- Behavioral interaction analysis

---

## 📈 Key Insights

- Majority of respondents sleep **6–8 hours**
- Strong positive correlation between **Sleep Hours and Sleep Quality Score**
- Moderate positive correlation between **Sleep Hours and Mood Rating**
- High screen exposure slightly reduces sleep quality
- Early bedtime habits are associated with better mood
- **Insufficient Sleep** and **Difficulty Falling Asleep** are strongest predictors of Poor Sleep Hygiene

---

## 📊 Sample Visualizations

> (Place your generated images inside the `visualizations/` folder)
