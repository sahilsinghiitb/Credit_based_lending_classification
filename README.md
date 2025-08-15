## 🧾 Credit Risk Modelling using Classification  

This project focuses on building a predictive model to classify loan applicants into low-risk vs high-risk profiles to aid better credit approval decisions in lending.

### 🔍 Objective
To develop a robust classification model for credit risk using internal banking data and credit bureau (CIBIL) features, enabling data-driven lending with improved precision.

---

### 🗃️ Data & Preprocessing
- Combined **internal product data** and **CIBIL datasets** (>80 features)
- Performed **encoding** and **feature scaling** for model readiness
- Handled **outliers** and applied **VIF**, **Chi-Square**, and **ANOVA tests** for feature reduction

---

### ⚙️ Modeling Approach
- Trained classification models with a focus on **XGBoost Classifier**
- Used **Grid Search** for hyperparameter tuning to optimize performance
- Adjusted **classification threshold** based on **Precision-Recall curve**

---

### ✅ Results & Evaluation
- Achieved **F1-score of 0.76**
- Final model explained using **SHAP interpretability** to highlight most influential credit factors

---

### 📦 Deployment
- Model exported and integrated into a **Flask-based API** for credit risk inference and scoring

---

### 🛠️ Tools & Libraries
- Python, pandas, NumPy, scikit-learn, XGBoost, SHAP, Flask
