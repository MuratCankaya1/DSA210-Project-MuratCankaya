# 📊 DSA 210 Term Project  
# **Understanding How Lifestyle & Fitness Metrics Influence Study Motivation**

---

## 🧩 1. Project Overview

This project aims to examine how various health and lifestyle factors — including daily physical activity, calorie expenditure, heart rate patterns, sleep quality, and gym activity — influence a student’s daily study motivation.

Modern wearable devices (Digital Watch, Fitbit, Garmin, etc.) continuously track key physiological and behavioral metrics that reflect a person's overall well-being. Since physical health, sleep quality, and exercise habits are strongly connected to mood, cognitive performance, and motivation, this project investigates whether these measurable signals can help explain or predict daily fluctuations in study motivation.

The goal is to explore whether healthier daily routines and better physical metrics correspond to higher academic motivation levels.

---

## 🗂️ 2. Data Overview & Collection Methods

This project uses a multi-source dataset representing different dimensions of lifestyle health and activity.  
The dataset includes daily self-logged values combined with wearable-device style metrics.

| **Dataset** | **Description** | **Collection Method** |
|------------|-----------------|------------------------|
| **Daily Activity Data** | Total steps, active minutes, movement intensity. | Apple Health, Google Fit, or manual tracking. |
| **Calorie Expenditure Data** | Total calories burned per day (active + basal). | Wearable export or manual logging. |
| **Heart Rate Data** | Resting HR, average HR, peak HR. | Digital Watch, Fitbit, or manual estimates. |
| **Sleep Quality Data** | Total sleep time, deep sleep, sleep efficiency, satisfaction. | Wearable sleep tracking or self-report. |
| **Gym Activity Data** | Gym attendance, workout duration, intensity (1–10). | Self-logged. |
| **Study Motivation** | Daily 1–10 study motivation score. | Self-logged. |

All datasets cover the same 30–60 day timeline to enable multivariate analysis.

---

## 🎯 3. Research Question

> **To what extent do daily activity level, calorie expenditure, heart rate, sleep quality, and gym activity impact and explain daily study motivation?**

---

## 📐 4. Hypotheses

### **Null Hypothesis (H₀):**  
Daily activity, calorie expenditure, heart rate, sleep quality, and gym activity **have no significant effect** on daily study motivation.

### **Alternative Hypothesis (H₁):**  
Daily activity, calorie expenditure, heart rate, sleep quality, and gym activity **have a significant effect** on daily study motivation.

Regression, correlation, and statistical tests will be used to evaluate these hypotheses.

---

## 💪 5. Motivation

- I actively track my daily fitness metrics, so analyzing them is personally meaningful.  
- Study motivation fluctuates daily, and understanding the reasons may improve academic consistency.  
- Many students struggle to balance sleep, physical activity, and studying — this project can reveal useful insights.  
- Exercise and sleep are strongly linked to mood, motivation, and cognitive performance.  
- I want to identify which lifestyle habits influence my study motivation most.

---

## ⚙️ 6. Data Preparation and Analysis Plan

### **1. Exploratory Data Analysis (EDA)**  
- Descriptive statistics  
- Correlation matrix  
- Visualizations (line charts, scatter plots, histograms, heatmaps)

Questions explored:  
- Does sleep quality correlate with higher motivation?  
- Do gym days correspond to better motivation?  
- Does resting heart rate indicate stress → lower motivation?

### **2. Modeling & Statistical Testing**
- **Multiple Linear Regression:**  
  `StudyMotivation ~ DailyActivity + Calories + HeartRate + SleepQuality + GymActivity`

- **Hypothesis Tests:**  
  - t-test: motivation on gym vs non-gym days  
  - ANOVA: sleep quality groups vs motivation  
  - Correlation significance  

- **Feature Importance (Optional ML):**  
  - Random Forest  
  - Decision Tree  

---

## 📈 7. Possible Outcomes

- Positive correlations: sleep quality, gym consistency, daily activity.  
- Negative correlations: high resting HR (stress), low sleep.  
- Regression may show sleep/gym having biggest impact.  
- ML may identify top predictors (e.g., sleep quality).  
- Or lifestyle may have limited influence → motivation is more psychological.

---

## ⚠️ 8. Limitations

- Self-reported motivation & sleep quality may be biased.  
- Wearable device accuracy may vary.  
- Short time window may reduce statistical power.  
- External factors (stress, exams, mood) are not included.

---

## 🔮 9. Future Work

- Add variables like caffeine intake, mood, screen time, diet.  
- Collect data for 3–6 months.  
- Build a prediction dashboard or app.  
- Compare consistent vs inconsistent gym periods.

---

## ⏱️ Project Timeline

| **Date** | **Task Description** |
|---------|-----------------------|
| 31 October | Submit project proposal (README). |
| 30 November | Data collection, preprocessing, and EDA. |
| 02 January | Apply regression and ML models. |
| 09 January (23:59) | Final report + notebook submission. |

