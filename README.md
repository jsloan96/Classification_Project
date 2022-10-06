# Classification_Project
https://jeremy-sloan.com/2022/09/30/project-2-classification/

Introduction

In the Machine Learning terminology, the process of Classification can be defined as a supervised learning algorithm that aims at categorizing a set of data into different classes. In other words, if we think of a data set as a set of data instances, and each data instance as a set of features, then Classification is the process of predicting the particular class that that individual data instance might belong to, based on its features. There are many applications in classification in many domains such as in credit approval, medical diagnosis, target marketing etc.

For example, spam detection in email service providers can be identified as a classification problem. This is s binary classification since there are only 2 classes as spam and not spam. A classifier utilizes some training data to understand how given input variables relate to the class. In this case, known spam and non-spam emails have to be used as the training data. When the classifier is trained accurately, it can be used to detect an unknown email.

Unlike regression where the target variable (i.e., the predicted value) belongs to a continuous distribution, in case of classification, the target variable is discrete. It can only be one of the various target classes in a given problem. 

This project will use the Drug Classification data set available on Kaggle to demonstrate 7 different machine learning categorical models.

    Logistic Regression
    K-Nearest Neighbor
    Support Vector Machine (SVM)
    1 Categorical Naive Bayes
    2 Gaussian Naive Bayes
    Decision Tree
    Random Forest

Because the Drug Classification data set contains information on 4 different drugs, we will be using multi-label Classification. Multi-Label Classification – As the name suggests, the prediction for a data instance can be more than 2 possible discrete outcomes. For example, when predicting the correct drug a patient is taking, a given data instance representing a patient can belong to any one of the 4 classes.The target feature of the data set is Drug type and the feature sets are Age, Sex, Blood Pressure, Cholesterol Levels, and Na to Potassium Levels.
