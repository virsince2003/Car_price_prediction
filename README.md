# Car_price_prediction 🚗 

Project link: https://github.com/virsince2003/Car_price_prediction

# Aim

This project aims to predict the price of a used Car by taking its Company name, it's Model name, Year of Purchase, and other parameters.

## How to use?

1. Clone the repository
2. Install the required packages in the "requirements.txt" file.

Some packages are:
 - NumPy 
 - Pandas 
 - sci-kit-learn

3. Run the "app.py" file
And you are good to go. 

# Description

## What does this project do?

1. This project takes the parameters of a used car like Company name, Model name, Year of Purchase, Fuel Type and Number of Kilometers it has been driven.
2. It then predicts the possible price of the car. You can predict the price of your car 😉.

## How does this project do?

1. First of all the data was scraped from Quikr.com, which has data till year 2019 (https://quikr.com).
    Link for data: https://github.com/virsince2003/Car_price_prediction/blob/main/dataset/quikr_car.csv
2. The data was cleaned (it was very unclean :( ) and analysed.

3. Then a Linear Regression model was built on top of it which had 0.87 R2_score.

    Link for notebook: https://github.com/virsince2003/Car_price_prediction/tree/main/notebook

4. This project is about making a website built on  Flask where we used the Linear Regression model to perform predictions.
