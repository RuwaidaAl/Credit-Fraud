# Credit Card Fraud Detection with Machine Learning

This repository contains a full machine learning pipeline to detect fraudulent credit card transactions. It combines geospatial, temporal, and behavioral features with ensemble learning methods to improve detection performance.

## 📌 Project Highlights
- **Feature Engineering**: Age, transaction time, day of week, and distance traveled.
- **Geospatial Analysis**: Calculates distances between customer and merchant locations using latitude and longitude.
- **Suspicious Travel Detection**: Flags implausible high-speed travel between transactions.
- **Imbalanced Data Handling**: Uses SMOTE to address severe class imbalance.
- **Modeling**: Random Forest and XGBoost for robust fraud classification.


## 🛠️ Tech Stack
- **Python**
- **Libraries**: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`, `geopy`, `xgboost`, `imbalanced-learn`

## 📁 Dataset
The data used for this project is stored locally and includes columns such as:
- Transaction time and date
- Customer and merchant geolocation
- Transaction amount and category
- Demographics (e.g., gender, date of birth)
- Link to dataset: https://www.kaggle.com/datasets/kelvinkelue/credit-card-fraud-prediction
  

## 📊 Visualizations
- Gender-based transaction distributions
- Day-of-week transaction trends
- Correlation matrix of engineered features

## 🚀 Getting Started
1. Clone the repo:
```bash
git clone https://github.com/your-username/credit-card-fraud-detection.git
cd credit-card-fraud-detection
```
2. Install dependencies:
```bash
pip install -r requirements.txt
```
3. Run the notebook or script to train and evaluate the model.

## 📈 Performance Metrics
- Precision
- Recall
- F1 Score
- ROC-AUC

## 📌 Output
The final model is evaluated using an optimized threshold derived from the precision-recall curve. A classification report is printed to assess its performance.

## 📬 Contact
Created by **Ruwaida Al Harrasi** – feel free to reach out!

---
Feel free to fork the repository or suggest improvements via pull requests!
