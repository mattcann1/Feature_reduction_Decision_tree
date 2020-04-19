# Feature_reduction_Decision_tree

## Abstract  
In this study, three methods of feature reduction were analyzed to investigate the effect on accuracy and
computational cost of a C4.5 classifying decision tree algorithm on the Human Activity Recognition (HAR)
Using Smartphones dataset from the UCI Machine Learning Repository. The dataset is comprised of 561
attributes measured from the accelerometer and gyroscope of a smartphone over 10299 instances. Feature
reduction on the dataset helps to solve the overfitting behaviour of the C4.5 algorithm when fitting data
with many extraneous features. The dimension reduction techniques analysed were principal component
analysis (PCA), linear discriminant analysis (LDA), and a PCA+LDA combination. The feature reduction
methods were applied to the training set to transform the data. Using the reduced dataset, a C4.5 decision
tree was trained and then used to predict the class labels using the transformed testing dataset. From the
analysis of this study, LDA outperforms the other dimension reduction methods in accuracy, precision and
computational complexity resulting in a final testing accuracy on the HAR dataset of 95.62%.
