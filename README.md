📊 DSA 210 Term Project
Understanding How Lifestyle & Fitness Metrics Influence Study Motivation


🧩 1. Project Overview
This project aims to examine how various health and lifestyle factors — including daily physical activity, calorie expenditure, heart rate patterns, sleep quality, and gym activity — influence a student’s daily study motivation.
Modern wearable devices (Apple Watch, Fitbit, Garmin, etc.) continuously track key physiological and behavioral metrics that reflect a person's overall well-being. Since physical health, sleep quality, and exercise habits are strongly connected to mood, cognitive performance, and motivation, this project investigates whether these measurable signals can help explain or predict daily fluctuations in study motivation.
The goal is to explore whether healthier daily routines and better physical metrics correspond to higher academic motivation levels.


🗂️ 2. Data Overview & Collection Methods
This project uses a multi-source dataset representing different dimensions of lifestyle health and activity.
The dataset includes daily self-logged values combined with wearable-device style metrics that can either be collected manually or simulated for analysis.
Dataset	Description	Collection Method
Daily Activity Data	Total steps, active minutes, movement intensity. Reflects overall physical movement.	Manually recorded or obtained from a wearable device (Apple Health / Google Fit exports).
Calorie Expenditure Data	Total calories burned per day (active + basal). Represents daily physical load.	Wearable device export or manually logged estimates.
Heart Rate Data	Resting HR, average HR, and peak HR during the day. Indicates stress, fitness level, and physical state.	Apple Watch, Fitbit, or manual approximation.
Sleep Quality Data	Total sleep time, deep sleep minutes, sleep efficiency, sleep satisfaction score.	Wearable device sleep data or self-reported values.
Gym Activity Data	Whether the gym was attended that day, workout duration, intensity rating (1–10).	Self-logged data.
Study Motivation	Daily study motivation score (1–10 scale), self-reported each day.	Logged through daily self-tracking.
All datasets are recorded for the same timeline (e.g., 30–60 days) to allow daily-level correlation and regression analysis.


🎯 3. Research Question
“To what extent do daily activity level, calorie expenditure, heart rate, sleep quality, and gym activity impact and explain daily study motivation?”
This question aims to identify which physiological and lifestyle factors are the most influential predictors of motivation to study.


📐 4. Hypotheses
Null Hypothesis (H₀):
Daily activity, calorie expenditure, heart rate, sleep quality, and gym activity have no significant effect on daily study motivation.
Alternative Hypothesis (H₁):
Daily activity, calorie expenditure, heart rate, sleep quality, and gym activity have a significant effect on daily study motivation.
(Multiple regression and correlation analysis will be used to test these.)


💪 5. Motivation
There are several reasons behind choosing this topic:
I actively track my fitness and daily health metrics, making this project directly relevant to my personal life.
Study motivation fluctuates a lot, and I want to understand whether physical health metrics explain these fluctuations.
Modern students often struggle with balancing gym, daily activity, sleep, and study routines — this project can reveal practical insights.
Health, sleep, and exercise have strong theoretical links with discipline, mood, and cognitive ability.
I aim to analyze whether better lifestyle habits genuinely improve my study motivation or whether the relationship is more complex.
By analyzing these metrics together, I hope to identify which daily habits contribute most to staying motivated academically.


⚙️ 6. Data Preparation and Analysis Plan
Once all datasets are cleaned and aligned on the same date index, the following steps will be taken:
1. Exploratory Data Analysis (EDA)
Descriptive statistics for each variable.
Correlation matrix to examine relationships between lifestyle variables and study motivation.
Visualization techniques:
Line charts (daily trends),
Scatter plots (relationship patterns),
Histograms (distribution),
Heatmaps (correlations).
This helps identify initial patterns such as:
Does better sleep correlate with higher motivation?
Does resting HR signal stress → lower motivation?
Are gym days usually high motivation days?
2. Modeling and Statistical Testing
The following models and hypothesis tests will be applied:
• Multiple Linear Regression
StudyMotivation ~ (DailyActivity + Calories + HeartRate + SleepQuality + GymActivity)
This will reveal which variables significantly predict motivation and how strong each effect is.
• Hypothesis Testing
t-tests (gym day vs non-gym day motivation)
ANOVA (sleep quality groups vs motivation)
Correlation significance tests
• Feature Importance (Optional ML Models)
Random Forest / Decision Tree to identify which features are most influential.


📈 7. Possible Outcomes
After completing the analysis, possible results include:
Positive correlations: Better sleep quality, gym attendance, and high activity days may strongly increase motivation.
Negative correlations: High resting heart rate (stress) or low sleep may reduce motivation.
Regression models may show that sleep or gym habits explain more motivation variance compared to activity or calories.
Machine learning models might identify sleep quality or workout consistency as the strongest predictors.
Or, lifestyle factors may have less influence than expected — showing that study motivation is more psychological than physical.
All outcomes are valuable and meaningful.


⚠️ 8. Limitations
Self-reported motivation and sleep satisfaction may include bias.
Wearable device data can fluctuate due to measurement errors.
Short time periods may limit statistical significance.
External factors (stress from exams, deadlines, social life) are not included but may affect motivation.
Heart rate may be affected by caffeine intake, illness, or unrelated stress factors.


🔮 9. Future Work
Incorporate additional variables such as mood tracking, diet quality, screen time, or caffeine consumption.
Use longer time windows (3–6 months) for stronger statistical power.
Build a predictive app or dashboard to estimate tomorrow’s study motivation score.
Compare periods with consistent gym habits vs inconsistent ones.


⏱️ Project Timeline
Date	Task Description
31 October	Submit project proposal via GitHub (README containing topic, data plan, hypotheses).
30 November	Collect and preprocess lifestyle data, clean dataset, conduct EDA.
02 January	Apply regression and machine learning models.
09 January (23:59)	Final report + notebook submission.
