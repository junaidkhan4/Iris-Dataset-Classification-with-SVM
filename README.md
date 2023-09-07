# Iris-Dataset-Classification-with-SVM

This project aims to classify the famous Iris dataset using a Support Vector Machine (SVM). We've performed parameter tuning on the SVM to identify the best combination of parameters like kernel, gamma, and regularization (C).

**Dataset**
The Iris dataset was sourced from the Scikit-Learn library, which is a well-known dataset in the machine learning community. It contains three classes of 50 instances each, where each class refers to a type of iris plant. Each instance has four attributes:

Sepal length
Sepal width
Petal length
Petal width

**Tuned Parameters**
We performed a hyperparameter tuning for the following parameters of SVM:

Kernel: Determines the type of hyperplane used to separate the data.
Gamma: Defines how far the influence of a single training set reaches. Low values indicate 'far' and high values mean 'close'.
Regularization (C): The regularization parameter, also known as cost parameter, that tells the SVM optimization how much error is acceptable.
