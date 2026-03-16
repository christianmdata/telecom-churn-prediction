# 📊 Telecommunications Customer Churn Prediction

This project applies **machine learning to predict customer churn** for a telecommunications company. The goal is to identify customers who are likely to cancel their service so that businesses can take proactive steps to improve retention.

Customer churn is a major challenge for subscription-based companies. Losing customers directly impacts revenue, and acquiring new customers is often more expensive than retaining existing ones. By analyzing customer behavior and service usage patterns, this project builds predictive models capable of identifying high-risk customers.

---

## 🛠 Tools & Technologies

- Python  
- Pandas  
- NumPy  
- Matplotlib / Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## 📂 Dataset

The dataset contains customer records from a telecommunications provider and includes:

- Customer demographics  
- Service subscriptions  
- Contract type  
- Billing information (monthly and total charges)  
- Customer tenure  
- Churn status  

Each row represents a customer and each column represents a feature used for analysis or prediction.

---

## ⚙️ Methodology

### Data Exploration

Exploratory Data Analysis (EDA) was performed to understand customer behavior and identify patterns related to churn. Key variables such as tenure, monthly charges, and contract types were analyzed using statistical summaries and visualizations.

### Data Preparation

The dataset was cleaned and prepared for modeling by:

- Handling missing values  
- Converting categorical variables into numerical format  
- Ensuring consistent data types  

Proper preprocessing ensures that machine learning models can effectively learn patterns from the data.

### Feature Analysis

Key features influencing churn were analyzed, including:

- Customer tenure  
- Billing behavior  
- Service combinations  
- Contract type  

These features provide insights into customer engagement and retention risk.

### Model Training

Several machine learning classification models were trained and compared:

- Logistic Regression  
- Random Forest  
- Gradient Boosting  

The dataset was split into training and testing sets to ensure reliable model evaluation.

### Model Evaluation

Models were evaluated using multiple classification metrics:

- Accuracy  
- Precision  
- Recall  
- F1 Score  
- ROC-AUC  

These metrics provide a balanced understanding of how effectively the models identify customers likely to churn.

---

## 📈 Results

The final model demonstrated strong predictive performance:

| Metric | Score |
|------|------|
| Precision | ~0.80 |
| Recall | ~0.64 |
| ROC-AUC | ~0.90 |

The **Gradient Boosting model** performed best overall and was selected as the final model.

---

## 🎯 Key Insights

Analysis revealed several important factors influencing churn:

- **Customer tenure** is the strongest predictor of churn  
- Customers with **shorter tenure are significantly more likely to leave**  
- **Contract type** strongly affects retention  
- Customers on **month-to-month contracts show higher churn risk**  

These insights highlight how machine learning can help telecommunications companies identify at-risk customers and improve retention strategies.

---

## 🚀 Project Outcome

This project demonstrates how machine learning can be used to **predict customer churn and extract actionable business insights** from customer data.

By identifying customers at risk of leaving, businesses can take proactive actions such as targeted promotions, service improvements, or loyalty programs to improve customer retention.
