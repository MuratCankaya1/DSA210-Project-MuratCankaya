#  Personal Fitness & Energy Analytics Using Huawei Watch Data

## 1. Motivation
With the rise of wearable technology, individuals can monitor their health through real-time biometric data.  
This project aims to explore how **daily activity, calorie expenditure, heart rate, and sleep quality** impact my **energy levels and gym performance**.  
By analyzing data collected from my Huawei Watch, I will investigate which factors most affect daily performance — such as whether better sleep or higher calorie burn leads to more effective workouts.

---

## 2. Data Source
The dataset will be **self-collected** using my **Huawei Watch** and the **Huawei Health app**.  
Data will be exported manually to `.csv` files using Huawei Health’s export feature.

Each daily record will include:

| Date | Total Steps | Calories Burned (kcal) | Active Time (min) | Workout Type | Duration (min) | Heart Rate (avg) | Max Heart Rate | Sleep Duration (h) | Deep Sleep (h) | Energy Level (1–10) | Mood (1–10) |
|------|--------------|-------------------------|------------------|---------------|----------------|------------------|----------------|--------------------|----------------|---------------------|--------------|

Additional manual data:  
- **Workout Type** (push/pull/legs/cardio)  
- **Energy & Mood** ratings (1–10) through a Google Form

---

## 3. Data Collection Plan
- **Duration:** 4 weeks (Nov 1 – Nov 28)  
- **Frequency:** one record per day  
- **Tools:** Huawei Watch + Huawei Health app + Google Form  
- **Storage:** daily logs merged into one CSV file (`fitness_data.csv`)  

Data will remain private and only used for this academic project.

---

## 4. Planned Analysis
- **Exploratory Data Analysis (EDA):**
  - Correlation analysis between calorie burn, sleep, heart rate, and energy level  
  - Time-series trends and outlier detection  
- **Hypothesis Testing:**  
  - t-test for high-sleep vs low-sleep days  
  - Correlation between heart rate and energy levels  
- **Machine Learning:**  
  - Linear Regression & Random Forest to predict daily energy level  
  - Feature importance to determine main factors affecting performance  

---

## 5. Expected Findings
- Longer sleep duration and higher average heart rate variability are expected to improve energy levels.  
- Overtraining days may correlate with lower mood/energy.  
- Results will help identify an “optimal activity pattern” for better daily performance.

---

## 6. Tools & Libraries
Python, pandas, numpy, matplotlib, seaborn, plotly, scikit-learn, statsmodels  

---
