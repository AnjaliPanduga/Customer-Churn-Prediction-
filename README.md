# Customer Churn Prediction Using Machine Learning & Streamlit

## 📌 Project Overview
Customer churn is a major challenge for subscription-based businesses such as telecom and SaaS companies.  
This project predicts whether a customer is likely to **churn or stay** using machine learning models and provides a user-friendly **Streamlit web application** for real-time prediction.

---

## ❓ Problem Statement
Customer churn occurs when customers stop using a company’s services.  
Many organizations struggle to identify customers who are at risk of leaving due to:
- Large volumes of customer data
- Complex customer behavior patterns
- Lack of predictive systems

As a result, businesses react **after** the customer has already churned, leading to revenue loss and increased customer acquisition costs.

---

## 💡 Solution Approach (How the Problem is Addressed)
This project addresses the churn problem by:
- Analyzing historical customer data to identify churn patterns
- Applying multiple machine learning algorithms to learn customer behavior
- Comparing models and selecting the best-performing one
- Predicting churn **before it happens**, enabling proactive retention strategies
- Providing an interactive Streamlit web application for easy usage by non-technical users

---

## 🚀 Key Features
- End-to-end Machine Learning workflow
- Multiple ML models trained and evaluated
- Best model selected based on accuracy
- Real-time customer churn prediction
- Simple and interactive web interface

---

## 🧠 Machine Learning Models Used
The following algorithms were implemented and compared:
- Logistic Regression  
- Decision Tree Classifier  
- Random Forest Classifier  
- Gradient Boosting Classifier  

### ✅ Best Performing Model
- **Gradient Boosting Classifier**
- Achieved the highest accuracy among all models
- Used as the final production model

---

## 🛠️ Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- Streamlit
- Joblib

---

## 📂 Project Structure
```
Customer-Churn-Prediction/
│
├── app.py
├── customer churn prediction.ipynb
├── final_gb_classifier.pkl
├── requirements.txt
├── README.md
└── .gitignore
```
