# Early Alzheimer’s Detection via Handwriting

This project predicts early signs of Alzheimer’s disease from handwriting benchmark tests using machine learning ensembles.  

## Problem
Detect early signs of Alzheimer’s from handwriting data. Ensemble approach reduces feature redundancy while maintaining predictive accuracy.

## Tech Stack
- Python 3.11+
- scikit-learn
- pandas, numpy
- XGBoost, LightGBM
- matplotlib / seaborn (optional for visualizations)

## Features
- PCA for dimensionality reduction
- Ensemble of Random Forest, Linear SVC, XGBoost, GaussianNB, Logistic Regression
- Cross-validation and evaluation metrics (accuracy, precision, recall, F1-score, specificity)
- Outputs PCA results in Excel

## Folder Structure
early-alzheimers-detection/
├─ src/
│ └─ gp2_ensemble_model_darwin_dataset.py
├─ data/
│ └─ data.csv
├─ collab notebook/
  └─GP2_Ensemble_Model_DARWIN_Dataset.ipynb
├─ results/
│ └─ PCA_Results.xlsx
├─ README.md
├─ requirements.txt
└─ .gitignore
