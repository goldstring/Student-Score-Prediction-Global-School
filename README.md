# 🎓 Predicting Student Exam Performance at Global School

## 📌 Problem Statement

**Predicting Student Exam Performance at Global School**

---

## 🏫 Background

Global School is committed to enhancing student academic outcomes by understanding the key factors that influence overall exam performance. With access to data on student behavior, health, and support systems, the school aims to develop a data-driven strategy to support students who are likely to underperform and tailor interventions to improve outcomes.

---

## 🎯 Objective

The objective is to build a **regression model** that can accurately predict the **average exam score** of a student based on various influencing factors such as study habits, attendance, sleep hours, health status, motivation level, and parental support.

---

## 📊 Dataset Description

The dataset includes **2,000 anonymized student records** from Global School with the following features:

| Feature               | Description                                      |
|-----------------------|--------------------------------------------------|
| `Student_ID`          | Unique student identifier                        |
| `Gender`              | Gender of the student                            |
| `Study_Time_Hours`    | Average study time per day (in hours)            |
| `Attendance_Percent`  | Class attendance percentage                      |
| `Sleep_Hours`         | Average hours of sleep per day                   |
| `Parental_Education`  | Highest education level of parents               |
| `Study_Habits`        | Study behavior rating (scale or categorical)     |
| `Access_To_Resources` | Access to study material and digital resources   |
| `Health_Status`       | Self-reported health condition                   |
| `Part_Time_Work`      | Whether the student has a part-time job          |
| `Extra_Tuition`       | Attending additional tuition classes (Yes/No)    |
| `Motivation_Level`    | Motivation level score (1–10 scale)              |
| `Parental_Support`    | Level of support from parents (scale or flag)    |
| `Avg_Exam_Score`      | **Target** – Average exam score (%)              |

---

## 💼 Business Use Case

By accurately predicting student performance, Global School can:

- ✅ Identify students at risk of underperforming early in the academic year  
- 🎯 Personalize support such as extra tuition or mentoring  
- 📣 Inform parents and educators about key non-academic factors affecting outcomes  
- 📌 Prioritize interventions where they'll be most effective  

---

## 🧠 Problem Type

**Supervised Learning – Regression**

---

## 🎯 Target Variable

`Avg_Exam_Score` (continuous numeric value representing a student's average exam score)

---

## 🛠️ Tools & Techniques (Optional - To Add Later)

- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- Regression Algorithms (Linear Regression, Random Forest, XGBoost)
- Model Evaluation (MAE, RMSE, R² Score)

---

## 📌 License

This dataset is synthetic and intended for educational and research purposes only.
