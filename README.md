# AIML Portfolio Projects

This repository contains end-to-end machine learning projects developed as part of the AIML Data Science Accelerator program at Noblex Infinity Labs.

## Red Wine Quality Prediction (Vino Veritas)

**Project Overview**  
Developed machine learning models to predict red wine quality scores based on 11 physicochemical properties. The project evaluated both classification (binary and multi-class) and regression approaches.

**Key Results**  
- Multi-class classification (Low/Medium/High): LightGBM (Tuned) – 88.8% accuracy  
- Binary classification (Good vs Not Good): XGBoost – 90.4% accuracy  
- Most important features: Alcohol content, Sulphates, Volatile Acidity

**Project Files**  
- Notebooks: `wine-quality-prediction/1. wine_quality_ml_models.ipynb`, `2. wine_quality_conclusions.ipynb`, `summary_notebook.ipynb`  
- Dataset: `winequality_red_cleansed.csv`  
- Final Report: `Wine_Quality_Project_Report.docx`

**Business Impact**  
Provides data-driven recommendations to winemakers for optimizing chemical composition to improve wine quality.

## Telco Customer Churn Prediction

**Project Overview**  
Built and compared multiple classification models to predict customer churn for a telecommunications company using customer demographics, account information, and service usage data.

**Key Results**  
- Best performing model: Random Forest (F1-Score: 0.6374)  
- ROC-AUC: ~0.84  
- Primary churn drivers: Month-to-month contracts, short tenure, lack of tech support, electronic check payment method

**Project Files**  
- Notebook: `telco-churn-prediction/Telco_Churn_Prediction_Notebook.ipynb`  
- Final Report: `Telco_Churn_Project_Report.docx`

**Business Impact**  
Enables proactive customer retention strategies and targeted interventions to reduce churn and protect revenue.

## Repository Structure
- `wine-quality-prediction/` – Red wine quality prediction project files
- `telco-churn-prediction/` – Telco customer churn prediction project files
- `docs/` – Additional documentation

## Technologies Used
- Python, Pandas, NumPy
- Scikit-learn, XGBoost, LightGBM
- Jupyter Notebooks
- Matplotlib and Seaborn for data visualization

## Author
Shriniket Patil  
Noblex Infinity Labs | AIML Data Science Accelerator

---
Detailed methodology, model evaluation, and business recommendations are available in the respective project reports.
