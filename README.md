# 💳 Credit Card Fraud Detection

## 📌 Project Description

Credit Card Fraud Detection is a data analysis and machine learning project focused on analyzing credit card transactions and identifying patterns associated with fraudulent activities.

The project uses a dataset containing **20,000 credit card transactions and 26 features**. These features include transaction amount, merchant category, card type, authentication method, transaction channel, device type, foreign transaction status, transaction frequency, velocity score, IP-country mismatch, billing-shipping mismatch, CVV retry count, merchant risk score, prior disputes, and the fraud label.

The project begins with **data loading and data understanding**, followed by a systematic data-cleaning process. The dataset is checked for missing values, duplicate records, inconsistent values, incorrect data types, invalid values, and outliers. After cleaning and validating the data, exploratory analysis and visualization are performed to understand transaction behavior and fraud-related patterns.

The cleaned dataset can then be used as a foundation for developing a **machine learning classification model** to predict whether a transaction is fraudulent or legitimate.

## 🎯 Project Objectives

* Understand credit card transaction data.
* Identify patterns related to fraudulent transactions.
* Perform data cleaning and preprocessing.
* Handle missing, duplicate, inconsistent, and invalid data.
* Detect and analyze outliers.
* Explore important fraud-related features.
* Visualize transaction and fraud patterns.
* Prepare the dataset for machine learning-based fraud classification.

## 🛠️ Technologies Used

* **Python**
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **Jupyter Notebook** – Development environment

## 📊 Dataset Features

Some important features included in the dataset are:

* `transaction_id`
* `amount_usd`
* `merchant_category`
* `card_type`
* `auth_method`
* `channel`
* `device_type`
* `is_foreign_transaction`
* `hours_since_last_txn`
* `txn_count_last_24h`
* `ip_country_mismatch`
* `billing_shipping_mismatch`
* `cvv_retry_count`
* `velocity_score`
* `time_of_day_hour`
* `day_of_week`
* `is_ai_generated_scam_attempt`
* `merchant_risk_score`
* `prior_disputes`
* `is_fraud`

## 🔄 Project Workflow

```text
Dataset
   ↓
Data Loading
   ↓
Data Understanding
   ↓
Data Cleaning
   ↓
Missing Value Analysis
   ↓
Duplicate Detection
   ↓
Invalid & Inconsistent Value Checking
   ↓
Data Type Correction
   ↓
Outlier Analysis
   ↓
Exploratory Data Analysis
   ↓
Data Visualization
   ↓
Fraud Pattern Analysis
   ↓
Machine Learning Preparation
```

## 🔍 Data Cleaning

The following data-cleaning steps are performed:

1. Load the dataset.
2. Understand the dataset structure.
3. Check data types.
4. Check missing values.
5. Handle missing values.
6. Check duplicate values.
7. Remove duplicates.
8. Check inconsistent values.
9. Correct data types where required.
10. Detect and handle outliers.
11. Check invalid values.
12. Rename columns if required.
13. Verify the cleaned dataset.
14. Save the cleaned dataset.

## 📈 Expected Outcome

The main goal of this project is to understand transaction-level fraud patterns and prepare a reliable dataset for fraud detection. The analysis can help identify transaction characteristics that may be associated with fraudulent activity and provide a foundation for building a machine learning model for fraud classification.

## 👨‍💻 Project Type

**Data Science + Machine Learning**

**Domain:** Finance / Banking / Fraud Detection
