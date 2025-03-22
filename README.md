# Fraud-Detection-System
Credit Card Fraud Detection System
1. Introduction
This project focuses on detecting fraudulent credit card transactions using Machine Learning. It utilizes the Credit Card Fraud Detection dataset from Kaggle and applies classification techniques to differentiate between genuine and fraudulent transactions.

2. Dataset Information
The dataset contains 284,807 transactions, with only 0.17% fraudulent cases. Due to this imbalance, special techniques are applied to improve fraud detection accuracy. The dataset includes features like transaction time, amount, and anonymized variables derived from Principal Component Analysis (PCA).

3. Data Preprocessing
Before training the model, several preprocessing steps are performed:

Loading the dataset and exploring its structure.

Scaling numeric features like transaction amount and time for consistency.

Handling imbalanced data using SMOTE (Synthetic Minority Over-sampling Technique) to generate additional fraudulent cases and improve model learning.

4. Model Training
A Random Forest Classifier is trained to classify transactions as either fraudulent or normal. The model is chosen due to its efficiency in handling classification problems and its ability to work well with imbalanced datasets.

5. Model Evaluation
The trained model is evaluated using several performance metrics:

Precision: Measures the percentage of correctly identified fraud cases.

Recall: Evaluates the ability of the model to detect fraudulent transactions.

F1-score: Provides a balance between precision and recall.

Confusion Matrix: Shows the number of correct and incorrect predictions.

6. Testing Interface
A command-line interface (CLI) is implemented where users can manually enter transaction details (such as amount and time) to check if the transaction is fraudulent or normal.

7. Future Improvements
To enhance the fraud detection system, the following improvements can be made:

Testing other machine learning models like XGBoost for better accuracy.

Deploying the model as an API using Flask or FastAPI for real-time fraud detection.

Implementing a real-time streaming system to monitor transactions dynamically.

8. Conclusion
This project demonstrates how machine learning can be used to detect fraudulent transactions. With further optimizations and real-time deployment, it can be a valuable tool for financial institutions and e-commerce platforms to minimize fraud risks.

