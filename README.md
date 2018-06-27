# Rosbank-ML-Competition-2018
Solution for Rosbank ML Competition 2018
https://boosters.pro/champ_15  

For the competition tasks,the participants were given a single data set, which contains the history of 500k customer transactions for 3 months of preferential use of product.

Task 1.
In the first task, the participants have to solve the task of binary classification - to predict the outflow of customers.
35 fundamental features from the dataset were engineered, then different classifiers were explored and funed(Logistic Regression, SVM with rbf kernel etc.). Best performance (80% AUC, first place had 87% AUC) was obtained with AdaBoost. 

Task 2.
In the second task, the participants have to predict the amount of transactions through POS-terminal in the next three months of using the product. 
The amount of transactions through Pos-terminal in the next three months of using the product was predicted with Multilayer Perceptron. 
