# Car value regressor

In this project, a linear regression model with multiple variables was developed to predict a car price based on some features like popularity index, vehicle make, age of the car etc. Rather than using libraries like scikit-learn, the normal equation was scripted in python. The machine learning pipeline along with all the functions required for preprocessing of the data are detailed in the attached jupyter notebook. The model accuracy was monitored in a step-wise manner through adding more features to the feature bank. Also rather than using the OneHotEncoder class from scikit-learn library to encode the categorical features, Pandas capability was leveraged to perform the one-hot encoding. Also the regularized linear regression was tried to address the issue of singularity and numerical instability, which is the case when populating the feature banks with more features. 
![](https://raw.githubusercontent.com/DanialArab/images/main/ML_bookcamp/car_price_predictor.PNG)

data source: https://www.kaggle.com/datasets/CooperUnion/cardataset
