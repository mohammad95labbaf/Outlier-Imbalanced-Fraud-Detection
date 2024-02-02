# Credit Card Fraud Detection Repository

Welcome to the **Credit Card Fraud Detection Repository**! This project focuses on identifying fraudulent credit card transactions using a combination of statistical techniques and machine learning. The goal is to build a robust system that can automatically detect suspicious activities and protect users from financial losses.

## Key Components

1. **Data Preprocessing:** The process starts by cleaning and preparing the credit card transaction data. This involves handling missing values, standardizing features, and exploring the dataset. Boxplots and Z-scores play a crucial role in identifying outliers, which are potential anomalies that might indicate fraudulent transactions.

2. **Outlier Detection:** Boxplots and Z-scores are leveraged to pinpoint outliers in the transaction data. Outliers could be transactions with unusually high or low amounts, abnormal frequency, or suspicious patterns. Removing outliers helps improve the accuracy of our fraud detection model.

3. **Classification Model:** Decision trees are powerful tools for binary classification tasks. A decision tree model is trained to classify transactions as either legitimate or fraudulent. The decision tree algorithm splits the data based on features such as transaction amount, merchant category, and time of day.

## How to Use This Repository

1. **Download the Dataset:** You can download the credit card fraud dataset from this link: [Credit Card Fraud Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud). Make sure to explore the dataset and understand its structure.

## Evaluating Credit Card Fraud Detection: Beyond Accuracy

In credit card fraud detection, accuracy alone doesn't tell the whole story. Other essential metrics are considered to draw meaningful conclusions:

1. **Precision (Positive Predictive Value):** Precision measures how many of the predicted fraud cases are actually fraud. A high precision means fewer false positives (legitimate transactions incorrectly flagged as fraud).

2. **Recall (Sensitivity):** Recall measures how many actual fraud cases were correctly predicted. A high recall means fewer false negatives (frauds missed).

3. **F1-Score (Harmonic Mean):** The F1-score balances precision and recall, considering both false positives and false negatives.

4. **ROC AUC (Receiver Operating Characteristic Area Under the Curve):** The ROC AUC evaluates the model's ability to distinguish between classes. A higher ROC AUC indicates better performance.

## Conclusion

The **Box Plot Method** significantly improved precision, recall, and F1-score, while the **Z-Score Method** also improved these metrics but not as significantly. Depending on business requirements (e.g., prioritizing recall to catch most frauds), you can choose the method that best suits your needs.

Please refer to the detailed evaluation results in the repository for more information. Happy exploring!
