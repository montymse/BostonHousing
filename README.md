# BostonHousing
Linear pyTorch model that predicts housing values in suburbs of Boston. To train the model run train.py and to evaluate the model run eval.py

Data for the model available at https://www.kaggle.com/c/boston-housing/overview or see Data/housing.csv\
Prediction of the model is available at Data/predictions_and_targets.csv

Data description: The Boston data frame has 506 rows and 14 columns. The medv variable is the target variable.

This data frame contains the following columns:

crim     = per capita crime rate by town.\
zn       = proportion of residential land zoned for lots over 25,000 sq.ft.\
indus    = proportion of non-retail business acres per town.\
chas     = Charles River dummy variable (= 1 if tract bounds river; 0 otherwise).\
nox      = nitrogen oxides concentration (parts per 10 million).\
rm       = average number of rooms per dwelling.\
age      = proportion of owner-occupied units built prior to 1940.\
dis      = weighted mean of distances to five Boston employment centres.\
rad      = index of accessibility to radial highways.\
tax      = full-value property-tax rate per \$10,000.\
ptratio  = pupil-teacher ratio by town.\
black    = 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town.\
lstat    = lower status of the population (percent).\
medv     = median value of owner-occupied homes in \$1000s.\
