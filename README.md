# Machine-Learning-ClassificationTools-RealWorldData

This is a comparison between some Machine Learning classification(supervised learning) tools and their accuracy results.

The data set (in the Data.csv file) is a real world data set that I pulled from the UCI machine learning repository and this data set is about breast cancer.
Each row in this data set represents a patient and for every patient we have the following independent variables(features), Sample Code number,
Clump thickness, Uniformity of cell size, uniformity of cell shape, Marginal Adhesion, Single Epithelial cell, Bare nuclei, Bland Chromatin,
Normal Nucleoli, Mitoses, and for the dependent variable we have class which contains binary results. All those independent variables or f
eatures predict whether the patient will have a class of 2 (benign) or 4(malignant).


In general, If I want to know which classification model to choose for my problem I first firgure out whether the problem is linear or non linear.
If the problem is linear I would go for logistic regression or SVM, and if the problem is non linear I would go for either K-NN, Naive Bayes, Decision tree or Random forest.

Moreover, whether the problem is linear or not if I want to rank my predictions by their probability I would go for logistic regression(linear) or Naive Bayes(non-linear), e.g ranking the probability of customers buying a certain profuct from highest to lowest.

I would use SVM(linear) when I want to predict for example to which segment my customers belong to, and Decision Tree when I want to have a clear interpretation of my model results, and finally Random Forest when I am looking for high performance with less need for interpretation.

