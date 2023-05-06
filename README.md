 **Boston-House-pricing-MLR**
 
This dataset contains information on the median value of owner-occupied homes in various neighborhoods in Boston, MA. The dataset was originally published in 1978 and has been used extensively in regression analysis since then.

**Dataset Description**

The Boston House Pricing dataset contains 506 observations with 14 attributes. Each observation represents a different neighborhood in Boston, and each attribute provides information on various aspects of the neighborhood or the houses within it.

The attributes are as follows:

CRIM: per capita crime rate by town.
ZN: proportion of residential land zoned for lots over 25,000 sq.ft.
INDUS: proportion of non-retail business acres per town.
CHAS: Charles River dummy variable (= 1 if tract bounds river; 0 otherwise).
NOX: nitric oxides concentration (parts per 10 million).
RM: average number of rooms per dwelling.
AGE: proportion of owner-occupied units built prior to 1940.
DIS: weighted distances to five Boston employment centers.
RAD: index of accessibility to radial highways.
TAX: full-value property-tax rate per $10,000.
PTRATIO: pupil-teacher ratio by town.
B: 1000(Bk - 0.63)^2 where Bk is the proportion of black people by town.
LSTAT: % lower status of the population.
MEDV: median value of owner-occupied homes in $1000s.

**Data Cleaning**
This dataset is considered to be a "clean" dataset, meaning that it has already been preprocessed and cleaned . 

**Explanation**
The data was splitted into 80 and 20 ratio for training and test set. Performed square root transformation for all the independdent features, I used Linear Regression,Random Forest Regressor,XGB boost regressor,Gradient boost Regressor models are used amongst which 'Linear Regression' performed well.

**Acknowledgements**

This dataset can be found in the UCI Machine Learning Repository (https://archive.ics.uci.edu/ml/datasets/housing). The dataset is also included in the Scikit-Learn library in Python.

**Quick Glance**

<img width="441" alt="image" src="https://user-images.githubusercontent.com/119112861/236607704-7cfa4755-2838-4267-b82b-58e25c189303.png">

<img width="390" alt="image" src="https://user-images.githubusercontent.com/119112861/236609131-a009de43-fe2a-47ca-9ace-57956bb6a2c8.png">

<img width="397" alt="image" src="https://user-images.githubusercontent.com/119112861/236609117-b83afd0f-862b-4511-8d07-29ece64a9e8a.png">

<img width="383" alt="image" src="https://user-images.githubusercontent.com/119112861/236609101-43eb36b2-ee93-43bf-9136-2b7355c3dbbc.png">


