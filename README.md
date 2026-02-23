# Machine Learning Project | Classification | Customer Analytics
# Customer-Churn-Telecom-ML
This project predicts customer churn using Machine Learning models. The goal is to identify customers likely to leave so that businesses can take preventive action.
# Telco Customer Churn dataset from kaggle.
# Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Seaborn
- Matplotlib
# EDA Insights
- Dataset is imbalanced (73% No Churn, 27% Churn)
- Contract type strongly affects churn
- MonthlyCharges and TotalCharges are correlated
# Model Used
Logistic Regression (5000 iterations)
- Accuracy: 78.4%
- Recall(Churn): 47%
- Precision: 63%
- F1-score: 0.54
# Random Forest
- Accuracy: 79.1%
- Recall: 45%
- Precision: 66%
- F1-score: 0.54
# Conclusion
Although Random Forest achieved slightly higher accuracy, Logistic Regression achieved higher recall for churners, making it more suitable for business use where identifying at-risk customers is critical.
