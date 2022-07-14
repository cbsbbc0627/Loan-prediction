# Loan Prediction based on customer beheavior 

-- predict who possible defaulters are for customer loans products with historic customer behavior 

What is in the dataste? 
It has 28,000 rows. 
One important variable: risk_flage 
Some explaination for the columns: 
1. income -- Income of the user 
2. age -- age of the user 
3. profession 
4. married -- whether married or single 
5. house_ownership -- owned or rented or neither
6. care_ownership -- does the person own a car 
7. risk_flag -- whetehr there has been a default in the past or not   ** 
8. currentjobyera -- years of experience in the current job 
9. currenthouseyears -- number of years in the current residence
10. city -- city of residence 
11. state -- state of residence 

#### Thesis Statement:
We intend to use Loan Prediction Training Dataset to predict those potential non-defaulter and defaulters are for customer loans product.
We apply 5 models to test the dataset including DecisonTreeClassifer, logiticsRegression, RandomForestClassifer, XGBClassifer, and LightGBM. We decide to use AUC and accuracy to select best classifier where AUC is given priority over accuracy. We also checkout confusion matrix, recall and precision.
We propose a DecisionTree classifier to predict. The accuracy score is 0.89 and the AUC is 0.91.

The dataset link: https://www.kaggle.com/datasets/subhamjain/loan-prediction-based-on-customer-behavior?sort=votes 
