# Waze Monthly Churn – Insights & Recommendations

## 1. Executive Summary
This project analyzes monthly churn behavior among Waze users and develops
a predictive framework to identify users at high risk of disengagement.

The analysis reveals clear behavioral differences between churned and retained users.
These insights can be used to trigger targeted retention actions and improve long-term
user engagement and growth.

---

## 2. Key Insights

### 2.1 Who is most likely to churn?
- Users with declining recent activity are significantly more likely to churn
- Low-frequency users show substantially higher churn rates than highly engaged users
- Churn risk increases after periods of reduced app interaction

### 2.2 Why do users churn?
- Reduced usage intensity often precedes churn rather than occurring suddenly
- Churned users exhibit lower engagement across multiple signals, not just one metric
- This suggests churn is typically a gradual disengagement process

### 2.3 When do users churn?
- The highest churn risk occurs shortly after sustained drops in activity
- Early identification windows exist where intervention may still be effective

---

## 3. Model Findings

### 3.1 Baseline Model (Logistic Regression)
- Provides a clear, interpretable benchmark
- Identifies direction and relative importance of engagement signals
- Useful for explaining churn drivers to non-technical stakeholders

### 3.2 Tree-Based Model (Random Forest)
- Improves predictive performance over the baseline
- Captures non-linear relationships between engagement metrics and churn
- Requires careful validation to avoid overfitting

---

## 4. Business Recommendations

### 4.1 Retention Strategy
- Use churn risk scores to segment users into low, medium, and high-risk groups
- Focus proactive engagement efforts on medium-to-high risk users where impact is highest
- Avoid over-investing in users who have already fully disengaged

### 4.2 Product & Engagement Actions
- Trigger in-app prompts or reminders after sustained drops in activity
- Test targeted incentives (e.g. feature highlights, notifications) for high-risk segments
- Personalize interventions based on usage patterns

### 4.3 Analytics & Governance
- Recompute churn scores on a rolling monthly basis
- Monitor model performance and recalibrate thresholds as behavior evolves
- Combine model outputs with qualitative product insights for decision-making

---

## 5. Limitations
- Analysis is based on historical data and may not capture future behavioral shifts
- External factors (seasonality, location, competition) are not explicitly modeled
- Predictions support decisions but do not replace product judgment

---

## 6. Next Steps
- Introduce time-based validation to better simulate real-world prediction
- Expand features with longitudinal and cohort-based signals
- Run controlled A/B tests to measure the causal impact of retention interventions
