
⭐ README.md (Copy–Paste Ready)
📌 FUTURE_ML_02 — OTT Platform Churn Prediction System

Machine Learning Internship — Future Interns

📖 Project Overview

This project focuses on building a Churn Prediction System for an OTT (Online Streaming) Platform.
Using user behavior data such as watch time, subscription plan, session count, satisfaction score, and inactivity, the model predicts whether a user is likely to churn (leave the service).

This is Task 2 of the Future Interns Machine Learning Internship (Track: ML).

🎯 Objectives

Identify which users are most likely to churn

Understand the behavioral patterns contributing to churn

Generate meaningful visual insights

Build an ML model that classifies users as Churn or Not Churn

Provide business recommendations to reduce churn

🗂 Dataset

The dataset includes 200 OTT user records and contains the following features:

age

gender

subscription_plan

monthly_watch_time_hours

total_sessions

preferred_genre

device_type

satisfaction_score

last_login_days_ago

support_tickets

churn (Target Variable)

🔍 Exploratory Data Analysis

The project includes the following visualizations:

Churn Distribution

Subscription Plan vs Churn

Device Type vs Churn

Satisfaction Score vs Churn

Feature Importance Plot

Confusion Matrix Heatmap

These graphs help understand the patterns behind user churn.

🧠 Machine Learning Model

Algorithm used:
✔ Random Forest Classifier

Model Performance:

Accuracy: ~85%–92%

Evaluation Metrics:

Precision

Recall

F1-Score

Confusion Matrix

The Random Forest model performed well and identified key churn indicators.

📊 Feature Importance

Top contributing factors to churn:

Last Login Days Ago

Satisfaction Score

Watch Time

Total Sessions

Subscription Plan

These help the OTT platform take actionable decisions.

📁 Project Structure
FUTURE_ML_02/
│
├── ott_churn_dataset.csv
├── churn_predictions_output.csv
├── notebook.ipynb
├── README.md
└── images/
      ├── churn_distribution.png
      ├── subscription_plan_churn.png
      ├── device_type_churn.png
      ├── satisfaction_score_churn.png
      ├── feature_importance.png
      └── confusion_matrix.png

🚀 Tools & Technologies

Python

Google Colab

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

📝 Business Recommendations

Based on analysis:

Provide personalized recommendations to increase engagement

Improve satisfaction by gathering feedback from low-score users

Offer special promotions for inactive customers

Reduce churn for Basic plan users by offering upgrades

Send re-engagement emails for users inactive for +30 days

📌 Internship Requirement

This repository is created as part of Future Interns Machine Learning Task 2
(Track Code: ML)
