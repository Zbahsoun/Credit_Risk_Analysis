# Credit_Risk_Analysis

## Overview of the project

For this project, we will use supervised machine learning algorithms to predict credit risk to be able to provide a more reliable loan experience, and to help identify good candidate for loans. We will be cleaning the data and then splitting it into training and testing data, after implementing these algorithms we will evaluate their performance. 

## Results

Below are the learning machine models used and their findings.

### Naive Random Oversampling:
- The balanced accuracy score is 61.7%
- The precision for high risk is 1%
- The precision for low risk is 100%
- The recall for high risk is 56%
- The recall for low risk is 67%

<img src="https://github.com/Zbahsoun/Credit_Risk_Analysis/blob/main/Models-Summary/Summary%201.png" width=50% height=25%>


### SMOTE Oversampling:
- The balanced accuracy score is 62.2%
- The precision for high risk is 1%
- The precision for low risk is 100%
- The recall for high risk is 55%
- The recall for low risk is 69%

<img src="https://github.com/Zbahsoun/Credit_Risk_Analysis/blob/main/Models-Summary/Summary%202.png" width=50% height=25%>


### Cluster Centroids Undersampling:
- The balanced accuracy score is 50%
- The precision for high risk is 0%
- The precision for low risk is 100%
- The recall for high risk is 48%
- The recall for low risk is 53%

<img src="https://github.com/Zbahsoun/Credit_Risk_Analysis/blob/main/Models-Summary/Summary%203.png" width=50% height=25%>


### SMOTEEN Combination Sampling:
- The balanced accuracy score is 62.6%
- The precision for high risk is 1%
- The precision for low risk is 100%
- The recall for high risk is 63%
- The recall for low risk is 62%

<img src="https://github.com/Zbahsoun/Credit_Risk_Analysis/blob/main/Models-Summary/Summary%204.png" width=50% height=25%>


### Balanced Random Forest Classifier:
- The balanced accuracy score is 78.8%
- The precision for high risk is 3%
- The precision for low risk is 100%
- The recall for high risk is 70%
- The recall for low risk is 87%

<img src="https://github.com/Zbahsoun/Credit_Risk_Analysis/blob/main/Models-Summary/Summary%205.png" width=50% height=25%>


### Easy Ensemble AdaBoost Classifier:
- The balanced accuracy score is 93.1%
- The precision for high risk is 9%
- The precision for low risk is 100%
- The recall for high risk is 92%
- The recall for low risk is 94%

<img src="https://github.com/Zbahsoun/Credit_Risk_Analysis/blob/main/Models-Summary/Summary%206.png" width=50% height=25%>
