# BANK-MARKETING-ANALYSIS-Classification
Our project demonstrated the significance of thorough exploratory data analysis, 
thoughtful feature engineering, and appropriate model selection in tackling real-world binary 
classification challenges. By addressing class imbalance, uncovering key influencing factors, and 
applying machine learning techniques, we gained valuable insights that can inform marketing 
decisions and improve the bank's outreach effectiveness.
# Dataset Information
This Project delves into the analysis of data gathered by a Portuguese banking institution during the 
timeframe spanning from 2008 to 2010. The dataset primarily revolves around the outcomes of 
direct marketing campaigns conducted through telephone conversations. These campaigns 
frequently necessitated multiple interactions with individual clients to ascertain their likelihood of 
subscribing to a bank term deposit, with potential outcomes categorized as either 'yes' (subscribed) 
or 'no' (not subscribed).
# Problem Statements 
1. Will the person subscribe to the term deposit or not?
Ans: Our main objective is to predict whether a person will subscribe to the bank's term 
deposit or not. This is a binary classification problem where the outcome is categorized as 
either 'yes' (indicating subscription) or 'no' (indicating non-subscription) based on the data 
collected from direct marketing campaigns conducted by a Portuguese banking institution. 
2. Does the customer's loan affect their decision to do a term deposit? 
Ans: We will analyze the dataset and conduct appropriate statistical analyses that will help to 
reveal the extent of the impact of a customer's loan status on their term deposit decision, 
providing insights that will guide the bank's future marketing strategies and customer 
engagement approaches.
3. How does job types impact the likelihood of term deposit subscription? 
Ans: With the help of univariate analysis, we got to know about the distribution of each 
feature and with the help of multivariate analysis we get to know about feature's associativity 
with each other. 
4. Does the mode of communication impact subscription decisions? 
Ans: With the help of EDA, we get to know about the correlation between the mode of 
communication and term deposit decision. Heat map is the best way to show their relation 
more accurately and efficiently. 
5. What is the correlation between contact duration and term deposit subscription? 
Ans: With the help of correlation matrix, we will know that whether there is a positive or 
negative correlation between contact duration and term deposit.
# Subject Area
Finance, Marketing, Banking, Customer Behavior Analysis, Predictive Modeling, Classification, Customer Engagement, Investment Decisions
# Libraries
* pandas
* seaborn
* matplotlib
* sklearn
# Techniques & Methods 
* Exploratory Data Analysis (EDA) - Univarate Analysis, Multivariate Analysis.
* Outliers detection - IQR Method.
* Data Exploration & distribution - Summary Statistics.
* Data normalization - MinMax Normalization.
* Dealing with imbalanced data - SMOTE Analysis.
* Model Evaluation - Confusion Matrix
# ML Algorithms
* K-Nearest Neighbors (KNN)
* Logistic Regression
* Decision Tree Classifier 
* Random Forest Classifier 
* Best Model AUC: 82.94% (RF)
