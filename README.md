# 🏥 Patient Readmission Prediction

A machine learning project to predict whether a diabetic patient will be readmitted within 30 days of discharge.

## 📊 Dataset
- Source: [UCI - Diabetes 130-US hospitals](https://www.kaggle.com/datasets/aaron7sun/diabetes-health-indicators-dataset)
- Records: 100,000+
- Features: Demographics, lab procedures, diagnoses, medications

## ⚙️ Project Workflow
1. Data Cleaning & Preprocessing
2. Exploratory Data Analysis (EDA)
3. Imbalanced Class Handling with SMOTE
4. Model Training (Random Forest, Gradient Boosting)
5. Threshold tuning & Evaluation
6. Feature Importance Visualization

## ✅ Best Performing Model
- **Random Forest with SMOTE**
- **ROC-AUC:** ~0.64
- **Precision-Recall Tradeoff Tuned**
- **Feature Importance:** Top predictors identified

## 🚀 How to Run
```bash
pip install -r requirements.txt
jupyter notebook
