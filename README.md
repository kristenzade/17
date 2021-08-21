# 17
# Credit_Risk_Analysis

## Analysis Overview

In this project, we use Python to build and evaluate several machine learning models to predict credit risk.
We adopted the following procedure:

- Using the RandomOverSampler and SMOTE algorithms, oversample the data. 
- Using the ClusterCentroids technique, undersample the data. 
- BalancedRandomForestClassifier and EasyEnsembleClassifier are two machine learning models that eliminate bias.

## Process
In these models, loan risks are assigned:
- "o" equals high-risk
- "1" equals low-risk

- The first analysis oversamples the data using RanomOverSample and Smote to predict credit risk:
  - Balaned Accuracy Score: 65%
  - ![over](https://user-images.githubusercontent.com/79612565/126854076-19ea1df7-f57d-419c-b951-c54c0cdb7e47.png)


- The second analysis undersamples the data using SMOTEENN to see if this reduces bias from analysis 1
    - Balanced Accuracy Score: 64%
    - ![SMOTE](https://user-images.githubusercontent.com/79612565/126854068-a714ad1b-dde3-4a0a-8069-b8631ee10410.png)

- Finally, the two models are compared to evaluate the performance and determine which model is most accurate
    - Accuracy Score: 55%
    - ![d_2_cluster](https://user-images.githubusercontent.com/79612565/126854064-9595e786-16ea-4634-814e-37718c8dc1d8.png)

## Resources

- Data Source: LoanStats_2019Q1.csv

- Software: Python 3.7.9, Anaconda Navigator 1.9.12, Conda 4.8.4, Jupyter Notebook 6.0.3
