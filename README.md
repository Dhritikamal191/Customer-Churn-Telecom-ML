# Machine Learning Project | Classification | Customer Analytics
# Customer-Churn-Telecom-ML
Customer churn significantly impacts revenue for subscription-based businesses.
This project builds machine learning models to predict whether a customer is likely to churn, enabling proactive retention strategies.
    The objective is not just high accuracy- but effectively identifying at-risk customers.
# Dataset
- Dataset: Telco Customer Churn (Kaggle)
- Total Records: 7043
- Target Variable: Churn(Yes/No)
- Class Distribution:
- - No:~73%
  - Yes:~27% (Imbalanced dataset)
# EDA Insights
Key findings:
- Month-to-month contract customers show significantly higher churn.
- Higher MonthlyCharges correlate with churn.
- Dataset is imbalanced->recall becomes more important than raw accuracy.
- After one-hot encoding, dataset expanded to 7061 features.
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
# Model Evaluation Insights
- Random Forest achieved slightly higher overall accuracy.
- Logistic Regression achieved higher recall for churners.
- Since churn prediction prioritizes minimizing missed churners, recall is critical.
- Both models achieved similar F1-scores, indicating comparable overall balance.
# Final Model Selection
Logistic Regression was preferred due to slightly higher recall, making it more aligned with business objectives of minimizing customer loss.
# Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
# Business Impact
By identifying 47% of potential churners:
- Marketing teams can target high-risk customers
- Customer retention stratagies can be optimized
- Revenue loss can be reduced proactively
# Visualizations included
- Target distribution plot
- Correlation heatmap
- Contract vs Churn analysis
- Confusion matrices
- ROC curve
- Feature importance (Random Forest)
# Data Preprocessing
- Converted TotalCharges to numeric
- Handled missing values
- One-hot encoded categorial variables
- Train-test split: 80/20
- Feature scaling for Logistic Regression
- Class imbalance handled using class_weight='balanced'
# Future Improvements 
- Hyperparameter turning (GridSearchCV)
- Threshold turning for better recall/precision balance
- SMOTE for class imbalance
- Try XGBoost/Gradient Boosting
# Author
Dhritikamal Das


Machine Learning Enthusiast | Data Science Learner
