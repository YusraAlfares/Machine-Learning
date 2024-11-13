# Machine Learning


## Project details

This project has been implemented using Python and Jupyter notebook

## Results of experiment & project description 

This project's objective is to provide differences between three different machine learning algorithms, which are KNN, SVM, and Decision Tree
from the results provided using the stroke dataset, the SVM has achieved an accuracy rate of 95%, but is misleading because it's not actually predicting "Stroke" correctly. This means that the dataset may be imbalanced or that the SVM algorithm has learned the features that differentiate stroke cases well enough, leading it to stick to predicting "no stroke" as a default.
On the other hand, Decision tree has faced an issue with overfitting which is seen in the evaluation metrics results, this issue can be solved by using pruning to fix the overfitting problem.

## What can be done? 

Many machine learning algorithms face these pros and cons when it comes to running it, Decision tree faces the overfitting problem, some require higher computational power, some provide very good results but with the tradeoff of speed, etc.
These issues can be mitigated by using different solutions, for example, when faced with the overfitting problem in Decision tree, pruning can be used to mitigate it. or when facing a learning problem in SVM, we can address the class imbalance, or tune the decision boundary.
