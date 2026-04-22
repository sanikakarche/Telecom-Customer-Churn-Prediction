# 📊 Telecom Customer Churn Prediction

## 📌 Project Overview
Customer churn is a critical metric in the telecom industry, where annual attrition rates typically range between **15-25%**. This project focuses on identifying "high-risk" customers likely to leave the service by leveraging machine learning classification.

By predicting churn early, companies can implement targeted retention strategies, reducing acquisition costs and improving long-term customer loyalty.

## 🎯 Objectives
* **Quantify Churn:** Identify the percentage of customers transitioning away from the service.
* **Feature Analysis:** Analyze demographic and service-related factors contributing to attrition.
* **Predictive Modeling:** Evaluate multiple Machine Learning models to accurately classify potential churn.

## 📂 Dataset Analysis
The project utilizes the **Telco Customer Churn** dataset, covering:
* **Demographics:** Gender, age, partners, and dependents.
* **Services:** Phone, multiple lines, internet (DSL/Fiber optic), and security add-ons.
* **Account Info:** Tenure, contract type, payment method, and billing preferences.

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn (Logistic Regression, KNN, Random Forest, AdaBoost, Gradient Boosting)

## 📊 Key Insights
* **Contract Risk:** 75% of customers on Month-to-Month contracts churned, compared to only 3% for Two-Year contracts.
* **Service Type:** Fiber optic users show a significantly higher churn rate, suggesting potential service dissatisfaction.
* **Support Gap:** Customers without Tech Support or Online Security are the most likely to migrate to competitors.

## ⚙️ Model Performance
I implemented a **Voting Classifier** ensemble to maximize predictive power, combining Gradient Boosting, Logistic Regression, and AdaBoost.

### **Final Results (K-Fold Cross Validation):**

| Model | Accuracy Score |
| :--- | :--- |
| **Voting Classifier (Ensemble)** | **84.68%** |
| Gradient Boosting | 84.46% |
| AdaBoost | 84.45% |
| Logistic Regression | 84.13% |

## 🚀 Future Scope
* **API Integration:** Wrapping the model in a FastAPI backend for real-time churn scoring.
* **Automation:** Integrating predictions into a CRM dashboard for automated marketing triggers.

---

## 👤 Author
**Sanika** *Full-Stack Developer & AI Enthusiast* Specializing in Web Development, Hardware-AI Integration, and Data-Driven Solutions.

[LinkedIn](https://www.linkedin.com/in/sanika-karche) | [GitHub](https://github.com/sanikakarche)
Development, Hardware-AI Integration (NeuralKrushi), and Data-Driven Solutions.

LinkedIn: https://www.linkedin.com/in/sanika-karche | GitHub: https://github.com/sanikakarche
