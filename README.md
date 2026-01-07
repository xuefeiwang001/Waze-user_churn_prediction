# Waze User Churn Prediction – Retention & Growth Analytics Project

## 📌 Project Overview
This project analyzes monthly user churn for the Waze navigation app.
The goal is to identify users at high risk of churn, understand *why* they churn,
and provide actionable insights to support retention and growth strategies.

The work is structured to reflect a real-world analytics workflow:
technical analysis is separated from business-facing insights.

📄 **Final deliverable:**  
- `05_waze_churn_insights_and_recommendations.md`

---

## 🎯 Business Problem
User churn represents lost engagement, reduced lifetime value, and slower growth.
By predicting churn in advance, Waze can proactively intervene with targeted
product, communication, or incentive strategies.

This project focuses on three core questions:
- **Who** is most likely to churn?
- **Why** do users churn?
- **When** are users most at risk of churning?

---

## 🧠 Analytical Approach
The analysis follows an end-to-end framework commonly used in product analytics:

1. **Exploratory Data Analysis & Data Quality**
   - User activity patterns
   - Distribution of engagement metrics
   - Missing values and outlier handling

2. **Statistical Analysis**
   - Group comparisons between churned and retained users
   - Hypothesis testing to identify meaningful differences

3. **Predictive Modeling**
   - Logistic Regression as an interpretable baseline
   - Tree-based models (Random Forest) for performance improvement
   - Comparison of model performance and trade-offs

4. **Insights & Recommendations**
   - Translation of model outputs into retention strategies
   - Identification of high-risk user segments
   - Discussion of limitations and next steps

---

## 📂 Project Structure
```text
waze-user-churn-prediction/
│
├── README.md
├── requirements.txt
├── 05_waze_churn_insights_and_recommendations.md
│
└── notebooks/
    ├── 01_waze_churn_eda_and_data_quality.ipynb
    ├── 02_waze_churn_statistical_analysis.ipynb
    ├── 03_waze_churn_baseline_logistic_regression.ipynb
    ├── 04_waze_churn_tree_models_random_forest.ipynb

```

## 🛠️ Tools & Skills Demonstrated
- Python (pandas, numpy)
- Exploratory Data Analysis (EDA)
- Statistical inference (hypothesis testing)
- Churn modeling (logistic regression, random forest)
- Model evaluation and business trade-offs
- Product & growth-oriented data storytelling

## 🚀 Key Takeaways
- Churn prediction is not just a modeling task, but a decision-support problem
- Interpretability is critical for translating predictions into product actions
- Different thresholds can be used depending on retention capacity and business risk

## 👩‍💻 Author  
🎓 Dual Master's Degrees in Data Science  
  - MSc in Data Analytics & Artificial Intelligence  
  - MSc in Statistics  

📌 Profile Summary  
A data-driven professional with strong analytical foundations and hands-on experience in end-to-end data projects — from ETL & dashboarding to statistical modelling and AI-powered insights.   
Passionate about transforming raw operational data into actionable business strategies.

📧 Contact: xuefei.wang.fr@gmail.com
