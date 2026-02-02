DATASET – INDEPENDENT AND DEPENDENT VARIABLES

The dataset is sourced from Kaggle and contains 10,000 samples with 13 independent feature variables and one dependent (target) variable. All variables were used during model training and prediction.

The independent variables include customer demographic, financial, and account-related information such as Credit Score, Geography, Gender, Age, Tenure, Account Balance, Number of Products, Credit Card ownership, Active Membership status, and Estimated Salary, along with customer identifiers.

The dependent variable is Exited, which is a binary categorical variable indicating customer churn, where 0 represents customers who remained with the bank and 1 represents customers who exited.

There are no missing values in the dataset. The target variable is imbalanced, which informed the modeling and evaluation strategy.

What Drives Customer Churn and How Can It Be Reduced?
📌 Project Overview

This project analyzes customer churn to understand the key factors that cause customers to leave and explores strategies that businesses can use to reduce churn. Using Python and data analysis techniques, the notebook investigates customer behavior patterns and builds insights that can inform decision-making.

🎯 Objectives

Understand what customer churn is and why it matters

Identify key factors that influence customer churn

Perform exploratory data analysis (EDA) on customer data

Draw insights and recommendations to reduce churn

🧰 Tools & Technologies Used

Python

Jupyter Notebook

Pandas – data manipulation

NumPy – numerical operations

Matplotlib / Seaborn – data visualization

📊 Key Analysis Performed

Data cleaning and preprocessing

Exploratory Data Analysis (EDA)

Visualization of churn vs customer attributes

Identification of trends and high-risk churn groups
Predicting Bank Customer Churn: Data-Driven Insights and Strategies

1. The Problem: Why Churn Matters

2.  
In the banking sector, retaining a customer is significantly cheaper than acquiring a new one. This project analyzes a dataset of 10,000 customers to identify the "red flags" that signal a customer is about to leave (churn).
3. Key Insights from Exploratory Data Analysis (EDA)

4. 
Your visualizations revealed several critical patterns:
•	The Age Factor: Older customers show a higher tendency to churn. This might suggest that the bank's digital products or loyalty rewards are better suited for younger demographics.
•	Geography Matters: Germany has a significantly higher churn rate compared to France and Spain. This is a huge finding—it suggests a need for a deep dive into regional competition or service quality in Germany.
•	Product Overload: Interestingly, customers with 3 or 4 products have extremely high churn. This often indicates "forced" cross-selling where customers feel overwhelmed or dissatisfied with the bundled services.
•	Activity Gap: As expected, inactive members are much more likely to leave.
 
5. The Modeling Approach

6. 
We tested two primary models to predict the probability of a customer exiting:
1.	Logistic Regression: A great baseline, achieving an AUC of 0.777.
2.	Random Forest: Our top performer with an AUC of 0.855.
3.	
The Random Forest model is superior here because it captures the non-linear relationships in the data (like the complex interaction between the number of products and churn).
4. Strategic Recommendations
5. 
Based on the data, here is how the bank can reduce churn:
•	Targeted Engagement for Inactive Members: Launch re-activation campaigns (e.g., special interest rates or personalized offers) specifically for those flagged as "Inactive."
•	Review German Operations: Investigate why German customers are unhappy. Is it higher fees? Local competitors? A localized survey is needed.
•	Simplify the Product Suite: Since churn spikes at 3+ products, the bank should review its multi-product bundles to ensure they add genuine value rather than complexity.
•	Proactive Retention for Older Clients: Develop wealth management or retirement-focused features to better engage the older demographic which is currently at risk.
