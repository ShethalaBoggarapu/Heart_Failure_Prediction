
# 📊 Heart Failure Prediction - Results Summary

This project explores the application of machine learning models to predict heart failure based on patient clinical records. It includes evaluation, interpretability, and comparative model insights.

---

## ✅ Models Evaluated

- **Logistic Regression**
- **Decision Tree**
- **Random Forest**
- **XGBoost**

All models were tested with:
- Raw data
- Normalized data
- Hyperparameter tuning

---

## 📈 Model Performance Summary

![Model Comparison Table](model_comparison_table.png)

- **Random Forest** achieved highest accuracy: **89.13%**
- **XGBoost** followed with **85.38%**
- Preprocessing and tuning significantly boosted model performance

---

## 🔬 Feature Importance & Interpretability

### 🔹 ELI5 - Logistic Regression Weights
![Logistic Regression ELI5](eli5_logistic_weights.png)

### 🔹 ELI5 - Logistic Regression Prediction Breakdown
![Logistic Regression Prediction](eli5_logistic_prediction.png)

### 🔹 ELI5 - Decision Tree Feature Importance
![Decision Tree ELI5](eli5_tree_weights.png)

### 🔹 Decision Tree Visual Structure
![Tree Structure](decision_tree_structure.png)

### 🔹 ELI5 - XGBoost and Random Forest Weights
![XGBoost & RF ELI5](eli5_xgb_rf_weights.png)

### 🔹 LIME - Random Forest Local Explanation
![LIME RF](lime_rf_instance_explainer.png)

### 🔹 SHAP Summary Plot
![SHAP Plot](shap_summary_plot.png)

---

## 🎯 Predictions Comparison

The following visual shows model prediction probabilities for test instances:

![Prediction Probabilities](model_prediction_probs.png)

---

## 📊 Visual Insights

- Tableau heatmap (`heatmap.png`) shows feature correlation
- Notebook includes additional visualizations for each modeling step

---

## 🧾 Conclusion

- Ensemble models with feature explainability tools (ELI5, SHAP, LIME) deliver strong predictive power and transparency
- **Random Forest** + **SHAP/ELI5** combination provided the best tradeoff between accuracy and explainability

---

**Author**: Shethala Boggarapu
