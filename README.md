This repository contains a classifier model trained with Car Evaluation Dataset(Source:[Kaggle](https://www.kaggle.com/datasets/elikplim/car-evaluation-data-set)).
The main challenge with the dataset is that most the features are categorical and we can't give these categorical features directly to a machine learning model.
We need to convert these categorical features into real values to train a machine learning model.


In this repo I used ordinal encoder to convert these categorical features into numerical values with proper mapping from category level to numerical value and trained a SVC(Support Vector Classifier).
Though the dataset is having class imbalance with 1434 data points for one class and 120 data points for other class,achived 93% test accuracy.


To tackle the problem of class imbalance I used SMOT(synthetic minority oversampling technique).


   

