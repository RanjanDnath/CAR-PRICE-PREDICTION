# CAR-PRICE-PREDICTION
The focus of this project is developing machine learning models that can accurately predict the price of a used car based on its features.

# How to use?
Clone the repository
Install the required packages in "requirements.txt" file.
Some library package are: numpy, pandas, matplotlib, seaborn, scikit-learn , 
 ML : piping ;
Run the "application.py" file And you are good to go.

# What this project does?
This project takes the parameters of an used car like: Company name, Model name, Year of Purchase, Fuel Type and Number of Kilometers it has been driven.
It then predicts the possible price of the car. For example, the image below shows the predicted price of our Hyundai Grand i10.


# How this project does?
First of all the data was scraped from Quikr.com (https://quikr.com) 
Link for data: https://github.com/RanjanDnath/CAR-PRICE-PREDICTION/blob/main/quikr_car.csv

The data was cleaned (it was super unclean :( ) and analysed.
Link for cleaned data: https://github.com/RanjanDnath/CAR-PRICE-PREDICTION/blob/main/Cleaned_Car_data.csv

Then a Linear Regression model was built on top of it which had 0.89 R2_score.
Link for notebook: https://github.com/RanjanDnath/CAR-PRICE-PREDICTION/blob/main/_EXISTING%20CAR%20PRICE%20PREDICTION.ipynb

This project was given the form of an website built on Flask where we used the Linear Regression model to perform predictions.
 Website link : http://127.0.0.1:5000/
 
 # Benifit : 
 1) Based on the given input, it gives the prediction which includes the selling price of the existing car and also some of the available cars in that price.
 2) For Time reduceness 
 3) Online pricing services: There are websites that offers an estimate value of a car. They may have a good prediction model.
 
 
 
