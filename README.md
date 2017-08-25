# Kaggle-Titanic
My first attempt to predict survival of the Titanic's passengers (R)


## Table of Contents

1  Exploratory data analysis <br>
...1.1  Check data <br>
...1.2  Check correlations among variables <br>
...1.3  Visualize some potentially important variables <br>
......1.3.1  Passenger's class <br>
......1.3.2  Women and children first! <br>
2  Feature engineering <br>
....2.1  Create new features 1 <br>
......2.1.1  Create Title from Name <br>
....2.2  Impute missing data <br>
......2.2.1  Fare <br>
......2.2.2  Embarked <br>
......2.2.3  Age <br>
....2.3  Create new features 2 <br>
......2.3.1  Create Child and Young from Age <br>
......2.3.2  Create Title2 from Title <br>
......2.3.3  Create dummy variables <br>
3  Machine learning <br>
...3.1  Logistic regression <br>
......3.1.1  A first quick and dirty model <br>
......3.1.2  Check learning curves <br>
......3.1.3  Feature selection <br>
.........3.1.3.1  Manual selection <br>
.........3.1.3.2  Automatic selection <br>
...3.2  Classification tree: CART (Recursive Partitioning) <br>
...3.3  Random forest <br>
...3.4  Support Vector Machine (SVM) <br>
......3.4.1  With linear kernel <br>
......3.4.2  With Gaussian kernel <br>
...3.5  Neural network <br>
...3.6  XGBoost <br>
......3.6.1  Linear <br>
......3.6.2  Tree <br>
4  Compare the best models <br>
...4.1  Compare the performances <br>
...4.2  Check correlations among models <br>
5  Predictions on the test set <br>
...5.1  GLM <br>
...5.2  CART <br>
...5.3  Random forest <br>
...5.4  SVM <br>
...5.5  XGBoost (linear) <br>
...5.6  XGBoost (tree) <br>
6  Going further <br>
