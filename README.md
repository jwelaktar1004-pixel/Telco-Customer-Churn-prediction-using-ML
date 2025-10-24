Project Title: Customer Churn Prediction using Machine Learning
🎯 Objective:

To predict which telecom customers are likely to leave (churn) so the company can take retention actions in advance.

🧠 Work Done (My Contributions)

Collected and analyzed Telco Customer Churn Dataset from Kaggle.

Performed data cleaning & preprocessing (handled missing values, converted data types).

Applied feature engineering & encoding on categorical variables.

Used DBSCAN for outlier detection to identify unusual customers.

Scaled numerical features using StandardScaler for better model performance.

Split dataset into training (80%) and testing (20%) sets.

Trained multiple models and finalized Random Forest Classifier for prediction.

Evaluated model using Accuracy, Recall, Precision, and F1-Score metrics.

Visualized churn trends using Pie Chart, Tree Map, and PCA Scatter Plot.

Generated business insights from model results to support customer retention strategy.


📊 Results & Performance

Achieved 82% Accuracy and 74% Recall in predicting churn customers.

Model successfully identified majority of high-risk customers.

Outliers detected through DBSCAN (<5%) analyzed separately.


💡 Key Insights

Short-tenure and month-to-month contracts have highest churn rates.

Fiber optic users with high monthly charges are more likely to leave.

Customers with long-term contracts or automatic payments are more loyal.

Business can reduce churn by offering discounts or loyalty plans to short-tenure users.


🔍 Prediction Summary

Predicted whether each customer will churn (Yes/No) using Random Forest.

Created a predictions file (with customer ID, actual, and predicted churn).

Visualized predicted churn distribution with pie charts.


🧰 Tools & Techniques Used

Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, DBSCAN, RandomForestClassifier, PCA

🏁 Outcome

A machine learning model that helps the telecom company identify at-risk customers early, enabling targeted offers and improving customer retention.
