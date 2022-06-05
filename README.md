# Covid_Regressor_Comparison
 Used Turkey's covid data to compare different regression methods. 

 Used Regressions: Random Forest, Support Vector Mavhine, Logistic Regression, XG Boost, Gradient Boosting Regression and RANSAC.


## Total Cases Covid-19 Turkey

![data](./pictures/data.png)

## Linear Regresison Estimated Line

![LRNS](./pictures/LinearRegNoShuf.png)

## SVR Estimated Line

![SVRNS](./pictures/SVRNoShuf.png)

## Random Forest Estimated Line

![RFNS](./pictures/RandomForestNoShuf.png)

## Gradient Boosting Estimated Line

![GBNS](./pictures/GradientBoostingNoShuf.png)

## XGBoost Estimated Line

![XGBNS](./pictures/XgBoostNoShuf.png)

## Ransac Estimated Line

![RANSACNS](./pictures/RansacNoShuf.png.png)


The reason for some of the regressors to predict a straight line is because they these regressors require a homogeneous input data to train. Since these estimated lines are without shuffling the data in the process of splitting to train and test. Lets look at the estimated lines with the shuffled data.

## Linear Regression With Shuffle Estimated Line

![LR](./pictures/LinearRegShuf.png.png)

## SVR With Shuffle Estimated Line

![SVR](./pictures/SVRShuf.png)

## Random Forest With Shuffle Estimated Line

![RF](./pictures/RandomForestShuf.png)

## Gradient Boosting With Shuffle Estimated Line

![GB](./pictures/GradientBoostingShuf.png)

## XGBoost With Shuffle Estimated Line

![XGB](./pictures/XgBoostShuf.png)

## Ransac With Shuffle Estimated Line

![RANSAC](./pictures/RansacShuf.png.png)

# Conclulsion

As we can see from the estimated line graphs, when the data is homogeneous the results we got are pretty good. This time we can see that other regression types surpasses the Linear Regression by a lot. The winning regression is the Random Forest Regression according to the r2 scores gained by each of the regressions. 

![result](./pictures/ShuffledR2scores.png)

