# Credit_Risk_Analysis

## Overview of the analysis

As part of this project, we used several techniques to evaluate and train models on credit card credit datasets from LendingClub. Our purpose is to predict High and low credit risk based on many different features. We used the imbalanced-learn and scikit-learn libraries to build and evaluate our models using resampling.

The RandomOverSampler and SMOTE algorithms were used to oversample the data, followed by the ClusterCentroids algorithm to undersample it. A combinatorial method of over- and undersampling was also used, using the SMOTEENN algorithm. 

Next, we applied two machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. The models were evaluated based on their accuracy and confusion matrices.

## Results

![Capture](https://user-images.githubusercontent.com/66279829/172100296-5bacc92e-86ae-4bb2-b724-0e9f90f5cde8.PNG)

## Summary

As we predict credit risk, we are mostly interested in having a model that is highly accurate in detecting high-risk customers. Since most high-risk customers have a very small level of precision, none of the six models performed well. Between the six models, the easy ensemble AdaBoost classifier performed best with 93% accuracy. The model should be improved by collecting more data about the minority class or by adding features that can detect low-risk customers, or by using a more complex model such as a neural network. 

