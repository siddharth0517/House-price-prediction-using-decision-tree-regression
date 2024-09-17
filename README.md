# House Sale Price Prediction Using Decision Tree Regression
+ This project uses the AmesHousing dataset to predict house sale prices. A Decision Tree Regressor is implemented to create a model that can predict the price of a house based on various features like square footage, location, number of rooms, etc.

## Table of Contents
+ Introduction
+ Dataset
+ Requirements
+ Installation
+ Modeling
+ Results
+ Conclusion
+ References
## Introduction
+ In this project, I use machine learning techniques to predict house prices based on a range of features. The goal is to develop a decision tree model that can accurately predict the house sale price given its features.

## Dataset
The dataset used in this project is the AmesHousing dataset. It consists of 2,930 observations with 82 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa. The dataset includes various features like:

+ Lot Area
+ Year Built
+ Overall Quality
+ Neighborhood
+ Number of Rooms
+ Garage Area, and many more.
+ For more information on the dataset

## Requirements
+ The project requires the following libraries:

+ Python 3.x
+ pandas
+ numpy
+ scikit-learn
+ matplotlib
## Modeling
+ The decision tree regression model is trained to predict house prices. The following steps were followed:

## Model Evaluation: 
+ The model was evaluated using metrics such as Mean Squared Error (MSE) and R² score.
## Results
+ The decision tree model achieved the following evaluation metrics:

+ MSE: 2598325061.40
+ R² Score: 0.6042
+ The model performed well, predicting house prices with reasonable accuracy. However, there is room for improvement using more sophisticated models like Random Forest or Gradient Boosting.

## Conclusion
+ This project demonstrates the implementation of a decision tree regression model to predict house sale prices using the AmesHousing dataset. The results show that decision tree regression can be an effective approach for this task, though further optimizations could improve performance.

## References
+ AmesHousing dataset on Kaggle
+ Scikit-learn Decision Tree Regressor
