# preventive_maintenance_classifier

# Predictive Maintenance using Machine Learning

This project predicts whether a machine is likely to fail based on various sensor readings and conditions. The goal is to reduce downtime by anticipating failures.

## Dataset
The dataset contains sensor readings (e.g., temperature, pressure, vibration) and failure states (0: No failure, 1: Failure).

##  Problem Statement
Build a classification model that predicts machine failure with high accuracy.

##  Approach
- **Data Cleaning:** Handled missing values, checked imbalance.
- **EDA:** Explored feature relationships using heatmaps and bar plots.
- **Modeling:**
  - Used RandomForestClassifier.
  - Performed hyperparameter tuning with GridSearchCV.
  - Evaluated model using accuracy, F1-score, confusion matrix, and cross-validation.

## 🎯Results
- **Best Test Accuracy:** ~98.8%
- **Cross-Validation Accuracy:** ~98.75%
- **Balanced Precision and Recall across classes.**

##  Files
- `notebooks/`: Jupyter notebook with full code.
- `model/`: Optional trained model file.
- `requirements.txt`: Dependencies.

##  Future Work
- Try XGBoost or LightGBM for improved performance.
- Deploy using Streamlit or Flask.
