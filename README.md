# Customer Churn Dataset Analysis

This project explores a customer dataset from a financial institution, analyzing customer behavior and attributes to understand potential drivers for churn or retention.

## 📁 Files

- Jupyter Notebook containing data exploration, preprocessing, visualization, and analysis.
- Dataset containing details of over 110,000 customers, including their demographics and banking behavior.

## 📊 Dataset Features

The dataset has 13 columns:

- `id`: Unique identifier for the row
- `CustomerId`: Unique customer identifier
- `Surname`: Customer's last name
- `CreditScore`: Credit score (300–850 range)
- `Geography`: Country of residence (e.g., France, Germany)
- `Gender`: Male/Female
- `Age`: Customer's age
- `Tenure`: Years with the bank
- `Balance`: Account balance
- `NumOfProducts`: Number of bank products the customer uses
- `HasCrCard`: Whether the customer has a credit card (1: Yes, 0: No)
- `IsActiveMember`: Whether the customer is active (1: Yes, 0: No)
- `EstimatedSalary`: Estimated yearly salary

## 🎯 Objective

The goal is to explore this dataset to uncover customer patterns related to credit scores, product usage, activity status, and other financial indicators—possibly to support churn prediction or customer segmentation.

## 📈 Features in Notebook

- Data Cleaning and Summary Statistics
- Visual Analysis:
  - Distribution of Age, Credit Score, Balance
  - Gender and Geography Breakdown
  - Product Usage vs. Salary or Tenure
- Correlation heatmaps to identify related features

## 🧰 Libraries Used

- Python 3.8+
- tensorflow
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn
- Jupyter Notebook
  
