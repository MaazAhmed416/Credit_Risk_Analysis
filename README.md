# Credit_Risk_Analysis
## Overview of the analysis
The purpose of our analysis was to detemrine the credit risk of loans. We took into account the data of loan_stats to determine whether someone was of high risk or low risk. One way to conduct such a test is done by creating a model and than evaluating and training the model that was created. For this project, we were requested to use imbalanced-learn and scikit-learn libararies to build models and than evaluate them using a resampling method. In the first few models, we use RandomOverSampler and SMOTE algorithms to oversample the data. Next we created a undersampled model using the ClusterCentroids algorithm. We also created a model using a combination approach to over and undersample the data using smoteenn. Lastly, we compared two new machine learning models BalancedRandomForestClassifier and EasyEnsembleClassifier. These helped us reduce bias while predicting credit risk.
## Results of our analysis
- For the Naive Random Oversampling, our balanced accuracy score is 67%, the precision for the high_risk has a low positivty of 1% and the recall is 74%
![image](https://user-images.githubusercontent.com/76402559/116302879-b5e7ae00-a76f-11eb-96f2-e506d963b90b.png)

-For SMOTE oversampling, the accuracy score is 66% , the precision of high risk has a low positivity of 1% and the recall is 63% 
![image](https://user-images.githubusercontent.com/76402559/116304573-b2a0f200-a770-11eb-87fd-29920d5e0e6a.png)

