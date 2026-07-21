# Telco-Customer-Churn-Prediction

An end-to-end Data Science project to predict whether a telecommunications customer is likely to churn (cancel their subscription) based on demographic information, subscribed services, and billing history.

<p align="center">
  <!-- Add your screenshots here -->
  <img src="images/eda.png" width="30%">
  <img src="images/model.png" width="30%">
  <img src="images/dashboard.png" width="30%">
</p>

> 🚧 **Project Status:** In Progress

This project is being developed step by step as a practical exercise in following a proper end-to-end Data Science workflow, rather than building everything inside a single notebook. It also serves as a portfolio project to demonstrate best practices throughout the machine learning lifecycle.

Any unfinished sections will be clearly marked and updated as development continues.

---

# 📋 Table of Contents

- Project Goal
- Why This Dataset?
- Project Structure
- Progress
- Dataset
- Methodology
- Results
- How to Run
- Contact

---

# 🎯 Project Goal

The objective of this project is to predict whether a customer is likely to **churn** (cancel their subscription), allowing the business to proactively offer retention strategies before the customer leaves.

### Target Variable

- **Churn**
  - **1** = Customer churned
  - **0** = Customer stayed

### Evaluation Metrics

Since the target variable is imbalanced, this project does **not** rely on accuracy as the primary evaluation metric.

The evaluation focuses on:

- **Primary Metric:** F1-score for the churn class
- **Secondary Metric:** ROC-AUC

A **DummyClassifier** (`strategy="most_frequent"`) is used as the baseline model. The final machine learning model is expected to outperform this baseline in terms of **F1-score** and **Recall**, rather than simply achieving higher accuracy.

---

# 🤔 Why This Dataset?

This project uses the **IBM Telco Customer Churn** dataset because it presents several realistic challenges commonly encountered in real-world machine learning projects.

The dataset includes:

- A variety of categorical features (services, contract types, payment methods, etc.)
- A numerical feature (`TotalCharges`) that requires data cleaning
- An imbalanced target variable (approximately **27%** of customers have churned)

These characteristics make the dataset well suited for practicing proper preprocessing techniques, feature engineering, and selecting evaluation metrics that match the business problem, rather than simply training a model and reporting its accuracy.

---

# 📂 Project Structure

```
Telco-Customer-Churn/
│
├── data/
├── notebooks/
├── src/
├── models/
├── reports/
├── images/
├── requirements.txt
└── README.md
```

---

# 🚧 Project Progress

- [x] Problem Framing
- [x] Dataset Exploration
- [ ] Data Cleaning
- [ ] Exploratory Data Analysis (EDA)
- [ ] Feature Engineering
- [ ] Model Training
- [ ] Hyperparameter Tuning
- [ ] Model Evaluation
- [ ] Model Interpretation
- [ ] Model Deployment

---

# 📊 Dataset

- **Dataset:** IBM Telco Customer Churn
- **Task:** Binary Classification
- **Target:** `Churn`

The dataset contains customer demographics, account information, subscribed services, and billing details used to predict customer churn.

---

# 🔬 Methodology

The project follows a structured machine learning workflow:

1. Problem Framing
2. Data Understanding
3. Data Cleaning
4. Exploratory Data Analysis (EDA)
5. Feature Engineering
6. Data Preprocessing
7. Model Training
8. Model Evaluation
9. Model Interpretation
10. Model Saving

---

# 📈 Results

> 🚧 This section will be updated after the model training and evaluation stages are completed.

The final README will include:

- Model comparison
- Confusion Matrix
- Classification Report
- ROC Curve
- Feature Importance
- Final evaluation metrics

---

# 🚀 How to Run

Clone the repository:

```bash
git clone https://github.com/yourusername/telco-customer-churn.git
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Run the notebooks in order or execute the scripts inside the `src/` directory.

---
