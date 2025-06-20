# 🏥 Power BI Healthcare Analytics: Predicting ER Patient Mortality

---

## 📌 Overview  
Emergency rooms are high-stakes environments where timely and informed decisions are critical. This project applies predictive analytics to ER data to identify high-risk patients, enabling faster, data-driven interventions. The Power BI dashboard visualizes key patient metrics and hospital performance indicators to support clinicians in improving emergency care and reducing mortality rates.

---

## 📋 Executive Summary  
This project leverages historical ER patient data to build a predictive model capable of identifying individuals at risk of mortality based on features such as:

- Age  
- Wait time  
- Infection and readmission rates  
- Patient satisfaction scores  

The resulting Power BI dashboard supports hospital staff in prioritizing patients, optimizing workflows, and making impactful decisions in real time.

---

## 📁 Data Overview  

- **Source:** [Data.world - Hospital ER Dataset](https://data.world/)  
- **File:** `Hospital ER.csv`  
- **Date Range:** 2019 – 2020  
- **Key Features:**  
  - Mortality rate  
  - Age  
  - Gender  
  - Satisfaction score  
  - Wait time  
  - Referral department  
  - Infection rate  
  - Readmission rate  

---

## 🏗️ System Architecture  

1. **Data Ingestion & Cleaning** (Pandas, NumPy)  
2. **Exploratory Data Analysis (EDA)**  
3. **Feature Engineering**  
4. **Model Training** (`ExtraTreeClassifier` using Scikit-learn)  
5. **Model Evaluation** (Accuracy, Precision, Recall, F1 Score)  
6. **Data Visualization** (Power BI)

---

## 🧪 Methodology  

### 🔹 Model Used  
- **ExtraTreeClassifier** (Scikit-learn)

### 🔹 Evaluation Metrics  

| Metric     | Score     |
|------------|-----------|
| Accuracy   | 91.7%     |
| Precision  | 90.2%     |
| Recall     | 100.0%    |
| F1 Score   | 94.8%     |

---

## 📊 Key Insights  

### ✅ Case 1: Reducing Wait Times  
- Patients seen within 19 mins: **49% mortality**  
- Patients with 60-minute wait: **56% mortality**  
- **ROI:** 72% ($34,700 investment saved $25,000/year)

### ✅ Case 2: Lowering Readmission Rates  
- Readmission Rate (53% → 45%)  
- Cost Impact Reduced: $49K → $43K  
- **ROI:** 79% ($19,000 investment saved $15,000/year)

---

## 🎯 Business Impact  

- Reduced patient wait times, improving treatment efficiency  
- Lowered readmission rates, relieving ER congestion  
- Optimized resource allocation, improving hospital operations  
- Enabled data-driven triage, supporting life-saving decisions  

---

## 🏆 Key Achievements  

- Built a high-accuracy classification model to identify high-risk ER patients  
- Integrated Power BI visualizations to support clinical decision-making  
- Demonstrated financial and operational ROI with actionable insights  

---

## 🔍 Lessons Learned  

- **Data Quality:** Accurate, clean data is essential for valid predictions  
- **Model Optimization:** Feature selection and tuning boosted performance  
- **Insight Discovery:** Even with limited features, strong patterns emerged  
- **Scalability:** Future implementations can benefit from real-time data  

---

## 🔮 Future Work  

- Integrate real-time EHR data  
- Include patient vital signs as time-series features  
- Experiment with ensemble models for higher predictive accuracy  
- Expand to real-time dashboard deployment for clinical use  

---

## 🧠 Recommendations  

- 📉 Reduce ER wait times using AI-powered triage  
- 🔁 Strengthen discharge & follow-up programs  
- 📊 Analyze mortality disparities across departments  
- 🧾 Improve data completeness for better prediction reliability  
- 🧠 Leverage predictive tools for smarter resource planning  

---
