# Problem Statement
I have made this model which will predict estimated price of old car base on thier features.
As now a day we know many people are going to buy second hand car instaed of buying new one,
so its better investment option where we get almost 30-40% discount.
but main question is how will us know actual price of car base on their features so in orer to solve this problem
I have used this dataset to build model which will give a estimated price of car at which car should be sold.

## Content
This Dataset contains information of 5000+ old cars with different models and features like their Year, Name of the Company, Power, Fuel Type and Location.

This Dataset contains total 12 features

Name

Location

Year

Kilometers_Driven

Fuel_Type

Transmission

Owner_Type

Mileage

Engine

Power

Seats

Price

# Models I used:
1-Linear Regression

2-Polynomial regression

3-Polynomial regression with PCA due to high number of features

4-Random Forest regression without PCA

# conclusion
The best accuracy I got is from RandomForestRegressor

Accuracy on Traing set:  0.9825878876014844

Accuracy on Testing set:  0.9088929588684407

