# 💳 Financial Risk Analytics Dashboard

An end-to-end Financial Risk Analytics project that predicts customer default risk using Machine Learning and visualizes key financial insights through an interactive Power BI dashboard.

---

## 📖 Project Overview

This project analyzes customer credit data to identify default risk patterns and support data-driven financial decision-making.

The project demonstrates the complete analytics workflow:

- Data Cleaning
- Feature Engineering
- Machine Learning
- SQL Analysis
- SQLite Database
- Power BI Dashboard
- Business Intelligence Reporting

---

## 🎯 Objectives

- Predict customer default risk using Machine Learning
- Analyze customer credit behavior
- Identify high-risk customer segments
- Build an interactive dashboard for business users
- Support financial risk assessment

---

## 📊 Dataset

- UCI Credit Card Default Dataset
- 30,000 customer records
- 24 original attributes
- Additional engineered financial features

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- SQLite
- SQL
- Power BI
- Google Colab
- Git & GitHub

---

## ⚙️ Machine Learning Models

### Logistic Regression

- Accuracy: **80.97%**

### Random Forest Classifier

- Accuracy: **80.98%**

Random Forest was selected as the final prediction model due to its stronger overall performance.

---

## 📈 Feature Engineering

Created additional business features including:

- Total Bill Amount
- Total Payment
- Average Payment Delay
- Credit Usage Ratio
- Predicted Default
- Risk Level

---

## 📊 Power BI Dashboard

The interactive dashboard includes:

### KPI Cards

- Total Customers
- Total Defaults
- Default Rate
- Average Credit Limit
- Average Bill
- Average Payment

### Visualizations

- Risk Level Distribution
- Default Customers by Education
- Default Customers by Gender
- Default Customers by Age Group
- Credit Limit Distribution
- Payment Delay Analysis

### Interactive Filters

- Gender
- Education Level
- Age Group
- Risk Level

---

## 📷 Dashboard Preview

> Add your dashboard screenshot here.

Example:

![Dashboard](images/dashboard.png)

---

## 📁 Project Structure

```text
Financial-Risk-Analytics-Dashboard/
│
├── data/
├── notebook/
├── powerbi/
├── database/
├── images/
├── README.md
```

---

## 📌 Key Insights

- Default Rate: **22.12%**
- Low-risk customers represent approximately 80% of the dataset.
- University-educated customers form the largest customer segment.
- Customers with longer payment delays have a higher likelihood of default.
- Credit usage ratio and payment history are among the most influential predictive features.

---

## 🚀 Future Improvements

- Hyperparameter tuning
- XGBoost implementation
- SHAP explainability
- Real-time dashboard integration
- Cloud deployment using Azure or AWS
- Automated data refresh

## 👤 Author

**Eric Rathod**

Master of Artificial Intelligence – Design and Development

Seneca Polytechnic

💻 GitHub: https://github.com/EricRathod
