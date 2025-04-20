# 📊 Bellabeat Case Study – Wellness Data Analysis
**Author:** Hassan Raza  
**Date:** April 20, 2025  
**Tools Used:** Python, Pandas, Matplotlib, Seaborn, Jupyter Notebook, Kaggle

---

## 🔍 Step 1: ASK – Business Task

Analyze smart device usage data to gain insight into how consumers use non-Bellabeat smart devices. Apply those insights to help shape Bellabeat’s marketing strategy for one of their products.

### Business Questions:
1. What are some trends in smart device usage?
2. How could these trends apply to Bellabeat customers?
3. How could these trends help influence Bellabeat marketing strategy?

---

## 📦 Step 2: PREPARE – Data Source

**Dataset:** Fitbit Fitness Tracker Data (via Kaggle – Public Domain)  
- 30 user profiles  
- Minute-level & daily metrics  
- Data includes steps, sleep, calories, heart rate, and intensity  
- Time range: 2016–2018

**ROCCC Check:** Reliable ✔️ | Original ✔️ | Comprehensive ✔️ | Current ❌ | Cited ✔️

---

## 🧹 Step 3: PROCESS – Data Cleaning

- Removed duplicates (e.g., 23,424 duplicates in heart rate data)
- Standardized all datetime columns (ActivityDate, SleepDay, etc.)
- Dropped irrelevant or mostly null columns (e.g., 'Fat' in weight log)
- Verified all datasets were cleaned and merged where needed

---

## 📊 Step 4: ANALYZE – Key Insights

### 🏃‍♂️ A. Daily Activity
- **Users:** 35  
- **Avg Steps/day:** 7,280  
- **Only 30.78%** of records hit 10,000+ steps  
- **Correlation (Steps vs Calories):** 0.59  
→ Indicates opportunity for engagement via step challenges

### 😴 B. Sleep Behavior
- **Users:** 24  
- **Avg Sleep:** 7 hrs  
- **Avg Time in Bed:** 7.6 hrs  
- **Avg Sleep Efficiency:** 91.68%  
→ High efficiency, but sleep time could be improved

---

## 📈 Step 5: SHARE – Visualizations

- Histograms for step and sleep distribution
- Scatterplots of steps vs. calories burned
- Boxplots of sleep efficiency

These visualizations support the behavioral patterns discovered through the analysis.

---

## 🔥 Step 6: ACT – Final Recommendations

1. Launch **daily/weekly step challenges** in the Bellabeat app  
2. Use **data visualizations** to link steps with calorie burn  
3. Offer **sleep coaching & mindfulness** content before bed  
4. Target users with **personalized health suggestions**  
5. Increase Bellabeat Membership value with **habit reports & nudges**  

---

### ✅ Outcome:
This case study demonstrates how Bellabeat can use behavioral insights to promote healthy lifestyles and build smarter, data-driven marketing strategies.

---

> © 2025 Hassan Raza | Data Analyst Portfolio Project
