********************************************** 
 
Version: Python 3.7.6 
IDE: Jupyter Notebook
@author: 何灿 Sany
Time: 2020/07/28

**********************************************
Package:
numpy、pandas、matplotlib、sklearn

Realiztion:
1. Stratified sampling based on clustering results (eg. kmeans)
2. Contrast pure random sampling with stratified sampling (take the multi-classifier constructed by LogisticRegression as an example)
3. Construct a cross-validation class based on stratified sampling (take the multi-classifier constructed by SGD Classifier and the Linear Regressor as examples)

Dataset:
【data.xlsx】: The TRUE VALUE column in the data set is the actual category information
【data_after_clustering.csv】: A data set containing clustering results obtained through clustering【kmeans_ap_clustering.ipynb】

Grading:
It can be evaluated by the score of classification (or regression) model over stratified sampling/pure random sampling

Further work:
You can apply it into the classification or regression model (such as neural network, SVM, linear, polynomial, etc.)

Note:
1. For the cross-validation of stratified sampling, there is no built-in library like 'cross_val_score' in the python package library, so you can construct the corresponding class yourself
2. The complete data set refers to the original data set that has not been divided (layered or purely random)
3. 【data.xlsx】and【data_after_clustering.csv】are the same data set, the difference between them is the latter one contain the clustering results

*********************************************

