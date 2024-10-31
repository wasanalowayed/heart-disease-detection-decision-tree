# Table of Contents:

- Introduction
- Describe The Decision Tree Algorithm
- Steps of The Algorithm
- Authors


# Introduction:

We have data for different people. We want to try to predict, based on certain data, whether these
people are likely to suffer from heart disease or not. We have come to the closest solution, which
is to use a well-known algorithm in machine learning called Decision Tree, so that it builds for us
a model that predicts the values for a target variable by teaching it on labeled data.


# Describe The Decision Tree Algorithm:

Decision Tree is a Supervised learning technique that can be used for both classification and
Regression problems, but mostly it is preferred for solving Classification problems. It is a tree-
structured classifier, where internal nodes represent the features of a dataset, branches represent
the decision rules, and each leaf node represents the outcome.
Decision trees are like a flowchart for making decisions. They split the data based on features,
creating branches that lead to different outcomes. Each split aims to make groups that are as pure
as possible. This process repeats until the groups are either all the same or a stopping condition is
met. Finally, when new data comes in, it follows the branches of the tree to predict the outcome.


# Steps of The Algorithm:

1. Start with the entire dataset: The algorithm begins with all the data points at the root of the
tree.
2. Select the best feature to split on: It looks at all the features and chooses the one that best
separates the data into different groups or classes. It could use criteria like information gain
or Gini impurity to make this decision.
3. Split the data based on the selected feature: The dataset is divided into subsets based on the
chosen feature's values. Each subset corresponds to a branch in the tree.
4. Repeat recursively: Steps 2 and 3 are repeated for each subset of data, creating more
branches and nodes until a stopping criterion is met. This could be reaching a maximum
depth, having only one class in a subset, or another condition.
5. Make predictions: Once the tree is built, it can be used to make predictions on new data.
When new data comes in, it follows the branches of the tree based on the feature values until 
it reaches a leaf node, where a prediction is made based on the majority class or the average
value of the samples in that node.
6. Prune the tree (optional): In some cases, the tree may be too complex and prone to
overfitting. Pruning techniques can be applied to simplify the tree by removing branches that
do not provide much predictive power.
7. Evaluate the performance: Finally, the performance of the decision tree model is evaluated
using metrics such as accuracy, precision, recall, or others depending on the task
(classification or regression).


# Authors: 

- Sadeem Alnfeisah
- Lulu Altuwijri
- Wasan Alowayed
