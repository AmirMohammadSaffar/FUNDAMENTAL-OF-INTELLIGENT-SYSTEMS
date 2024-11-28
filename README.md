🌟 Mini Project #1 - Fundamentals of Intelligent Systems

This project contains two main parts, corresponding to Questions 1 and 2 of the assignment for the Fundamentals of Intelligent Systems course.

🔍 Question 1: Predicting Customer Churn

In this part, we use a dataset related to customer information to predict which customers are likely to stop using the service.

📊 Project Overview

Data Exploration 🧐: Analyze customer data such as age, income, and account details.

Data Preprocessing 🛠️: Apply One-Hot Encoding to categorical features, handle missing values, and balance the dataset.

Machine Learning Models 🤖: Train different models, including Logistic Regression and Random Forest, to predict customer churn.

Handling Imbalanced Data ⚖️: Use SMOTE to balance the dataset and improve the model's ability to predict minority classes.

Model Evaluation 📈: Compare model performance with metrics like Precision, Recall, F1-score, and ROC-AUC.

📂 Dataset

The dataset contains the following features:

Client Number 🔢: Unique identifier for each customer.

Attrition Flag 🚩: Indicates if the customer is continuing or has stopped services.

Demographic Information 👥: Age, gender, marital status, etc.

Account Details 💳: Credit limit, number of transactions, average utilization, etc.

🧠 Key Concepts

Regularization 🔒: We used L2 Regularization (Ridge) to prevent overfitting.

Imbalanced Data Handling ⚖️: Balanced the dataset with SMOTE to improve accuracy in predicting both classes.

Model Comparison ⚙️: Compared model performance before and after balancing the dataset.

📊 Results

Model

Accuracy Before

Accuracy After

Logistic Regression

0.69

0.86

Random Forest

0.94

0.97

The results show improved performance in identifying customers likely to stop services after balancing the dataset.

🔄 Question 2: Polynomial Regression with Regularization

In this part, we explore polynomial regression with regularization techniques to reduce overfitting and improve model performance.

📊 Project Overview

Polynomial Regression 📐: Fit polynomial models with different degrees to see their impact on model accuracy.

Manual Regularization ✋🔒: Apply L2 regularization manually to prevent overfitting.

Model Comparison 🤖⚖️: Compare different regression models (Linear, Ridge, Decision Tree).

📂 Dataset

The dataset is a simple one-dimensional array stored in data.npy.

Place the dataset in the appropriate location, such as /content/data.npy in Google Colab.

🧠 Key Concepts Implemented

Polynomial Regression 📐: Fit models of different degrees to observe their performance.

Manual Regularization ✋🔒: Implement L2 regularization manually to control model complexity.

Model Comparison ⚙️: Compare Linear Regression, Ridge Regression, and Decision Tree Regression.

📊 Results and Observations

Training and Test Error 📉: Compare errors for different models and polynomial degrees to understand overfitting.

Regularization Impact 🔒: See how regularization helps in reducing overfitting.

🚀 Future Improvements

Cross-Validation 🔄: Add cross-validation to evaluate models more robustly.

Hyperparameter Tuning 🎛️: Use Grid Search to find the best model parameters.

Explore Other Models 🌲: Try models like Random Forest or Support Vector Regression.

📜 License

This project is licensed under the MIT License.

🙏 Acknowledgments

Thanks to Scikit-Learn for providing the machine learning tools used in this project.

