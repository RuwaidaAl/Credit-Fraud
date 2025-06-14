Credit Card Fraud Detection with Machine Learning

This project implements a complete pipeline for detecting fraudulent credit card transactions. It leverages powerful classification algorithms and domain-specific features to improve detection accuracy. Key components include:

🔍 Features:
Temporal Features: Hour of transaction, day of the week, customer age.

Geospatial Analysis: Distance between customer and merchant locations.

Suspicious Travel Detection: Flags for high-speed travel suggesting possible fraud.

Imbalanced Data Handling: Uses SMOTE for oversampling minority (fraud) class.

Modeling:

Random Forest (with class balancing)

XGBoost for improved accuracy and performance

Threshold Optimization: Precision-recall curve to select the best threshold based on F1-score.

📊 Evaluation Metrics:
Precision

Recall

F1-Score

ROC-AUC

📈 Tools & Libraries:
Python (Pandas, NumPy, Scikit-learn, imbalanced-learn, Geopy, Matplotlib, Seaborn, XGBoost)
