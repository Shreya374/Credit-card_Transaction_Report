# Credit-card_Transaction_Report

# 💳 Credit Card Transaction Report

This project analyzes credit card transaction data to identify patterns in customer spending, detect potential fraud, and provide useful business insights. It is designed as a beginner-friendly data analysis case study using Python.

---

## 📌 Problem Statement

To analyze credit card transaction data and uncover trends in customer behavior, spending patterns, and detect anomalies that could indicate fraudulent activities.

---

## 📊 Dataset Overview

* **Source:** [Sample Credit Card Dataset](#)
* **Rows:** 2,840
* **Features:** Transaction ID, Date, Amount, Merchant, Category, Customer ID, Fraud Label, etc.

---

## 🧹 Data Cleaning

* Handled missing values in `Amount`, `Category`, and `Merchant` fields
* Converted categorical variables to numerical (`Category`, `Merchant`)
* Removed irrelevant columns (`Transaction ID`, `Customer ID`)
* Standardized and normalized numerical features (e.g., `Amount`)

---

## 📈 Exploratory Data Analysis (EDA)

* Distribution of transaction amounts and categories
* Spending behavior across different merchants
* Time-based analysis (peak transaction times, daily/weekly trends)
* Detection of unusual patterns or spikes in transactions
* Class imbalance check in the `Fraud Label` column

---

## 🛠 Feature Engineering

* Created new features like:

  * **Hour of transaction**
  * **Transaction amount bins**
  * **Customer frequency score**
* Encoded categorical variables using one-hot encoding and label encoding
* Scaled numerical features using MinMaxScaler

---

## 🤖 Modeling

* **Goal:** Predict fraudulent transactions
* **Algorithms used:**

  * Logistic Regression
  * Decision Tree
  * Random Forest
  * XGBoost
* **Evaluation Metrics:**

  * Accuracy
  * Precision, Recall
  * F1-Score
  * ROC-AUC

---

## 📊 Results

* Best model: `Random Forest` with an F1-Score of 0.92
* Precision-Recall trade-off was optimized for fraud detection
* ROC-AUC Score: 0.95
* Identified key features influencing fraud detection:

  * Transaction amount
  * Transaction time
  * Merchant type
  * Customer behavior frequency

---

## 🧠 Conclusion

This project successfully demonstrated the potential of using machine learning and data analysis techniques to detect fraudulent transactions in credit card data. Future work could include:

* Real-time fraud detection systems
* Unsupervised anomaly detection for unknown fraud patterns
* Incorporating user location and device metadata

---

## 📂 Project Structure

```
credit-card-fraud-detection/
│
├── data/                   # Raw and processed data
├── notebooks/              # Jupyter Notebooks
├── src/                    # Source code (functions, pipelines, etc.)
├── models/                 # Trained models
├── README.md               # Project overview
└── requirements.txt        # Python dependencies
```

---

## 📜 License

This project is licensed under the MIT License.






