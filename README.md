# Stroke Risk Prediction

This project is focused on predicting the risk of stroke using machine learning techniques. The goal is to assist in early medical intervention by identifying individuals at higher risk.

## Objective
Build a predictive model to classify whether a person is likely to have a stroke based on health and demographic attributes.

## Dataset
- **Source**: Kaggle Stroke Prediction Dataset
- **Features** include: age, hypertension, heart disease, avg_glucose_level, BMI, smoking_status, etc.
- **Target**: `stroke` (1 = stroke, 0 = no stroke)

## Tools & Technologies
- Python, Pandas, NumPy
- Scikit-learn, XGBoost
- SMOTE (for handling class imbalance)
- Matplotlib, Seaborn
- Jupyter Notebook

## Key Steps
- Data cleaning & preprocessing
- Encoding categorical features
- Handling imbalanced data using SMOTE
- Model training with XGBoost
- Evaluation using accuracy, precision, recall, F1-score, and confusion matrix

##  Results
- **Best Accuracy**: ~90.4% at threshold = 0.4
- The model is good at identifying non-stroke cases, but improving recall for stroke cases is an area for further tuning.

## Files
- `stroke risk prediction.ipynb`: Full notebook with data preprocessing, modeling, and evaluation
- `README.md`: Project overview

## Future Improvements
- Hyperparameter tuning
- Try different classification algorithms (Random Forest, Logistic Regression, etc.)
- Deploy model as a web app

---

Feel free to explore the notebook and run the code to understand the full pipeline!
