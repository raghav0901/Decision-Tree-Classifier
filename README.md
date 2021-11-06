# Decision-Tree-Classifier
Decision Tree Classifier ( written from scratch)


## Overview:

This is a decision tree classifier written from scratch which works on the iris <br>
dataset to build a decision tree to classify the class of the flower:

## Numerical Representation of the flower classes:

0 -- Iris Setosa <br>
1 -- Iris Versicolour <br>
2 -- Iris Virginica <br>

## Printing steps:
At each level, the nodes ans their current entropy value are printed. <br>
Whenever, a split is made or a leaf node is reached, appropriate message is also printed at that level.


## Criterion for reaching a leaf node:
If we reach a node with 0 entropy value, then we have reached a leaf node.

## Criterion for best split:
We split the node by chossing a feature which offers the highest Gain Ratio for the particular split.



