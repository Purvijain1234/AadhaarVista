# 🆔 AadhaarVista  
## Aadhaar Enrolment & Update Intelligence  
### UIDAI Data Hackathon 2026

---

## 📌 About the Project

**AadhaarVista** is a data analytics and visualization project developed for the **UIDAI Data Hackathon 2026** under the **Data Analytics & Visualization** track.

The project analyzes large-scale **Aadhaar enrolment**, **demographic update**, and **biometric update** datasets to understand **national, state-level, and district-level patterns** in Aadhaar service activity. As Aadhaar enrolment in India has reached maturity, the project focuses on **update dynamics and operational pressure**, rather than only new enrolments.

### The solution combines:
- Exploratory Data Analysis (EDA) using Python  
- Time series analysis & short-term forecasting  
- An interactive **Power BI dashboard** for KPI-driven insights  

---

## 🎯 Problem Context

With near-universal Aadhaar coverage, UIDAI operations are increasingly driven by:
- Demographic updates (address, personal details)  
- Biometric updates (re-verification, age-related changes)  

However, raw datasets alone do not provide:
- Clear regional comparisons  
- Update pressure visibility  
- Temporal trend understanding  

**AadhaarVista** addresses this gap by transforming raw UIDAI data into an **interpretable, decision-support analytics system**.

---

## 📊 Dataset Description

The datasets are provided by **UIDAI** exclusively for the **UIDAI Data Hackathon 2026** and are fully anonymized.

### 📁 Dataset Categories
- Aadhaar Enrolment Data  
- Aadhaar Demographic Update Data  
- Aadhaar Biometric Update Data  

### ⏱ Time Period
- **01 April 2025 – 31 December 2025**

### 📍 Granularity
- State-level  
- District-level  

### 🔑 Key Fields
- Date  
- State, District, Pincode  
- Age-group-wise enrolment counts  
- Age-group-wise demographic & biometric update counts  

> ⚠️ No personally identifiable information (PII) is used.

---

## 🧪 Exploratory Data Analysis (EDA)

EDA is performed using **Python (Jupyter Notebook)** to understand:
- Age-wise enrolment distribution (0–5, 5–17, 18+)  
- Regional disparities across states and districts  
- Correlations between age-group enrolments  
- Temporal enrolment behaviour  

### Key EDA Techniques
- Data cleaning & merging of large CSV files  
- Monthly and quarterly aggregation  
- Correlation analysis using heatmaps  
- State-wise & district-wise comparisons  
- Heatmap-based regional trend analysis  

📓 **Notebook:** `Uidai_eda.ipynb`

---

## ⏳ Time Series Analysis & Forecasting

To analyze temporal behaviour:
- Daily data is aggregated to monthly level  
- Trend analysis is performed for Aadhaar enrolments (18+ age group)  
- Linear regression–based short-term forecasting is applied  

📌 Forecasting is used **only for exploratory trend interpretation**, not long-term prediction.

---

## 📈 Power BI Dashboard

An interactive **Power BI dashboard** translates analytical insights into actionable KPIs and visuals.

### 🔑 Key KPIs
- **Total Aadhaar Enrolments:** ~5 Million  
- **Total Demographic Updates:** ~49 Million  
- **Total Biometric Updates:** ~70 Million  
- **Update Pressure Ratio:** **21.90**

These KPIs clearly show that **update activities far exceed new enrolments**, highlighting the operational shift toward Aadhaar lifecycle management.

### 📊 Dashboard

📌 The dashboard enables **interactive exploration across states, districts, and time periods**.

---

## 📄 Documentation

A detailed project report is included, covering:
- Background & problem definition  
- Dataset structure and integration  
- Data preprocessing methodology  
- EDA findings  
- Dashboard design & KPI interpretation  
- Results, outcomes, and future scope  

📁 Available in the **`docs/`** folder.

---

## 🔍 Key Insights

- Aadhaar enrolments for **children (0–5 age group)** form the largest share of new enrolments  
- Aadhaar activity varies significantly across states and districts  
- Strong positive correlation exists across age-group enrolment patterns  
- Update pressure is consistently higher than enrolment volume  
- Aadhaar service demand is increasingly driven by **biometric and demographic updates**

---

## 🛠 Tech Stack

- **Python** (Pandas, ScikitLearn, Matplotlib, Seaborn)  
- **Jupyter Notebook**  
- **Microsoft Power BI**  

---

## 🏁 Hackathon Details

- **Hackathon:** UIDAI Data Hackathon 2026  
- **Track:** Data Analytics & Visualization  
- **Project Type:** EDA + Power BI Dashboard  
- **Project Name:** AadhaarVista  

---


## 👩‍💻 Author

**Purvi Jain**  
B.Tech (Artificial Intelligence)  
LinkedIn: linkedin.com/in/purvi-jain-315683326

---


📌 *This repository is part of the **UIDAI Data Hackathon 2026** submission.*
