# inn-hotels-booking-analysis
Machine learning project to predict hotel booking cancellations using Decision Tree classification and identify key factors influencing cancellation behavior.
# INN Hotels — Hotel Booking Cancellation Prediction

## 📌 Project Overview

This project analyzes hotel booking data and develops machine learning models to predict booking cancellations.

The analysis focuses on identifying factors associated with cancellations and building a classification model that can help the hotel business proactively identify bookings with a higher risk of cancellation.

## 🎯 Business Objective

The primary business objective is to improve the identification of potential booking cancellations.

Because missed cancellations can result in lost revenue and inefficient resource planning, the project places particular importance on **recall for the cancellation class**.

## 🛠️ Technologies & Tools

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Decision Tree
* Classification
* Data Visualization

## 🔍 Project Workflow

1. Data Understanding
2. Exploratory Data Analysis
3. Data Cleaning & Preprocessing
4. Feature Preparation
5. Decision Tree Classification
6. Model Evaluation
7. Model Pruning
8. Feature Importance Analysis
9. Business Recommendations

## 🤖 Machine Learning Approach

Multiple Decision Tree approaches were evaluated, including:

* Initial Decision Tree
* Class-weighted Decision Tree
* Pre-pruned Decision Tree
* Post-pruned Decision Tree

The models were evaluated using classification metrics including:

* Accuracy
* Precision
* Recall
* F1-score

## 📊 Final Model Performance

The **post-pruned Decision Tree** was selected as the preferred model based on the project's business objective.

On the test set, the model achieved:

* **Recall: 85.96%**
* **Precision: 73.84%**

The model provided a strong balance between identifying potential cancellations and limiting false alarms.

## 🔑 Key Predictors

The analysis identified the following variables as important predictors of booking cancellations:

* Lead Time
* Online Market Segment
* Average Price per Room
* Number of Special Requests

## 💡 Business Insights & Recommendations

The project findings support several potential business actions:

* Use the model to identify bookings with higher cancellation risk.
* Apply targeted confirmation reminders to high-risk bookings.
* Consider appropriate cancellation-policy strategies for longer lead-time bookings.
* Develop tailored approaches for online-channel bookings.
* Use proactive follow-up for high-value bookings.
* Consider flexible
