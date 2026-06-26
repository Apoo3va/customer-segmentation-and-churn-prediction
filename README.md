# Telecom Customer Churn Prediction & Customer Segmentation

## Overview

Customer retention is a critical challenge in the telecom industry. Acquiring new customers is often more expensive than retaining existing ones, making churn prediction a valuable business problem.

This project develops an end-to-end Machine Learning pipeline to analyze telecom customer behavior, predict customer churn, and identify meaningful customer segments. By combining predictive analytics with customer segmentation, the project provides actionable insights that can help businesses improve retention strategies, optimize marketing efforts, and enhance customer experience.

---

## Objectives

* Analyze customer demographics, services, and account information.
* Identify factors influencing customer churn.
* Build and evaluate Machine Learning models for churn prediction.
* Compare model performance to select the most effective classifier.
* Segment customers into distinct groups using clustering techniques.
* Generate business insights for targeted customer retention strategies.

---

## 📂 Dataset Features

The dataset includes customer-related information such as:

* Customer demographics
* Subscription details
* Internet and phone services
* Contract type
* Payment methods
* Monthly charges
* Total charges
* Customer tenure
* Churn status

---

## Exploratory Data Analysis (EDA)

Performed extensive data exploration to understand customer behavior and churn patterns:

* Missing value analysis and treatment
* Distribution analysis of numerical features
* Categorical feature exploration
* Correlation analysis
* Churn trend visualization
* Service usage analysis
* Contract and payment behavior analysis

Key business questions explored:

* Which customers are most likely to churn?
* How does tenure affect retention?
* Which services influence customer loyalty?
* What role do contracts and payment methods play in churn?

---

## ⚙️ Data Preprocessing

The following preprocessing techniques were applied:

* Handling missing and inconsistent values
* Feature encoding for categorical variables
* Feature scaling where required
* Data transformation and cleaning
* Train-test splitting
* Preparation of data for classification and clustering models

---

## 🤖 Machine Learning Models

Multiple Machine Learning approaches were explored and evaluated for churn prediction.

### Classification Task

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier
* Model evaluation using:

  * Accuracy
  * Precision
  * Recall
  * F1-Score
  * Confusion Matrix

### Best Performing Model

 **Random Forest Classifier** achieved the strongest overall performance and was selected as the final churn prediction model due to its ability to capture complex customer behavior patterns and provide robust predictions.

---

##  Customer Segmentation

To better understand customer groups, K-Means Clustering was applied.

### Segmentation Process

* Feature selection
* Data standardization
* Optimal cluster identification
* K-Means model training
* Cluster interpretation

### Customer Groups Identified

Examples of segments discovered include:

* High-value loyal customers
* At-risk customers
* Budget-conscious customers
* Premium service users

These segments can help businesses design personalized retention and marketing campaigns.

---

## 📈 Business Insights

The analysis revealed several important patterns:

* Customers with shorter tenure are more likely to churn.
* Contract type significantly impacts retention.
* Monthly charges influence customer behavior.
* Certain service combinations correlate strongly with churn risk.
* Customer segmentation enables more targeted decision-making.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## 📁 Repository Structure

```text
telecom-customer-churn-prediction/
│
├── CBSOT_Project1.ipynb
├── README.md
├── .gitignore
└── data/
```

## 🚀 Future Improvements

* Hyperparameter tuning using GridSearchCV
* XGBoost and LightGBM implementation
* Model deployment using Streamlit
* Real-time churn prediction dashboard
* Automated customer retention recommendation system

---

## Author

**Apoorva Yadav**

Electronics and Communication Engineering Student | Machine Learning Enthusiast | Data Analytics Learner

Feel free to explore the notebook, suggest improvements, or connect for collaboration.
