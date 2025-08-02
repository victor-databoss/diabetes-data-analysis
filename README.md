## Project Overview
![Average Glucose Chart](images/Average_glucose_chart.png)
This project explores the **pima indians Diabetes dataset** to identify patterns and insights about diabetes risk factos using Python (Pandas, Matplotlib, Seaborn). The analysis includes data cleaning, exploratory data analysis (EDA), and visiualisation.

---

## Dataset
-**Source:**[Kaggle - Pima Indians Diabetes Database](https://www.kaggle.com/diabetes-database)
-**Rows:** 768 patients
-**Columns:** 8 health metrics + Outcome(0 = No Diabetes, 1 = Diabetes)

**Main Features:**
-'Glucose'
-'BloodPressure'
-'BMI'
-'Age'
-'Outcome'

---

## Analysis Questions
1. Calculate **average, minumum, and maximum** for Glucose, BloodPressure, BMI, and Age.
2. Find the **total number of patients**.
3. Count **patients with diabetes** (Outcome = 1).
4. Analyze **distribution of number of pregnancies**.
5. Compare **average Glucose levels** for patients with and without diabetes.
6. Compare **average BMI** for patients with and without diabetes.
7. Calculate **diabetes prevalence by age group**.
8. Compare **Glucose levels visually** between diabetics and non-diabetics.
9. Explore **relationship between Glucose and diabetes**.
10. Summarize **key insights**.

---

## Tech Stack
-**Python**
-**Pandas**
-**Matplotlib**
-**Seaborn**
-**Jupyter Notebook**

---

## Steps Performed
-**Data Cleaning:**
Replaced zero values in Glucose, BloodPressure, BMI with NaN and inputed with mean.
-**Feature Engineering:**
Created Age Groups for better analysis.
-**Exploratory Data Analysis(EDA):**
 Summary  stats, grouped analysis, and visual comparisons.
 -**Visualization:**
 Bar charts, box plot.

## Key Visualizations
![Average Glucose Chart](images/Average_glucose_chart.png)

![Glucose Level Chart](images/Glucose_level_chart.png)


## Key Insights
-Diabetic patients have significantly **higher Glucose** and **BMI**.
-**Age 40+** has the highest diabetes prevalence.
-Glucose has the **strongest correlation** with diabetes outcome.
-High BMI in young patients is an early warning sign.
