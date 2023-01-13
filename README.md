# Car Price Prediction Using Macine Learning
### Final Capstone Project - Danish Ali

## Project Overview
An automobile company aspires to create a Machine Learning Model that estimate used car prices from a given dataset. It will facilitate a buying and selling of used cars for individuals and dealerships.

## Goal of the Project
* To understand the important features of dataset which are affecting selling prices of the cars.
* To dicover the best ML model for an automobile company to assist individuals and dealerships for prediction of the cars prices.

## Data Features
There are 7 columns in dataset, which all are affecting selling price of the cars. Columns are following:
* name
* year
* km_driven
* fuel
* seller_type
* transmission
* owner
 ![image](https://user-images.githubusercontent.com/109092241/212258994-d58a2009-e519-4902-b0bd-d0e32b42f161.png)
This graph depicts following points:
* Selling Price of cars seems to have higher prices when sold by Dealers when compared to Individuals.
* It can be observed that Selling Price would be higher for cars that are Automatic.
* Selling Price of cars with Fuel Type of Diesel is higher than Petrol and CNG.

### Relation between selling price and some important features affecting the selling price which are very self explanatory.

![image](https://user-images.githubusercontent.com/109092241/212260008-ba141588-31e5-4fec-80d5-1df2d5882bff.png)


## ML Model
I used two Machine Learning Models in this project which are following:
* Linear Regression Model 
* Random Forest Model

Both models were almost showing same results but I considered Random Forest Model as a best model due to R-Squared Score which was 96% for Random Forest was bit more acuurate as compare to Linear Regression Model.
* Linear Regression Model
![image](https://user-images.githubusercontent.com/109092241/212263701-8b8e492f-fb9e-4284-9e9a-26ef3ec0952c.png)

* Random Forest Model
![image](https://user-images.githubusercontent.com/109092241/212264020-5c18825b-a375-43b8-853f-02724ca0e5b7.png)


## Consclusion
* Car year is affecting negatively as older the car lesser the Selling Price
* Random Forest Model is being considered as the best model which is 96% accurate while predicting the car prices
* Selling price of cars with fuel type Diesel is more higher than the ones Petrol and CNG

## Citation
This article was very helpful while building my models

https://towardsdatascience.com/used-car-price-prediction-using-machine-learning-e3be02d977b2
