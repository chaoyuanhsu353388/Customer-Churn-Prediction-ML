# 🏦 Customer Churn Prediction (Machine Learning)

🚀 **Supervised Machine Learning - Classification using Random Forest & SVM**  
This project builds a **classification model** to predict **customer churn** in the banking sector.  
It uses **Random Forest and Support Vector Classifier (SVC)** to analyze customer attrition,  
optimize retention strategies, and improve decision-making.

---

## 📖 Project Overview

Customer churn, or customer attrition, is a significant issue for banks. Identifying potential  
churners allows banks to take proactive measures to retain customers. This project applies  
**machine learning** techniques to predict whether a customer will **stay or leave** based on  
demographic and financial data.

---

## 🎯 Objectives

1️⃣ **Develop** a classification model for customer churn prediction  
2️⃣ **Apply** feature engineering and preprocessing techniques  
3️⃣ **Optimize** models using **hyperparameter tuning**  
4️⃣ **Evaluate** model performance using appropriate metrics  
5️⃣ **Recommend** the best model for real-world deployment  

---

## 📂 Dataset  

📌 **Source**: CustomerChurn.csv (Bank Credit Card Customers)  
📊 **Features**:  
- **Demographics**: Age, Gender, Marital Status, Education Level  
- **Financial Data**: Credit Limit, Transaction Amount, Income Category  
- **Behavioral Data**: Relationship Duration, Contact Frequency, Inactivity Period  
- **Target Variable**:  
  - `Existing Customer` → Customer remains  
  - `Attrited Customer` → Customer churned  

---

## ⚙️ Tools & Techniques  

✔ **Data Preprocessing** (Handling missing values, feature encoding, scaling)  
✔ **Feature Engineering** (SMOTE for class balancing, PCA for dimensionality reduction)  
✔ **Machine Learning Models**:  
   - **Random Forest** 🌳  
   - **Support Vector Classifier (SVC)** ✴  
✔ **Model Evaluation Metrics**:  
   - Accuracy, Precision, Recall, F1-score  
✔ **Hyperparameter Optimization** (GridSearchCV)  

---

## 📊 Key Deliverables  

✅ **Preprocessed Dataset** (Cleaned & Engineered for ML)  
✅ **Model Training & Evaluation** (Random Forest vs. SVC)  
✅ **Comparison & Insights** (Hyperparameter Tuning Results)  
✅ **Deployment Recommendation** (Best Model for Production)  

---

## 🔍 Insights & Findings  

📌 **Best Performing Model**: **Random Forest** (Highest accuracy & F1-score)  
📌 **Random Forest vs. SVM**:  
   - **Random Forest** achieved **94.02% accuracy** after tuning  
   - **SVM (RBF Kernel)** improved to **88.51% accuracy** after tuning  
📌 **Precision-Recall Tradeoff**:  
   - **Random Forest** balanced both precision & recall  
   - **SVM** improved recall but sacrificed precision  

---

