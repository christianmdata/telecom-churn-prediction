📊 Telecommunications Customer Churn Prediction

Machine learning project that analyzes telecommunications customer data to predict churn and identify the key factors influencing customer retention.

The objective is to build a predictive model that helps businesses identify customers likely to cancel their service before it happens, allowing companies to take proactive retention actions.

🛠 Tools & Technologies

Python
Pandas
NumPy
Matplotlib / Seaborn
Scikit-learn
Jupyter Notebook

📂 Dataset

The dataset contains customer records from a telecommunications provider, including:

Demographic information
Service subscriptions
Contract type
Monthly charges
Customer tenure
Churn status

Each row represents a single customer, while the columns describe customer characteristics, service usage, billing information, and whether the customer eventually churned.

⚙️ Methodology
Data Exploration

Analyzed patterns and distributions across key variables:

Customer tenure

Monthly charges

Contract types

Service subscriptions

Visualization and correlation analysis were used to identify relationships between customer behavior and churn.

Data Cleaning

Prepared the dataset for modeling by:

Handling missing values

Converting categorical variables into numerical format

Ensuring data consistency across features

Proper data preparation ensures the model learns meaningful patterns from the data.

Feature Engineering

Analyzed and transformed features to improve predictive performance.

Key variables included:

Customer tenure
Billing behavior
Service combinations

These features help capture patterns related to customer engagement and service usage.

Modeling

Several machine learning classification models were trained and compared:

Logistic Regression

Random Forest

Gradient Boosting

The dataset was split into training and testing sets to evaluate model performance on unseen data.

Evaluation

Model performance was evaluated using classification metrics:

Accuracy
Precision
Recall
F1 Score
ROC-AUC

These metrics provide a balanced view of how effectively the model identifies customers likely to churn.

📈 Results

The final model demonstrated strong predictive performance:

Precision: ~0.80
Recall: ~0.64

This indicates the model can identify many customers at risk of leaving while maintaining a reasonable balance between false positives and missed churn cases.

Gradient Boosting achieved the best performance across the evaluated models.

🎯 Key Insights

Customer tenure is the strongest predictor of churn
Customers with shorter tenure are more likely to cancel their service
Contract type plays a significant role in customer retention
Customers on month-to-month contracts show higher churn rates

These insights highlight how machine learning models can help telecommunications companies proactively identify high-risk customers and improve retention strategies.
