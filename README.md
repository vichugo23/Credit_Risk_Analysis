# Credit_Risk_Analysis

## Overview of the analysis
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. Jill asks you to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling. Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.



## Results

Below are the results from the various techniques used for High-risk loans.

### SMOTE

![Screenshot 2022-12-18 at 6 08 20 PM](https://user-images.githubusercontent.com/110702997/208326716-881eee45-5dfa-4425-a5f6-69d00958b8a0.png)
![Screenshot 2022-12-18 at 6 09 27 PM](https://user-images.githubusercontent.com/110702997/208326763-a446ec52-5366-4147-9643-5a89a29a2a57.png)
