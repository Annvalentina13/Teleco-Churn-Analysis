# Customer Churn Analysis Using Machine Learning

## 📌 Project Overview
Customer churn refers to customers discontinuing a service, which directly impacts
business revenue and growth. This project focuses on analyzing customer behavior
and building machine learning models to predict whether a customer is likely to churn.

The project follows an end-to-end data science workflow including data cleaning,
exploratory data analysis (EDA), feature engineering, model training, evaluation,
and business insights generation.

---

## 🎯 Objectives
- Analyze customer behavior patterns related to churn
- Identify key factors influencing customer churn
- Build and evaluate machine learning models for churn prediction
- Provide actionable business recommendations to reduce churn

---

## 📂 Dataset
The dataset used in this project is a **Telecom Customer Churn** dataset.

### Key Features:
- Customer demographic information
- Billing details (Monthly and Total Charges)
- Contract and payment information
- Service usage attributes
- Target variable: **Churn (Yes/No)**

Each row in the dataset represents a single customer.

---

## 🔄 Project Workflow
1. Business Understanding
2. Dataset Loading and Inspection
3. Data Cleaning and Preprocessing
4. Exploratory Data Analysis (EDA)
5. Correlation Analysis
6. Feature Engineering
7. Train-Test Split
8. Model Training (Logistic Regression & Random Forest)
9. Model Evaluation
10. Feature Importance Analysis
11. Business Insights and Conclusion

---

## 📊 Exploratory Data Analysis (EDA)
EDA was performed to understand customer behavior and churn patterns, including:
- Churn distribution analysis
- Contract type vs churn
- Tenure and monthly charges analysis
- Payment method and senior citizen analysis
- Correlation heatmap

Multiple visualizations were used to clearly identify trends and relationships.

---

## 🤖 Machine Learning Models
The following models were implemented:

### 1. Logistic Regression
- Used as a baseline classification model
- Provides interpretability and reference performance

### 2. Random Forest Classifier
- Captures non-linear relationships
- Improves churn prediction performance
- Provides feature importance insights

---

## 📈 Model Evaluation Metrics
Models were evaluated using:
- Accuracy
- Precision
- Recall
- Confusion Matrix
- ROC-AUC Curve

The Random Forest model demonstrated improved performance over Logistic Regression,
especially in identifying churned customers.

---

## 🔍 Key Insights
- Customers with **shorter tenure** are more likely to churn
- **Month-to-month contracts** show higher churn rates
- Higher **monthly charges** increase churn probability
- Long-term contracts significantly reduce churn
- Service usage and payment methods influence customer retention

---

## 💡 Business Recommendations
- Encourage customers to switch from monthly to long-term contracts
- Provide onboarding and engagement strategies for new customers
- Offer targeted discounts to high-risk customers with high monthly charges
- Use churn prediction to proactively engage at-risk customers

---

## 🛠️ Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📁 Repository Structure
- ├── Customer Churn Analysis.ipynb
- ├── Customer Churn.csv
- └── README.md

---

## 🚀 Conclusion
This project demonstrates how data analysis and machine learning can be effectively
applied to predict customer churn and support data-driven business decisions.
The insights derived can help organizations improve customer retention strategies
and reduce revenue loss.

---

## 👤 Author
**Annie Valentina A**  
