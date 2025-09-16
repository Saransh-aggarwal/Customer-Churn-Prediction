# Customer-Churn-Prediction
A machine learning project to predict customer churn using Python, Scikit-Learn, and Power BI.

# Telecom Customer Churn Prediction

## 1. Project Overview & Business Problem

This project is an end-to-end data science analysis aimed at predicting customer churn for a fictional telecom company. Customer churn is a critical metric for subscription-based businesses, and by identifying customers who are likely to leave, the company can proactively implement targeted retention strategies to reduce revenue loss and improve customer loyalty.

## 2. Data Source

The dataset used is the **"Telco Customer Churn"** dataset, originally sourced from Kaggle. It contains demographic and account information for approximately 7,000 customers.

## 3. Tools & Technologies

* **Data Analysis & ML:** Python, Pandas, Scikit-Learn, Matplotlib, Seaborn
* **Data Visualization:** Power BI
* **Version Control:** Git & GitHub

## 4. Methodology

The project followed a standard data science workflow:
1.  **Exploratory Data Analysis (EDA):** Investigated relationships between various customer attributes (contract type, tenure, monthly charges) and churn.
2.  **Data Preprocessing:** Handled missing values, encoded categorical features using One-Hot and Label Encoding, and scaled numerical features with `StandardScaler`.
3.  **Model Building:** Trained and evaluated three classification models: Logistic Regression, Random Forest, and XGBoost.
4.  **Model Evaluation:** The Random Forest model was selected as the final model due to its strong performance, achieving an **accuracy of 82%**.

## 5. Interactive Dashboard & Key Insights

An interactive dashboard was developed in Power BI to summarize the key findings for business stakeholders. The analysis revealed three primary drivers of churn:

* **Month-to-Month Contracts Drive Churn:** Customers on flexible monthly contracts are over 4 times more likely to churn than those on two-year contracts.
* **New Customers Are a High-Risk Segment:** Churn is highest among new customers, particularly within the first year of service.
* **High Monthly Charges Increase Churn:** Customers with higher-than-average monthly bills are more likely to seek cheaper alternatives.

### Dashboard Preview
![Customer Churn Dashboard](https://github.com/Saransh-aggarwal/Customer-Churn-Prediction/blob/main/image.png)

## 6. Business Recommendations

Based on the insights, the following actions are recommended:
* Launch a targeted campaign to incentivize month-to-month customers to switch to one or two-year contracts.
* Implement a "First 90 Days" onboarding program to improve the experience for new customers.
* Proactively offer personalized discounts or bundle packages to high-spending customers identified by the model as "high-risk."
