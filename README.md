# 🫀 Heart-Disease-Prediction — End-to-End ML Project

**Author:** Siyu Chen  
**Tech stack:** Python, Pandas, scikit-learn, Matplotlib, Seaborn, Joblib  

---

## 📖 Project Overview
This project builds an **end-to-end machine learning pipeline** to predict the likelihood of heart disease from **13 clinical features**.  

Unlike a standard tutorial, this project goes further by adding **robust evaluation, PR curves, and production readiness**, which are critical in real-world data science.

---

## 🚀 Key Highlights
- ✅ End-to-end pipeline with `scikit-learn Pipeline + ColumnTransformer`.  
- ✅ **5-fold Stratified Cross-Validation** (F1 = 0.82 ± 0.03).  
- ✅ **Precision–Recall curve & threshold tuning** for imbalanced medical data.  
- ✅ **Persisted model with joblib** + lightweight **Model Card**.  
- ✅ Final performance: **ROC-AUC = 0.87, F1 = 0.82**.  

---

## 📊 Dataset
- Source: [UCI Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/heart+disease)  
- 13 clinical features (age, sex, chest pain type, cholesterol, resting blood pressure, etc.).  
- Binary target: `1 = heart disease`, `0 = no disease`.  

---

## ⚙️ Workflow
1. **Data Preprocessing**  
   - Handled numeric & categorical features via `ColumnTransformer`.  
   - Standardization + One-hot encoding.  

2. **Modeling**  
   - Logistic Regression (baseline).  
   - Random Forest (comparison).  

3. **Evaluation Improvements**  
   - 5-fold Stratified CV for robust metrics.  
   - ROC & PR Curves to visualize trade-offs.  
   - Threshold tuning to optimize recall.  

4. **Productionization**  
   - Save model with `joblib`.  
   - Documented assumptions & limitations in a **Model Card**.  

---

## 📈 Results
| Metric                | Score            |
|------------------------|------------------|
| F1 (5-fold CV)         | 0.82 ± 0.03      |
| ROC-AUC (Holdout)      | 0.87             |
| Precision-Recall Curve | See plots        |

---

