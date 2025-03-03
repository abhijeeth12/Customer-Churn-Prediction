# Customer Churn Prediction using ANN  

## Description  
This project focuses on predicting customer churn using an **Artificial Neural Network (ANN)** built with **TensorFlow/Keras**. Churn prediction is a critical task in customer retention, helping businesses identify customers likely to leave their service based on historical data.  

The dataset includes various customer attributes such as:  
- **Demographic Information** – Geography, Gender, Age  
- **Financial Data** – Credit Score, Balance, Estimated Salary  
- **Account Information** – Tenure, Number of Products, Active Membership Status  
- **Behavioral Insights** – Whether the customer has a credit card, and if they have exited  

Using these features, the model learns patterns that differentiate churned customers from retained ones.  

## Model Architecture  
- **Input Layer** → 11 neurons (for 11 input features)  
- **Hidden Layers** → Two hidden layers with **ReLU** activation  
- **Dropout Regularization** → Applied at each hidden layer to prevent overfitting  
- **Output Layer** → A single neuron with **sigmoid activation** for binary classification (Churn = 1, No Churn = 0)  
- **Optimizer** → Adam optimizer for adaptive learning rate  
- **Loss Function** → Binary Cross-Entropy for classification  

## Key Features & Techniques Used  
✅ **Data Preprocessing:**  
- Encodes categorical variables (e.g., Geography, Gender)  
- Normalizes numerical features for better training  

✅ **ANN Model with Regularization:**  
- Uses **Dropout layers** to prevent overfitting  
- Implements **Early Stopping** to monitor validation loss and halt training when improvement stagnates  

✅ **Evaluation Metrics:**  
- **Accuracy** – Measures how well the model classifies churned vs. non-churned customers  
- **Confusion Matrix & ROC Curve** – Helps visualize classification performance  

✅ **Hyperparameter Tuning:**  
- Adjustable **learning rate** for Adam optimizer  
- Flexible **batch size** and **epochs** for model training  
