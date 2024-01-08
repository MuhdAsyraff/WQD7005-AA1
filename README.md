# WQD7005-AA1
WQD7005 Case Study 

a. Objective
1. To integrate data sources from multiple sources using Talend Data Integration
2. To prepare the data for decision tree model using Talend Data Preparation
3.  To make a decision tree and assemble model analysis on the cleaned datasets using SAS Enterprise Miner
   
b. Data Import and Pre-processing

Dataset link: https://www.kaggle.com/datasets/shriyashjagtap/e-commerce-customer-for-behavior-analysis
1. There are two churn datasets found with same set of attributes. The datasets are integrated using tUnite from Talend Data Integration
2. After combining the dataset, the dataset is brought to Talend Data Preparation for data cleaning
3. There are 19% missing values present in the 'Returns' and all the rows containing the missing values are removed because the dataset size is large enough so removing a part of the dataset would not be an issue
4. some variables type are changed to double to assist the decision tree analysis later
5. the date format is changed by removing the time and maintaining the date of purchase.
6. decision tree is carried out in SAS Enterprise Miner
7. Assemble model chosen is Bagging using random forest because of the large dataset size
 
