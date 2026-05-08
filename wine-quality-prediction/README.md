# Red Wine Quality Prediction (Vino Veritas)

## Project Overview
This project develops machine learning models to predict the quality of red wine based on its physicochemical properties. The goal is to provide winemakers with data-driven insights and actionable recommendations to optimize wine production quality.

## Key Results
- **Multi-class Classification** (Low / Medium / High quality): Tuned LightGBM achieved **88.8% accuracy**
- **Binary Classification** (Good vs Not Good): XGBoost achieved **90.4% accuracy**
- **Regression**: Best R² score of 0.464 (SVR with feature engineering)
- **Top Features**: Alcohol, Sulphates, Volatile Acidity

## Files in this folder
- `1. wine_quality_ml_models.ipynb` – Full model training and evaluation
- `2. wine_quality_conclusions.ipynb` – Dynamic conclusions and recommendations
- `summary_notebook.ipynb` – Summary analysis
- `winequality_red_cleansed.csv` – Cleansed dataset (985 samples)
- `Wine_Quality_Project_Report.docx` – Complete project report

## Business Impact
The model provides clear guidance on target chemical ranges (e.g., higher alcohol content, lower volatile acidity) that correlate with higher quality ratings.