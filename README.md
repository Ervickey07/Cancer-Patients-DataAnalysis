# 🩺 Cancer-Patients-DataAnalysis

**Cancer Patients Data Analysis — Comprehensive EDA & Insights**  
This project performs a complete Exploratory Data Analysis (EDA) on a synthetic dataset of **50,000 cancer patients**, focusing on demographic variables, cancer types, stages, treatment costs, survival metrics, and major lifestyle/genetic risk factors.

The goal is to uncover meaningful insights that help understand **which factors influence cancer severity** and **how early detection varies across cancer types**.

---

## 📊 Project Overview

This analysis explores:

- Patient demographics  
- Cancer type & stage distribution  
- Risk factor patterns  
- Treatment cost variations  
- Relationships between risk factors and severity  
- Early-stage diagnosis rates  
- Correlation analysis (Pearson & Spearman)  

The project uses **Python-based EDA** to convert raw data into actionable insights.

---

## 🛠️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- SciPy (stats)  

---

## 🧹 1. Data Cleaning & Preparation

- Handled missing values  
- Encoded categorical variables  
- Generated statistical summaries  
- Prepared data for analysis and visualization  

---

## 📈 2. Exploratory Data Analysis (EDA)

The study covers:

### ✔ Age Distribution
- KDE plot & Histogram  
- Summary stats (mean age ~54)  
- Revealed a wide 20–89 age range  

### ✔ Gender Distribution
- Bar graph with value labels  
- Shows male–female distribution patterns  

### ✔ Country/Region Distribution
- Pie chart of patient geography  

### ✔ Cancer Type Analysis
- Bar plot with total count per cancer type  

### ✔ Cancer Stage Analysis
- Count of Stage 0 to Stage IV  
- Most patients lie in **Stage I–III**  
- Stage 0 lowest; Stage II highest  

### ✔ Treatment Cost Analysis
- KDE + histogram  
- Median cost ≈ **$52,474**  
- Cost range: **$5,000 to $99,999**  

---

## 🔬 3. Early-Stage Diagnosis Analysis

Measured the proportion of patients diagnosed at **Stage 0 & Stage I** across cancer types.

Results show early detection rates around **38–41%**, meaning:

> **Nearly 60% of patients are diagnosed in later stages (II–IV)**  
indicating poor screening or late symptom reporting.

---

## 🔗 4. Correlation Analysis (Risk Factors vs Severity)

Both **Pearson** and **Spearman** correlations were used to find relationships between:

- Age  
- Genetic Risk  
- Air Pollution  
- Alcohol Use  
- Smoking  
- Obesity  
- Survival Years  
- Target Severity Score  

### **Key Findings**

- **Smoking (≈0.48)** → strong correlation with severity  
- **Genetic Risk (≈0.47)** → strong predictor  
- **Air Pollution (≈0.36)** → moderate correlation  
- **Alcohol Use (≈0.35)** → moderate impact  
- **Obesity (≈0.24)** → weak–moderate  
- **Age → no correlation**  
- **Severity ≠ Survival Years → independent factors**  

These results indicate that **severity depends more on lifestyle & genetic factors**, not age.

---

## 🎯 Project Objective

The aim is to:

- Discover what influences cancer severity  
- Analyze how lifestyle/genetic risks affect outcomes  
- Understand detection patterns across cancer types  
- Support data-driven medical insights and public health awareness  

---


---

## 🧠 Key Insights Summary

- Strongest severity predictors: **Smoking & Genetic Risk**  
- Weakest predictor: **Age**  
- Early-stage diagnosis low across all cancers  
- Median treatment cost around **$52K**  
- Cancer stages mostly concentrated in **Stage I–III**  

---

## 📜 Conclusion

This project provides a deep understanding of cancer patient demographics, risk factors, and disease severity.  
The insights can support **public health research, awareness campaigns, and future predictive modeling work**.

---

## 🤝 Contributions

Feel free to submit issues or pull requests to enhance the project.



