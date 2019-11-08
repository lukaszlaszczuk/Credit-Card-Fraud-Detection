# Credit Card Fraud Detection
 Machine Learning project done with students' research club "KN Matematyki Statystycznej Gauss" at Wrocław University of Science and Technology.
 
## Description 
The task was to perform EDA and build predictive classification model for detecting fraudulent  credit card transactions made by European cardholders in September 2013. The original dataset from which the data for the project was taken, can be found on this Kaggle website: 

https://www.kaggle.com/mlg-ulb/creditcardfraud?fbclid=IwAR0ahRSoyPRu6mlitpuNxWSy6t9iTRKyeWFEYNHn--ROebOhsrscti9-HgA

The data on which the analysis was performed is a stratified, randomly selected subset of original data, which contains only 75% of original records. It can be found in data folder of this repository. The remaining 25% of observations (which is not provided in this repository) will serve as testing data for final comparison of models during "Gauss" meeting.

The modified dataset contains 369 frauds out of 213605 transactions which makes the dataset highly unbalanced. In regard to this fact, the Area Under the Precision-Recall Curve (AUPRC) was considered as a metric for evaluating models.
