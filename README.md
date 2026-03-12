📊 Telecommunications Customer Churn Prediction

Machine learning project that analyzes customer data from a telecommunications company to predict customer churn and identify factors that influence customer retention.

The goal is to build a model that can help businesses identify customers likely to cancel their service before it happens.

📌 Project Overview

Customer churn represents a major challenge for telecommunications companies. Losing customers directly impacts revenue, and acquiring new customers is often more expensive than retaining existing ones.

This project explores customer behavior using data analysis and machine learning to:

Identify patterns associated with customer churn

Understand the factors that influence churn

Build predictive models capable of identifying high-risk customers

🛠️ Tools & Technologies

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Jupyter Notebook

📂 Dataset

The dataset contains customer information from a telecommunications company, including:

Demographic information

Service subscriptions

Contract type

Monthly charges

Customer tenure

Churn status

Each row represents one customer, and each column represents a feature used for analysis or prediction.

⚙️ Project Workflow
1️⃣ Data Exploration (EDA)

Initial analysis was performed to understand the dataset and detect patterns between churned and non-churned customers.

This step included:

Distribution analysis

Correlation analysis

Visualization of key variables

2️⃣ Data Cleaning

Data preparation included:

Handling missing values

Converting categorical variables

Ensuring data consistency

This step ensures the model learns meaningful patterns.

3️⃣ Feature Engineering

Relevant features were analyzed and transformed to improve predictive performance.

Examples include:

Customer tenure patterns

Billing behavior

Service combinations

4️⃣ Model Training

Several machine learning models were trained and evaluated:

Logistic Regression

Random Forest

Gradient Boosting

The dataset was split into training and testing sets to ensure proper evaluation.

5️⃣ Model Evaluation

Model performance was evaluated using classification metrics:

Accuracy

Precision

Recall

F1 Score

These metrics help assess how effectively the model identifies customers likely to churn.

📈 Results

The final model achieved strong predictive performance:

Precision: ~0.80

Recall: ~0.64

This indicates the model can effectively identify customers at risk of leaving while maintaining a reasonable balance between false positives and missed churn cases.

🎯 Key Insights

Customer tenure plays a major role in predicting churn

Contract type significantly impacts retention

Customers with month-to-month contracts are more likely to churn

Machine learning models can help businesses proactively identify at-risk customers
