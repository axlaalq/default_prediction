# 💳 Credit Risk Modeling - Default Prediction & Payment Forecasting

## 📌 Overview

This project focuses on building machine learning models to analyze credit card client behavior and predict:

- **Regression task:** Payment amount (`PAY_AMT4`)
- **Classification task:** Default probability (`default.payment.next.month`)

The goal is to generate insights that can support financial institutions in risk management and decision-making.

---

## 📊 Dataset

The dataset used is **Default of Credit Card Clients**, which contains:

- Demographic information (age, gender, education, marital status)
- Credit limit information
- Historical payment behavior (April–September)
- Billing amounts and payment amounts
- Default indicator (target variable)

---

## ⚙️ Methodology

### 1. Exploratory Data Analysis (EDA)
- Distribution analysis
- Correlation analysis
- Outlier detection
- Temporal behavior of payments

### 2. Data Preprocessing
- Handling missing values
- Encoding categorical variables
- Feature scaling
- Data consistency checks

### 3. Feature Engineering
- Payment ratios (payment vs bill)
- Historical delinquency patterns
- Aggregated behavioral features
- Trend-based features

### 4. Modeling
Different models were implemented and compared:

- Linear Models (Linear Regression, Logistic Regression)
- Decision Trees
- Gradient Boosting Models (e.g., XGBoost, LightGBM)
- Neural Networks

---

## 📈 Evaluation

### Regression Metrics:
- RMSE
- MAE

### Classification Metrics:
- Accuracy
- Precision / Recall
- ROC-AUC

Model selection was based on performance, interpretability, and robustness.

---

## 🚫 Data Leakage Considerations

Special care was taken to avoid data leakage by:
- Respecting the temporal order of features
- Avoiding use of future information when predicting past outcomes

---

## 🧠 Key Insights

- Payment history is one of the strongest predictors of default.
- Credit utilization and payment ratios provide strong signals.
- Ensemble models outperform linear models in classification tasks.
- Neural networks can capture complex nonlinear relationships but require careful tuning.

---

## 🧩 Challenges

- Handling imbalanced data in classification
- Avoiding data leakage
- Feature selection vs model complexity trade-offs

---

## 📌 Tech Stack

- Python
- Pandas / NumPy
- Scikit-learn
- XGBoost / LightGBM
- TensorFlow / Keras (optional)
- Matplotlib / Seaborn

---

## 📎 Project Structure
