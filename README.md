
# 🫀 Heart Failure Prediction

This project focuses on predicting heart failure using patient clinical data via machine learning. It uses classification algorithms, model interpretability methods, and visualizations to deliver accurate and explainable results.

---

## 📊 Dataset

- **Source**: [Kaggle - Heart Failure Clinical Records](https://www.kaggle.com/datasets/andrewmvd/heart-failure-clinical-data)
- **Rows**: 299
- **Features**: 13 clinical measurements
- **Target**: DEATH_EVENT (binary)

---

## ⚙️ Technologies Used

- **Languages**: Python
- **Libraries**: pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost, eli5, lime, shap
- **Visualization**: Tableau, SHAP, LIME, ELI5
- **Notebook Environment**: Jupyter

---

## 🚀 Project Highlights

- Evaluated 4 ML models: Logistic Regression, Decision Tree, Random Forest, XGBoost
- Tuned hyperparameters using GridSearchCV
- Applied normalization and observed effect on model performance
- Extracted feature importance using ELI5, SHAP, LIME
- Created Tableau dashboard for correlation heatmap

---

## 📂 Repository Structure

```
heart-failure-prediction/
│
├── heart_failure_pred.ipynb           # Jupyter notebook
├── requirements.txt                   # Dependencies
├── LICENSE                            # MIT License
├── README.md                          # Project overview
├── RESULTS.md                         # Results and insights
├── heatmap.png                        # Tableau correlation heatmap
├── model_comparison_table.png         # Metrics summary
├── prediction_probabilities.png       # Model output comparison
├── eli5_logistic_weights.png          # ELI5 weights for Logistic Regression
├── eli5_logistic_prediction.png       # Local prediction breakdown (LogReg)
├── decision_tree_structure.png        # Decision Tree diagram
├── eli5_tree_weights.png              # Feature weights from Decision Tree
├── eli5_xgb_rf_weights.png            # ELI5 weights (XGB/RF)
├── lime_rf_instance_explainer.png     # LIME explanation for RF
└── shap_summary_plot.png              # SHAP summary plot
```

---

## 🧾 License

This project is licensed under the [MIT License](LICENSE)

---

**Author**: Shethala Boggarapu
