# 🧬 Cancer Data Analysis Project

## 📌 Project Overview

This project focuses on analyzing cancer patient data to extract meaningful insights about patient demographics, treatment outcomes, and survival rates. The goal is to understand patterns that can help in improving early detection and healthcare decision-making.

---

## 👩‍💻 Presented By

**Ankita Kheto**

---

## 🎯 Objective

* Analyze cancer patient dataset
* Identify key factors affecting survival rate
* Understand impact of smoking, BMI, and comorbidities
* Provide data-driven healthcare recommendations

---

## 🛠️ Tools & Technologies Used

* Python 🐍
* Pandas
* NumPy
* Matplotlib / Seaborn
* Jupyter Notebook

---

## 📂 Dataset Information

* **Source:** Kaggle Cancer Dataset
* **Total Rows:** 10,000
* **Total Columns:** 20

### 📊 Columns Include:

* Patient_ID
* Age
* Gender
* Cancer_Type
* Treatment_Type
* Diagnosis_Date
* Smoking_Status
* BMI
* Outcome
* Hospital
* etc.

---

## 🔍 Data Cleaning & Preprocessing

* Converted date columns to datetime format
* Handled missing values using `fillna()`
* Created new columns:

  * Age Category
  * Patient Status (Alive/Dead)
  * BMI
  * Survival Days
  * Diagnosis Year
* Updated "Cause of Death" for alive patients as "Not Applicable"

---

## 📈 Key Analysis Performed

* Survival analysis (Alive vs Dead patients)
* Cancer type distribution
* Stage-wise patient distribution
* Treatment type analysis
* Smoking vs mortality analysis
* Gender & ethnicity distribution
* BMI impact on cancer
* Year-wise trend analysis

---

## 📊 Key Insights

* ✅ Alive patients are higher → Positive survival rate
* 🚬 Smokers have higher mortality rate
* 📉 Advanced stage cancer → Higher death rate
* 🧓 Patients with comorbidities → Higher risk
* ⚖️ BMI impacts cancer risk
* 👩‍⚕️ Early detection improves survival significantly

---

## 💡 Recommendations

* Focus on early cancer detection programs
* Increase awareness about smoking risks
* Monitor high-risk patients (smokers, obese, comorbidities)
* Improve treatment for advanced stages
* Promote healthy lifestyle (diet & exercise)
* Use dashboards for real-time monitoring

---

## 📊 Visualizations

Project includes multiple charts:

* Bar Charts
* Distribution Plots
* Trend Analysis Graphs

---

## 🚀 Conclusion

This project demonstrates how data analytics can help in understanding cancer patterns and improving healthcare decisions. It highlights the importance of early diagnosis and lifestyle factors in survival rates.

---



