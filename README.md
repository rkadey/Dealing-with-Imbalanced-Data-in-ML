# Dealing-with-Imbalanced-Data-in-ML
## Table of Contents
1. Definition and Introduction of Class Imbalance
2. Why do we have to balance the data?
3. Techniques to handle Class Imbalanced datasets
### What is Class Imbalance?
Class Imbalance arises in Machine Learning when the target classes are not equally distributed or not in an equal ratio. For example, consider a dataset with a target values of dead and alive. If approximately more than half of the distribution represents the dead class and the other represent the alive class, we say the dataset is imbalanced. How then do we deal with this imbalance? This notebook helps us explore the ways we correct class imbalance in datasets to avoid getting inacurate results.
### Reasons why we balance data
Balancing class in datasets is super important because imbalance datasets can lead to inaccurate results. In Machine Learning, we always aim to make our predictions accurate. If we have imbalanced dataset, our model will be more biased towards the class with dominancy in our dataset.
### Techniques to handle Class Imbalanced datasets
There are atleast five known ways of dealing with data imbalance in Machine Learning.
 - Changing Performance Metrics
 - Changing the Algorithm
 - Oversampling the Minority Class
 - Undersampling the Majority Class
 - Imblearn SMOTE

#### Changing the Performance Metrics
