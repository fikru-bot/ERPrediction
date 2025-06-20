Power BI Healthcare Analytics: Predicting ER Patient Mortality
🩺 Overview
Emergency rooms are high-stakes environments where timely and informed decisions are critical. This project applies predictive analytics to ER data to identify high-risk patients, enabling faster, data-driven interventions. The Power BI dashboard visualizes key patient metrics and hospital performance indicators to support clinicians in improving emergency care and reducing mortality rates.

📊 Executive Summary
This project leverages historical ER patient data to build a predictive model capable of identifying individuals at risk of mortality based on features such as age, wait time, infection and readmission rates, and satisfaction scores. The resulting Power BI dashboard supports hospital staff in prioritizing patients, optimizing workflows, and making impactful decisions in real time.

📁 Data Overview
Source: Data.world - Hospital ER Dataset

Features: Mortality rate, age, gender, satisfaction score, wait time, referral department, infection & readmission rates

Period: 2019 – 2020

File: Hospital ER.csv

⚙️ System Architecture
Data Ingestion & Cleaning (Pandas, NumPy)

Feature Engineering & Selection

Model Training (ExtraTreeClassifier using Scikit-learn)

Performance Evaluation (Accuracy, F1, Precision, Recall)

Power BI Visualization & Dashboard Deployment

🧪 Methodology
Model Used: ExtraTreeClassifier

Model Accuracy: 91.7%

Precision: 90.2%

Recall: 100%

F1 Score: 94.8%

Data cleaning, outlier handling, and feature selection were performed to enhance performance and interpretability.

📈 Key Insights
💡 Wait Time Optimization
Patients seen within 19 minutes had 49% mortality.

60-minute waits resulted in 56% mortality.

A $34,700 investment reduced delays and saved $25,000 annually (72% ROI).

💡 Readmission Reduction
Lowering readmission from 53% to 45% decreased costs from $49K to $43K.

Investment: $19,000 | Savings: $15,000 | ROI: 79%.

📌 Business Impact
Enhanced patient triage and faster treatment

Reduced readmission rates and ER burden

Improved patient outcomes and hospital resource allocation

✅ Key Achievements
Built a reliable classification model to predict ER mortality

Delivered an actionable dashboard using Power BI

Demonstrated ROI-driven strategies to enhance ER operations

📚 Lessons Learned
Importance of complete and clean data in clinical ML

Feature importance helped refine hospital workflows

Model tuning and data quality significantly impact predictive performance

🔮 Future Improvements
Incorporate real-time EHR data

Expand with time-series patient vitals

Use ensemble models for further accuracy gains

Implement live dashboard in clinical environments

💡 Recommendations
Streamline high-wait departments with triage AI

Reinforce follow-up care to reduce readmissions

Improve data logging for more granular predictions

Allocate resources based on department mortality patterns
