# AIML Portfolio Projects

## Red Wine Quality Prediction (Vino Veritas)
Predicting wine quality from physicochemical properties using machine learning classification and regression models.

**Key Results:**
- Tuned LightGBM: 88.8% multi-class accuracy (Low/Medium/High quality)
- XGBoost: 90.4% binary accuracy (Good vs Not Good)
- Top predictive features: Alcohol content, Sulphates, Volatile Acidity

**Project Files:**
- Notebooks: `1. wine_quality_ml_models.ipynb`, `2. wine_quality_conclusions.ipynb`, `summary_notebook.ipynb`
- Dataset: `winequality_red_cleansed.csv`
- Final Report: `Wine_Quality_Project_Report.docx`

## Telco Customer Churn Prediction
Predicting customer attrition in the telecommunications sector using ensemble machine learning models.

**Key Results:**
- Best Model: Random Forest (F1-Score: 0.6374)
- ROC-AUC: approximately 0.84
- Key churn drivers: Month-to-month contracts, short customer tenure, absence of tech support

**Project Files:**
- Notebook: `Telco_Churn_Prediction_Notebook.ipynb`
- Final Report: `Telco_Churn_Project_Report.docx`

## Repository Structure
- `wine-quality-prediction/` – All files related to the wine quality prediction project
- `telco-churn-prediction/` – All files related to the telco churn prediction project
- `docs/` – Additional documentation and reports

## Tech Stack
- Python, Pandas, NumPy
- Scikit-learn, XGBoost, LightGBM
- Jupyter Notebooks
- Matplotlib / Seaborn for visualization

## Getting Started
1. Clone the repository: `git clone https://github.com/shriniketpatil-p/aiml-portfolio-projects.git`
2. Open the Jupyter notebooks in Jupyter Notebook, VS Code, or Google Colab
3. Review the detailed project reports (.docx) for methodology, results, and business recommendations

**Author:** Shriniket Patil  
**Organization:** Noblex Infinity Labs  
**Program:** AIML Data Science Accelerator