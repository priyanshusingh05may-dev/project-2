Customer Churn Prediction & Analysis
📝 About the Project
This project focused on analyzing customer churn for PowerCo, a major utility provider. As the energy market becomes increasingly competitive, retaining customers is critical. The objective was to build a predictive model to identify customers at risk of churning and evaluate whether price sensitivity is a primary driver of attrition.

The analysis follows the complete data science lifecycle:

Task 1: Business Understanding & Hypothesis Framing.

Task 2: Exploratory Data Analysis (EDA).

Task 3: Feature Engineering & Data Preprocessing.

Task 4: Predictive Modeling (Random Forest) & Evaluation.

🚩 Problem Statement
PowerCo is experiencing a significant number of customers switching to competitors. The business hypothesis is that price sensitivity is the main driver of churn. PowerCo wants to know:

Can we predict which customers are likely to churn?

Is churn truly driven by price, or are other factors more influential?

Would a 10% discount be an effective strategy to retain high-risk customers?

🔍 Key Insights
From the Exploratory Data Analysis and Feature Importance ranking, the following insights were uncovered:

Churn Rate: Approximately 10% of the customer base has churned.

Price Sensitivity: While price is a factor, it is not the primary driver of churn. The model showed that price-related features had low importance compared to consumption patterns.

Top Predictors: The most influential features for predicting churn were:

Net Margin: Customers with higher profitability margins were more stable.

Consumption History: 12-month electricity and gas consumption volumes were strong indicators.

Tenure (Antiquity): Newer customers are significantly more likely to churn than long-term loyalists.

Model Performance: Using a Random Forest Classifier, we achieved an accuracy of ~90%. However, the model showed high precision but low recall, indicating it is conservative in flagging churners but highly accurate when it does.

💡 Recommendations
Based on the data, I recommend the following strategies to PowerCo:

Targeted Retention: Instead of a blanket discount, offer the 10% discount only to customers identified as "High Risk" by the model who also have a high net margin.

Focus on New Customers: Implement an "Onboarding Loyalty Program" for customers in their first 2-3 years of antiquity, as this segment has the highest churn risk.

Cross-Selling: Encourage electricity-only customers to switch to dual-fuel (Gas + Electricity) plans, as multi-product customers show higher retention rates.

Beyond Price: Investigate "Service Quality" and "Customer Experience" metrics, as price sensitivity alone does not explain the majority of churn.

🖥️ Dashboard & Visualizations
<img width="1070" height="697" alt="download" src="https://github.com/user-attachments/assets/8379c459-b0ae-45af-83b9-b200a326d481" />
<img width="1079" height="1406" alt="download (1)" src="https://github.com/user-attachments/assets/50f8fa15-e882-47f4-b3cd-12952842e01d" />
<img width="1058" height="1406" alt="download (2)" src="https://github.com/user-attachments/assets/192a6712-ef84-4387-82ae-fe6b6ca411b8" />
<img width="1060" height="605" alt="download (3)" src="https://github.com/user-attachments/assets/6d9f708a-1f6c-48ba-ac82-ac05dcbe38af" />
<img width="1073" height="2765" alt="download (4)" src="https://github.com/user-attachments/assets/f7d13ab8-64d8-4c51-aa5a-49741260ca43" />






1. Customer Distribution & Churn Status
Insight: 10% of customers have churned, indicating a significant but manageable segment for intervention.

2. Feature Importance (Random Forest)
Insight: Consumption and margin features outweigh price sensitivity in predicting customer exit.
