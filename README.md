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
 
 
       ![over](https://user-images.githubusercontent.com/80402142/130335826-7974977f-6452-4683-93b1-582f7439f7bc.png)



- The second analysis undersamples the data using SMOTEENN to see if this reduces bias from analysis:


    - Balanced Accuracy Score: 64%
    
    
         ![SMOTE](https://user-images.githubusercontent.com/80402142/130335831-c8e6ea7c-ae96-4c4a-b384-de38fa922936.png)


- Finally, the two models are compared to evaluate the performance and determine which model is most accurate:


    - Accuracy Score: 55%
    
         ![d_2_cluster](https://user-images.githubusercontent.com/80402142/130335833-0b10e2cf-07f4-4af8-895f-1151ba39e24e.png)


## Resources

- Data Source: LoanStats_2019Q1.csv

- Software: Python 3.7.9, Anaconda Navigator 1.9.12, Conda 4.8.4, Jupyter Notebook 6.0.3
