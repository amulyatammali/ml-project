# House Price Prediction
# project objective:
 1> predicting house price in particular region inorder to help user to determine selling price and find right time to buy a house.
 2> predicting house price to offer valuable insights for real estate markets.
# Project Overview:
This project focuses on predicting house prices using the Boston Housing Dataset. The dataset contains various features such as crime rate, number of rooms, and accessibility to highways, which are used to train a machine learning model. The XGBoost algorithm is chosen for its effectiveness in regression tasks and handling complex datasets like the Boston dataset.
# Dataset Description: 
The Boston Housing Dataset is a well-known dataset in machine learning and contains 506 samples with 13 numerical features. These features are used to predict the median value of owner-occupied homes.
neumerical features of dataset are: 
1) Per capita crime rate
2) Number of rooms for dwelling.
3) Age of a person going to occupy
4) Tax
5) weighted distances to five Boston employment centres
6) proportion of non-retail business acres per town
7) proportion of residential land zoned for lots over 25,000 sq.ft.
8) Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
9) nitric oxides concentration (parts per 10 million)
10) index of accessibility to radial highways
11) pupil-teacher ratio by town
12) 1000(Bk - 0.63)^2 where Bk is the proportion of black people by town
13) lower status of the population.
>Target : the median value of owner-occupied homes.
# Flow of Project:
1) load dataset
2) prepocessing(handling missing values,feature engineering,data transformation)
3) data visualization ( correlation or covariance).
4) spliting of dataset into training and testing dataset.
5) model selection
6) traing model
7) model evalution
# model selection
XGBoost (Extreme Gradient Boosting) is chosen due to its capability to handle complex relationships within data, its robustness against overfitting, and its high prediction accuracy. Hyperparameter tuning may be performed to optimize model performance.
# model evalution 
1) On training data: 
   R square error: 0.9999948236320982
   mean absolute error: 0.0145848437110976
2) on testing data:
   R square error : 0.8711660369151691
   mean absolute error : 2.2834744154238233
#
By leveraging the Boston Housing Dataset and XGBoost algorithm, this project demonstrates the application of machine learning in predicting house prices, offering valuable insights and predictive capabilities for real estate markets and related industries.
