🌺# Predicting Menopause Symptom Severity with Machine Learning
Exploratory data analysis of open datasets related to menopause, symptoms and health impact using Python.
# Project Overview


Menopause is a critical phase in many women's lives where symptom burden varies widely. This project develops and evaluates machine learning models to predict severe menopause symptoms from demographic, clinical, and lifestyle variables. The aim is to provide interpretable risk predictions that could inform early interventions or targeted follow-up in clinical practice.

Key themes: women’s health, clinical data science, interpretability (SHAP), and ethical AI.

## 🎯 Objectives
Build an interpretable machine learning pipeline to classify whether a woman is likely to experience severe menopause symptoms (binary classification) within a defined time window, based on features such as age, BMI, hormonal markers, lifestyle factors, and comorbidities.

Primary outcomes:

Compare model performance (Logistic Regression, Random Forest, Gradient Boosting/XGBoost).

Evaluate models using balanced metrics (ROC-AUC, F1-score, balanced accuracy).

Provide clinical interpretation using SHAP and feature importance.

Discuss bias, limitations, and clinical applicability.

  
##🗂️ Dataset


Recommended dataset: Menopause Symptoms Severity Dataset (Kaggle) — or any similar dataset containing demographic, lifestyle, clinical and symptom severity fields.

Data notes:

Include a brief data/README.md with dataset provenance, license, preprocessing steps and column descriptions.

Ensure removal of direct identifiers and follow privacy/ethical constraints.

If dataset is not public, include a synthetic sample or instructions to obtain data.

Columns (example):

age, bmi, smoking_status, physical_activity, hormone_level_X, comorbidity_Y, symptom_score, symptom_severity (target: mild/moderate/severe or binarized to severe_yes/no).

##🧭 Methodology / Pipeline

Data loading & cleaning

Handle missing values (imputation strategy will be documented).

Validate and correct inconsistent entries.

Exploratory Data Analysis (EDA)

Distribution of features, symptom severity prevalence.

Correlation analysis and potential collinearity.

Preprocessing & Feature Engineering

Numeric scaling (StandardScaler/RobustScaler).

Categorical encoding (One-Hot / Target encoding if necessary).

Create derived features (age groups, lifestyle index, comorbidity counts).

Modeling

Models: Logistic Regression (baseline), Random Forest, Gradient Boosting (XGBoost / LightGBM).

Cross-validation with stratified folds.

Hyperparameter tuning (GridSearchCV / RandomizedSearchCV).

Evaluation

Metrics: ROC-AUC, Precision, Recall, F1-score, Confusion Matrix, Balanced Accuracy.

Calibration plot and decision thresholds if needed.

Interpretability

SHAP values to explain individual and global feature importance.

Partial Dependence Plots for actionable insights.

Reporting

Document findings, limitations, and reproducible steps.

Save final model and example inference script.








## 📌 Next steps
- Add datasets (WHO, CDC, Kaggle, NHANES).
- Develop first exploratory notebook.
- Publish first visualizations.

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


## Links
- [Interactive Notebook](https://github.com/umanaevelyn/google-advanced-data-analytics-capstone/blob/main/Salifort_Motors_Capstone.ipynb.ipynb)  
- [Pretty view on nbviewer – recommended!](https://nbviewer.org/github/umanaevelyn/google-advanced-data-analytics-capstone/blob/main/Salifort_Motors_Capstone.ipynb.ipynb) 
- [Full Portfolio](https://umanaevelyn.github.io/) • [LinkedIn](https://www.linkedin.com/in/evelynrpumana)

© 2025 Evelyn Roxana Perez Umana
