Customer Churn Prediction Model 🚀

This repository contains a machine learning model that predicts customer churn based on various demographic, financial, and activity-related factors. The dataset includes key customer details such as credit score, geography, age, account balance, and transaction behavior.

📌 Features & Dataset Overview
The dataset consists of 14 columns, where the target variable is Exited (1 = Churned, 0 = Retained).

RowNumber, CustomerId, Surname → Unique identifiers (not used in modeling).
CreditScore → A customer's credit rating.
Geography → Country of residence.
Gender → Male/Female.
Age → Customer's age.
Tenure → Number of years with the bank.
Balance → Account balance.
NumOfProducts → Number of products the customer holds.
HasCrCard → Whether the customer has a credit card (1 = Yes, 0 = No).
IsActiveMember → Whether the customer is an active bank member (1 = Yes, 0 = No).
EstimatedSalary → Estimated annual income.
Exited → Target variable (1 = Churned, 0 = Retained).
📊 Machine Learning Approach
Preprocessing: Data cleaning, feature scaling, and encoding categorical variables.
Models Used: Logistic Regression, Decision Trees, Random Forest, XGBoost, and Neural Networks.
Evaluation Metrics: Accuracy, Precision, Recall, F1-Score, and ROC-AUC Curve.
🔧 Installation & Usage
bash
Copy
Edit
git clone https://github.com/abhijeeth12/Customer-Churn-Prediction.git
cd Customer-Churn-Prediction
pip install -r requirements.txt
python churn_model.py
📜 Results & Insights
Customers with higher ages and lower activity levels are more likely to churn.
Having multiple bank products and a higher credit score reduces churn probability.
📢 Contributions & Contact
Feel free to fork, modify, and improve the model. Open for collaboration!
📩 Contact: abhijeethchandragi@gmail.com
