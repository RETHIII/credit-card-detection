# credit-card-fraud-detection

Task Objectives
Detect fraudulent transactions using machine learning with SMOTE balancing.

Dataset

Dataset: [Kaggle Credit Card Fraud Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

Steps to Run This Project
1. Clone repo.

cd path_to/Credit-Card-Fraud-Detection
git init
git remote add origin https://github.com/RETHIII/Credit-Card-Fraud-Detection.git
git add .
git commit -m "Initial commit - Credit Card Fraud Detection"
git branch -M main
git push -u origin main

git remote add origin https://github.com/RETHIII/credit-card-detection.git
git branch -M main
git push -u origin main

2. Install dependencies:
   pip install pandas numpy scikit-learn imbalanced-learn matplotlib seaborn

3. Run notebook Credit_Card_Fraud_Detection.ipynb.

Models Used
Random Forest Classifier
SMOTE for handling imbalance

Performance
Accuracy: 99.95%
Precision/Recall for Fraud class improved.

Performance Analysis
Confusion Matrix,classification Report, ROC Curve plotted.
