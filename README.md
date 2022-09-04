# Dealing-with-Imbalanced-Data-in-ML
## Table of Contents
1. Definition and Introduction of Class Imbalance
2. Why do we have to balance the data?
3. Techniques to handle Class Imbalanced datasets
4. Conclusion
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
 - Imblearn SMOTE<br>
 <br>
<strong>NB</strong> Before you do any Oversampling techniques, you must split your data into train and test datasets! This is to avoid the exact same observations to be present in both the test and train sets. This can allow our model to simply memorize specific data points and cause overfitting and poor generalization to the test data.

#### Changing the Performance Metrics
We can simply change our metric from accuracy to either one or all of these. ie. Confusion Matrix, Precision, Recall and F1 Score.
#### Changing the Algorithm
Decision Trees frequently perform better with imbalanced datasets. In a situation where your algorithm is different with your dataset also having class imbalance, you might want to add Decion Trees to improve the result.
#### Oversampling the Minority Class
Oversampling can be defined as adding more copies of the minority class. In other words, we are creating artificial/synthetic data of the minority class (or group). Oversampling could be a good choice when you don’t have a lot of data to work with.
#### Undersampling the Majority Class
Undersampling can be defined as removing some observations of the majority class. Undersampling can be a good choice when you have a ton of data -think millions of rows. But a drawback is that we are removing information that may be valuable. This could lead to underfitting and poor generalization to the test set.
#### SMOTE Technique
Here we will use imblearn’s SMOTE or Synthetic Minority Oversampling Technique. SMOTE uses a nearest neighbors' algorithm to generate new and synthetic data we can use for training our model.

### Conclusion
In conclusion, dealing with class imbalance in datasets is very vital as it curbs inaccurate results. Five major ways of dealing with imbalance are; Changing the Performance Metric, Changing the algorithm, Oversampling the Minority class, Undersampling the Majority class and finally, using the Imblearn SMOTE teachnique.
