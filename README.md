# Loan Approval Prediction (Machine Learning Project)

## 📌 Overview
This project predicts whether a loan application will be approved using multiple machine learning models.  
It includes full data preprocessing, baseline models, hyperparameter tuning using GridSearchCV, and evaluation using accuracy, precision, recall, F1-score, and confusion matrices.

---

## 📂 Dataset Description
The dataset includes customer loan information such as:
- Annual income  
- Number of dependents  
- Education level  
- Employment type  
- Loan amount  
- Loan term  
- CIBIL score  
- Asset values  
- Loan status (Approved / Rejected)

Preprocessing steps:
- Handling missing values  
- OneHotEncoding for categorical features  
- StandardScaler for numeric features  
- Train/Test splitting (70/30)

---

## ⚙️ Methodology

### **1️⃣ Baseline Models (Without Tuning)**
- Logistic Regression  
- Decision Tree  
- Random Forest  
- Gradient Boosting  
- XGBoost  
- AdaBoost  
- SVM  

### **2️⃣ Hyperparameter Tuning (With GridSearchCV)**
Tuning was applied to:
- Logistic Regression  
- Decision Tree  
- Random Forest  
- AdaBoost  

GridSearchCV was used to find the best parameters and reduce overfitting.

---

## 📊 Results and Visualizations
The following outputs are included in the notebook:
- Confusion matrices for each model  
- Bar plot comparing test accuracy across all models  
- A full comparison table showing:
  - Train accuracy  
  - Test accuracy  
  - Precision  
  - Recall  
  - F1-score  

### 🏆 **Best Model: Gradient Boosting**
- Test accuracy ≈ **98.67%**  
- Balanced performance  
- No overfitting (train ≈ test)

---

## 📄 Files Included
- `loan-prediction.ipynb` → Full ML pipeline  
- `Loan_Prediction_Report.pdf` → Short written report  
- Images generated inside the notebook (confusion matrices & plots)

---

## 🏁 Conclusion
Gradient Boosting delivered the best performance with strong generalization and minimal overfitting, making it the recommended model for real-world deployment.

