# Financial Fraud Detection using Anomaly Detection (Isolation Forest)

## 📌 Project Overview
In the financial industry, fraudulent transactions are rare but extremely costly. This project develops an intermediate-level machine learning pipeline to identify fraudulent activities in a synthetic financial dataset (PaySim). Instead of traditional classification, this project utilizes **Anomaly Detection** logic to isolate suspicious transactions that deviate from normal patterns.

## 🚀 Key Features
- **Data Exploration (EDA):** Identified that 100% of fraud occurs in 'TRANSFER' and 'CASH_OUT' transaction types.
- **Data Preprocessing:** Handled extreme class imbalance (fraud is <0.1% of data) and performed label encoding for categorical features.
- **Machine Learning:** Implemented an **Isolation Forest** algorithm, an unsupervised learning method ideal for outlier detection.
- **Evaluation:** Focused on **Recall** and **Confusion Matrix** metrics to ensure maximum detection of fraudulent actors.

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Environment:** Kaggle Notebook

## 📊 Results Summary
- **Recall:** [Insert your Recall score here, e.g., 85%]
- **Key Insight:** By filtering for specific transaction types and focusing on account balance depletion patterns, the model successfully isolated fraudulent "spikes" while minimizing false positives for legitimate users.

## 📂 Project Structure
- `financial_fraud&anomaly_detection.ipynb`: The complete Python code and analysis.
- `README.md`: Project documentation.
