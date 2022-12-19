# Credit_Risk_Analysis

## Overview of the analysis
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. Jill asks you to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling. Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.



## Results

Below are the results from the various techniques used for High-risk loans.

### SMOTE

![Screenshot 2022-12-18 at 6 08 20 PM](https://user-images.githubusercontent.com/110702997/208326716-881eee45-5dfa-4425-a5f6-69d00958b8a0.png)
![Screenshot 2022-12-18 at 6 09 27 PM](https://user-images.githubusercontent.com/110702997/208326763-a446ec52-5366-4147-9643-5a89a29a2a57.png)


### OVERSAMPLING

![Screenshot 2022-12-18 at 6 12 39 PM](https://user-images.githubusercontent.com/110702997/208326909-db99e574-457f-4bce-9622-99c30c0fc488.png)

![Screenshot 2022-12-18 at 6 14 52 PM](https://user-images.githubusercontent.com/110702997/208326988-1371e22c-9e13-4644-82bf-39d9039108f6.png)

![Screenshot 2022-12-18 at 6 15 17 PM](https://user-images.githubusercontent.com/110702997/208327017-c89438bc-9b58-4198-bfff-69a7ad8548d9.png)



### UNDERSAMPLING

![Screenshot 2022-12-18 at 6 24 04 PM](https://user-images.githubusercontent.com/110702997/208327372-d539d1a2-0bea-44b4-ba4c-23a060b6fb85.png)

![Screenshot 2022-12-18 at 6 25 45 PM](https://user-images.githubusercontent.com/110702997/208327466-5bd52b08-41ce-4d9d-bd48-ae1c4edfe100.png)

![Screenshot 2022-12-18 at 6 26 22 PM](https://user-images.githubusercontent.com/110702997/208327498-aa620c5f-ae7e-4204-9db7-6c55150f94eb.png)


### SMOTEENN

![Screenshot 2022-12-18 at 6 39 28 PM](https://user-images.githubusercontent.com/110702997/208328132-2ed4677c-cafb-405c-a0dd-d5984e3a13b5.png)

![Screenshot 2022-12-18 at 6 40 11 PM](https://user-images.githubusercontent.com/110702997/208328153-4370b889-de49-4db9-9a30-bdc040a4a9b0.png)


### BALANCED RANDOM FOREST CLASSIFIER

![Screenshot 2022-12-18 at 6 43 55 PM](https://user-images.githubusercontent.com/110702997/208328369-7468212f-1a80-442e-be62-bf7b2d419cef.png)

![Screenshot 2022-12-18 at 6 44 25 PM](https://user-images.githubusercontent.com/110702997/208328400-2cefdbbb-c1ee-4b81-91f1-216319d5296a.png)

![Screenshot 2022-12-18 at 6 44 56 PM](https://user-images.githubusercontent.com/110702997/208328438-5af49307-8a75-4f4a-a22d-0d647200ec2f.png)


### EASY ENSEMBLE CLASSIFIER

![Screenshot 2022-12-18 at 6 51 50 PM](https://user-images.githubusercontent.com/110702997/208328754-5a00117f-fe9a-499e-83a5-3947d6f433f5.png)

![Screenshot 2022-12-18 at 6 52 11 PM](https://user-images.githubusercontent.com/110702997/208328769-e5cf2b53-ce17-403f-82f9-87b76b52ad21.png)


![Screenshot 2022-12-18 at 6 52 36 PM](https://user-images.githubusercontent.com/110702997/208328783-205f4494-2f23-436f-84ca-967bdf992d38.png)


## SUMMARY

Out of all the models, the 

