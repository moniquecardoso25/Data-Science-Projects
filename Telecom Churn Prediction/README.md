# Telco Customer Churn - Machine Learning

## Objective

This project aims to predict customer churn in Telco, a fictional telecom company. Customer churn, which refers to customers discontinuing services or business with a company, is a critical metric for businesses. Predicting and understanding churn helps companies retain valuable customers.

## Approach and Results

- Explored the dataset, addressing missing values.
- Employed feature engineering to enhance model performance.
- Utilized three machine learning models: Logistic Regression, Random Forest Classifier, and XGB Classifier.
- Evaluated model performance using Accuracy, with Logistic Regression achieving the highest accuracy of 80%.
- Examined confusion matrix to understand the number of predicted customer churn cases.
- Derived conclusions and provided recommendations for the company to enhance its services.

## Tools Utilized
- Python
- Machine Learning models: Logistic Regression, Random Forest Classifier, and XGB Classifier.
- Data Preprocessing - Label Encoder, Robust Scaler
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Data Visualization using Matplotlib and Seaborn
- Pandas for data manipulation and analysis
- Evaluation metrics: accuracy and confusion matrix
  

## Conclusion

Customer Churn Analysis:

The model achieved an accuracy of 80%, predicting 460 customer churn cases.

1. **Churn Overview:**
   - Churn rate: 26.6% of customers switched services.
   - Demographics: 25.5% of senior citizens and 74.5% of younger individuals churned.

2. **Relationship Impact:**
   - Partnerships: 64.2% without a partner, 35.8% with a partner churned.
   - Dependents: 82.6% without dependents, 17.4% with dependents churned.

3. **Service Influence:**
   - Fiber Optic Users: Significant churn among Fiber Optic users.
   - Tech Support and Online Backup: 77% without Tech Support and 66% without Online Backup churned.

4. **Payment Plans:**
   - Monthly Payments: 89% of Month-to-Month clients churned.

5. **Billing Insights:**
   - Higher Charges: Churning customers had higher median monthly charges.
   - New Customers: New customers were more likely to discontinue services.

6. **Loyalty and Tenure:**
   - Tenure Effect: Longer tenure correlated with lower churn probability.
   - Loyal Customers: Longer tenure indicated stronger customer loyalty.

## Recommendations for the Company

Recommendations:

**Enhance New Customer Onboarding:**
   - Improve initial experiences for new customers to boost retention.

**Focus on Partner and Dependent Groups:**
   - Tailor services or incentives for customers without partners or dependents.

**Fiber Optic Service Improvement:**
   - Address Fiber Optic user concerns to enhance satisfaction and retention.

**Strengthen Tech Support and Online Backup:**
   - Enhance Tech Support and Online Backup services to reduce churn.

**Refine Monthly Payment Plans:**
   - Offer incentives for Month-to-Month customers to consider longer-term plans.

**Promote Long-Term Engagement:**
   - Implement strategies to nurture customer loyalty over time.

By analyzing churn patterns and implementing the outlined recommendations, the company can decrease churn rates, elevate customer satisfaction, and cultivate lasting relationships, leading to improved business performance.
