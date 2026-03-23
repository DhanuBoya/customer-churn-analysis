# Customer Churn Prediction (Machine Learning Project)

## Project Overview
This project develops a predictive analytics solution to identify customers at risk of churn in a telecommunications dataset.

The goal is to enable proactive retention strategies using machine learning and data-driven insights.

---

## Business Problem
Customer churn is a major challenge for subscription-based businesses. Retaining existing customers is significantly more cost-effective than acquiring new ones.

This project aims to:
- Predict which customers are likely to churn
- Identify key drivers of churn
- Provide actionable business recommendations

---

## Tools & Technologies
- Python (Pandas, NumPy)
- Scikit-learn
- XGBoost
- Matplotlib / Seaborn
- SHAP (Model Interpretability)

---

## Models Used
- Logistic Regression
- Random Forest
- XGBoost

---

## Key Results
- Best Model: Logistic Regression
- ROC-AUC: ~0.84
- Recall (Churn Class): ~0.79
- XGBoost achieved best F1-score (~0.62)

---

## Key Insights
- Customers with low tenure are most likely to churn
- Higher monthly charges increase churn risk
- Month-to-month contracts have highest churn rates
- Fiber optic users show higher churn probability
- Value-added services (security, tech support) reduce churn

---

## Business Recommendations
- Implement early churn detection system
- Incentivise long-term contracts
- Optimise pricing for high-risk segments
- Improve fiber optic service experience
- Promote value-added services

---

## Model Explainability
SHAP (Shapley Additive Explanations) was used to interpret model predictions and identify key drivers of churn.

---

## Future Improvements
- Add time-series features
- Implement real-time prediction system
- Use cost-sensitive learning
- Deploy model via Streamlit app

---

## Project Structure
(briefly describe your folders)

---

## Author
Dhanuja Boyagoda
Master of Business Analytics — Deakin University
