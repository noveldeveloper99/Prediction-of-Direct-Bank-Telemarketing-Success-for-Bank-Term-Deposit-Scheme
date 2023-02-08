# H9DAPA-Domain-Applications-of-Predictive-Analytics
Project repository for Semester 1 DAPA Module

# Prediction of Direct Bank Telemarketing Success for Bank Term Deposit Scheme

This project renders a critical analysis of Bank Telemarketing sales data to predict the customer response to sales calls using RandomForest with Synthetic Minority Oversampling Technique (SMOTE). 

### Dataset
Dataset from UCI machine learning repository was used:
[Bank MArketing Data Set](https://archive.ics.uci.edu/ml/datasets/bank+marketing)

### Technologies 
IDE: Jupyter Notebook

Language: Python

Libraries: Pandas, Numpy, Matplotlib, Seaborn, Sklearn, Imblearn

### Execution steps
1. The jupyter notebook can be directly run all at once without any issues once the dataset is downloaded and its path for data loading is updated in the notebook.
2. Data loading, exploration, preprocessing, data balancing and modelling are completed for revelation of conclusive insights.

### Project Summary
Optimizing marketing campaigns within a limited budget is a key issue for many banks and financial institutes. After critical assessment of the applicable techniques, a RandomForest model to assist in selection of customers for the Direct Telemarketing campaign was developed. We utilized the Portuguese Bank Dataset from the UCI Repository to model the Random Forest algorithm. The dataset was imbalanced in nature and had a ratio of 88:11 for the majority and minority class. In order to avoid the problems of an imbalanced dataset and prevent bias for the majority class SMOTE-NC technique was adopted. 

![image](https://user-images.githubusercontent.com/98535942/217400908-029a3cf3-4bb6-4713-b934-defe307e1a93.png)

Post applying the SMOTE-NC, the class was balanced to an acceptable ratio of 61:39, upon which the Random Forest Algorithm was applied. The developed model presented an accuracy of 88.56 %, Precision of 36.38 %, Recall of 32.31 % and an F1 score of 34.22%. The AUC ROC score of 0.7319 suggested that the developed model is a good classifier and is fit for the project objective.

![image](https://user-images.githubusercontent.com/98535942/217400977-edc39765-e3c3-4d6a-8bcc-60b0d1daee73.png)
