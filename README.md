# Telecom-Churn-Case-Study-Advanced-ML
Telecom Churn Case Study: Advanced Machine Learning (06 Dec 22)

Problem Overview:
In the telecom industry, customers switch their operators when they come across better deals. Since it costs 5-10 times more to acquire a new customer than to retain an existing one, customer retention is more important than customer acquisition. In this project, we predict the churn for pre-paid customers who are predominant in the Indian and Southeast Asian market.
Business Objective:
The business objective is to predict the churn in the ninth month using the data from the first three months.

Content:
1. Data Import and Preparation
2. Exploratory Data Analysis
3. Model Prediction using Logistic Regression
4. Handling Imbalance Dataset
5. Random Forest SMOTE
6. Decision Tree SMOTE
7. Feature Analysis
Conclusion:
1. 	In terms of modelling effectiveness, observe Random Forest post SMOTE class imbalance treatment, there is a better ROC curve of 0.81 with accuracy as 92%.
2. 	Features that majorly influences the Churn are as below - Mainly its covering the Customer behaviour on Recharge, Outgoing Calls
arpu_8
loc_ic_t2m_mou_8
total_ic_mou_8
loc_og_mou_8_perc
loc_og_t2m_mou_8
total_rech_amt_8
loc_ic_t2t_mou_8
loc_og_mou_8
max_rech_amt_8
loc_ic_mou_8_perc
last_day_rch_amt_8
total_og_mou_8
loc_og_t2t_mou_8
offnet_mou_8.

Recommendations:

There is a need to observe Month on Month on ARPU, Recharge and Call Activities to watch for the decline trend which need to be reversed by 
1. Giving Recharge Discounts.
2.  Value added packs for recharges.
3. Hidden concerns on the network quality to see if the network performance hindering the call activities.

