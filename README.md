# churn_prediction_shap
"Employee Churn Prediction with Explainable AI (SHAP)"
# 🧑‍💼 Employee Churn Prediction with Explainable AI (SHAP)

## 📌 Project Overview
Employee churn (attrition) is a major challenge for organizations.  
This project builds a **machine learning model** to predict employee churn and uses **SHAP (SHapley Additive exPlanations)** to make the predictions **interpretable** for HR decision-making.  

## 🎯 Objectives
- Predict whether an employee is likely to leave (churn).
- Identify **key factors driving churn** using explainable AI.
- Provide **global insights** (which features matter most overall).
- Provide **local insights** (why a specific employee might leave).

---

## ⚙️ Workflow
1. **Data Preprocessing**  
   - Handle missing values  
   - Encode categorical variables  
   - Scale numerical features  

2. **Model Training**  
   - Trained with [your chosen model, e.g., XGBoost / RandomForest].  
   - Evaluated with accuracy, precision, recall, F1-score, ROC-AUC.  

3. **Explainability with SHAP**  
   - **Global explanations**: Feature importance across all employees.  
   - **Local explanations**: Why a single employee is predicted to churn.  

---

## 📊 Key Visuals

### 🔹 Global Feature Importance (SHAP Beeswarm Plot)
<img src="images/shap_beeswarm.png" width="600">

### 🔹 Local Explanation (Force Plot Example)
*(Interactive version available in notebook)*  
<img src="images/shap_force_example.png" width="600">

---

## 🛠️ Tech Stack
- **Python**
- **Pandas / NumPy**
- **Scikit-learn**
- **XGBoost / RandomForest**
- **SHAP**
- **Matplotlib / Seaborn**

---

## 🚀 How to Run
Clone the repository:
```bash
git clone https://github.com/your-username/churn-prediction-shap.git
cd churn-prediction-shap
