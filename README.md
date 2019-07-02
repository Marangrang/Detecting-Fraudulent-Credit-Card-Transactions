Credit Card Fraud Detection
In this project, we will analyze the dataset which contains 193 frauds out of 95469 transactions from Zindi (www.zindi.africa/competitions/xente-fraud-detection-challenge/data). 
The transactions were made by Ugandanian credit card holders between 15 November 2018 and 15 March 2019. 
Our objective of this project is to fit the dataset into our machine learning models to predict precisely while dealing with the highly unbalanced issue of this dataset. 
Since there are 28 variables which are the result of a principle component analysis (PCA) transformation and the information of the variables was not given, we will drop the variables which have similar distributions. 
Our next step is to deal with the unbalanced issue. 
We will use the synthetic minority over-sampling technique (SMOTE) to resample the dataset to make the numbers of frauds and normal transactions even. 
The last step is to compare the machine learning methods and we found that Xgboost returned the highest AUC score.
