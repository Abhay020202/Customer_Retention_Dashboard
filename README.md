# Telecom Customer Retention Dashboard

## Project Overview
This project focuses on analyzing telecom customer data to address key challenges in retention and churn management. Using Power BI dashboards created from the provided dataset, the analysis visualizes customer demographics, service utilization, and churn risk indicators. The goal is to identify factors affecting customer retention and enable proactive measures to reduce churn rates.

---
## Problem Statement
- **Customer Acquisition Challenge**: Customers in the telecom industry are hard-earned, making it critical to prevent churn and retain existing users.
- **Current Approach**:
   - The retention department gets in touch with customers only after they have already terminated their contracts. This reactionary approach limits the ability to prevent churn proactively.
   - Previous customer analyses using Excel have proven ineffective and inconclusive, ending in dead-ends.
- **Need for Insights**:
   - A clear understanding of customer behavior and risks, presented through actionable, self-explanatory visualizations, is required for management to implement effective strategies.
---
## Dataset Description
The dataset, provided by the Retention Manager, includes the following columns:
- **customerID**: Unique identifier for each customer.
- **gender**: Gender of the customer (Male/Female).
- **SeniorCitizen**: Indicates whether the customer is a senior citizen (1: Yes, 0: No).
- **Partner**: Indicates if the customer has a partner (Yes/No).
- **Dependents**: Indicates if the customer has dependents (Yes/No).
- **tenure**: Number of months the customer has been with the company.
- **PhoneService**: Indicates whether the customer subscribes to phone service (Yes/No).
- **MultipleLines**: Indicates if the customer has multiple phone lines (Yes/No/No phone service).
- **InternetService**: Type of internet service (DSL/Fiber optic/No internet).
- **OnlineSecurity**: Subscription to online security service (Yes/No/No internet).
- **OnlineBackup**: Subscription to online backup service (Yes/No/No internet).
- **DeviceProtection**: Subscription to device protection service (Yes/No/No internet).
- **TechSupport**: Subscription to tech support service (Yes/No/No internet).
- **StreamingTV**: Indicates subscription to streaming TV service (Yes/No/No internet).
- **StreamingMovies**: Indicates subscription to streaming movies service (Yes/No/No internet).
- **Contract**: Contract type (Month-to-month/One year/Two year).
- **PaperlessBilling**: Indicates if the customer uses paperless billing (Yes/No).
- **PaymentMethod**: Method of payment (Electronic check/Mailed check/Bank transfer/Credit card).
- **MonthlyCharges**: Monthly charges incurred by the customer.
- **TotalCharges**: Total charges incurred by the customer.
- **numAdmin**: Number of admin tickets raised by the customer.
- **numTech**: Number of tech tickets raised by the customer.
- **Churn**: Indicates if the customer has churned (Yes/No).

---

## Key Insights

1. **Demographic Trends**:
   - Gender distribution is nearly equal, with senior citizens (25.47%) showing higher retention.
   - Customers with dependents exhibit stronger retention rates.

2. **Churn Drivers**:
   - Month-to-month contracts have an 88.55% churn rate, while two-year contracts show higher loyalty.
   - Electronic check payments (57.30% churn) and high monthly charges drive higher churn risks.

3. **Service Usage**:
   - PhoneService has the highest adoption (90.90%), while OnlineSecurity and TechSupport show low usage, correlating with higher churn.
   - Fiber optic internet users account for the highest churn (69.40%), signaling service concerns.

4. **Retention Patterns**:
   - Short-tenure customers (<1 year) are more likely to churn, while those with tenure >6 years show strong loyalty.
   - Unresolved technical and administrative tickets increase churn tendencies.
---

## Actionable Recommendations 
   - Transition month-to-month customers to longer-term plans with discounts.
   - Promote underutilized services like OnlineSecurity and TechSupport to improve retention.
   - Address issues with Fiber Optic services to reduce dissatisfaction.
   - Improve support ticket resolution times and engagement for new customers.

---

## Screenshots
### Churn Dashboard
*![Screenshot 2025-03-21 193001](https://github.com/user-attachments/assets/1aa0bae9-3ed8-458f-8064-bc15928f1dad)*

### Customer Risk Analysis Dashboard
*![Screenshot 2025-03-21 193021](https://github.com/user-attachments/assets/e66ced12-1ea5-473d-9a66-d521dc669d31)*

---

## How to Use This Project
1. **Clone the Repository**: Download or clone the repository to your local system.
2. **Load Dataset**: Use the provided Excel file as the data source for analysis.
3. **Access Dashboards**: Open the Power BI dashboards to explore insights.
4. **Customize Analysis**: Adjust filters and visuals in the dashboards to uncover additional insights.

---

## About the Author
**Abhay Bhandari**

This project demonstrates my expertise in data analysis, visualization, and customer retention strategies using Power BI. Feel free to connect for feedback or collaboration opportunities!

**LinkedIn**: [Abhay Bhandari](https://www.linkedin.com/in/abhay-bhandari-a92b73231/)

Thank you!
