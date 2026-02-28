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

# 📊 Data Visualizations

## 1️⃣ Sleep Duration Distribution

![Sleep Duration Distribution](visualizations/sleep_duration_distribution.png)

**Insight:** Majority of respondents sleep 6–8 hours, indicating generally healthy sleep patterns.



## 2️⃣ Sleep Duration vs Mood Rating

![Sleep vs Mood](visualizations/sleep_vs_mood.png)

**Insight:** Longer sleep duration is positively associated with higher mood ratings.



## 3️⃣ Correlation Heatmap

![Correlation Heatmap](visualizations/correlation_heatmap.png)

**Insight:** Strong positive correlation between Sleep Hours and Sleep Quality Score. Moderate positive relationship between Sleep Hours and Mood Rating.



## 4️⃣ Feature Influence on Poor Sleep Hygiene

![Feature Influence](visualizations/feature_influence.png)

**Insight:** Insufficient Sleep and Difficulty Falling Asleep are strongest contributors to Poor Sleep Hygiene.

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
