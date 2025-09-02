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

/<img width="866" height="497" alt="shap_beeswarm" src="https://github.com/user-attachments/assets/691b708f-8ae0-4d69-a3ab-ff003f63a198" />


**The SHAP Beeswarm Plot shows which features have the highest overall impact on predicting employee attrition.


*OverTime, TotalWorkingYears, and YearsAtCompany were among the most influential.

*Red = pushes towards higher attrition probability

*Blue = pushes towards lower attrition probability

### 🔹 Local Explanation (Force Plot Example)

<img width="860" height="180" alt="shap_froce_example" src="https://github.com/user-attachments/assets/7ccb76ab-3d53-4529-9924-549440df4388" />


**The SHAP Force Plot breaks down why the model predicted attrition for one employee:

*Positive (red) features increase the likelihood of attrition.
*Negative (blue) features decrease it.

This helps HR teams understand individual risk factors behind predictions.
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
