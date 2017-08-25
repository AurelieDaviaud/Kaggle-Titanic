# Kaggle-Titanic
My first attempt to predict survival of the Titanic's passengers (R)


## Table of Contents
1 Exploratory data analysis 
...1.1 Check data 
...1.2 Check correlations among variables 
...1.3 Visualize some potentially important variables 
......1.3.1 Passenger's class 
......1.3.2 Women and children first! 
2 Feature engineering 
....2.1 Create new features 1 
......2.1.1 Create Title from Name 
....2.2 Impute missing data 
......2.2.1 Fare 
......2.2.2 Embarked 
......2.2.3 Age 
....2.3 Create new features 2 
2.3.1 Create Child and Young from Age 
2.3.2 Create Title2 from Title 
2.3.3 Create dummy variables 
3 Machine learning 
...3.1 Logistic regression 
......3.1.1 A first quick and dirty model 
......3.1.2 Check learning curves 
......3.1.3 Feature selection 
.........3.1.3.1 Manual selection 
.........3.1.3.2 Automatic selection 
...3.2 Classification tree: CART (Recursive Partitioning) 
...3.3 Random forest 
...3.4 Support Vector Machine (SVM) 
......3.4.1 With linear kernel 
......3.4.2 With Gaussian kernel 
...3.5 Neural network 
...3.6 XGBoost 
......3.6.1 Linear 
......3.6.2 Tree 
4 Compare the best models 
...4.1 Compare the performances 
...4.2 Check correlations among models 
5 Predictions on the test set 
...5.1 GLM 
...5.2 CART 
...5.3 Random forest 
...5.4 SVM 
...5.5 XGBoost (linear) 
...5.6 XGBoost (tree) 
6 Going further 
