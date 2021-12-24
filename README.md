<img src="https://github.com/rachmaapriyani/FlightPricePrediction/blob/main/flight.gif"/>

## Background

Flight ticket prices can be something hard to guess, today we might see a price, check out the price of the same flight tomorrow, and it will be a different story.
To solve this problem, we have been provided with prices of flight tickets for various airlines between the months of March and June of 2019 and between various cities, using which we aim to build a model which predicts the prices of the flights using various input features.


## Dataset Descriptions 

This Project is used to predict the flight prices. We will use Flight Price Dataset provided by [Kaggle Flight Price](https://www.kaggle.com/nikhilmittal/flight-fare-prediction-mh). This dataset consists of 10683 records with 11 columns that explain about the flight in India by some Indian and foreign Airlines in 2019. We will analyze this dataset using Machine learning techniques in order to predict the flight ticket price based on the features provided in the columns of the dataset. We will begin the Data Science Life Cycle to process the data such as Cleaning the dataset, feature engineering, splitting dataset, feature selection, and hyperparameter tuning.


## Modelling and Evaluation

* Algorithms used
  * Random Forest
  * Extra Trees Regressor


* Metric - Since the target variable is a continuous variable, regression evaluation metric RMSE (Root Mean Squared Error) and R2 Score (Coefficient of Determination) have been used.

## Results

### Feature Correlation
![Feature correlation](https://github.com/rachmaapriyani/FlightPricePrediction/blob/main/heatmap_corr.jpg)
### Feature Importance
![Feature importance](https://github.com/rachmaapriyani/FlightPricePrediction/blob/main/feature_selection.jpg)
### Accuracy before Hyperparameter Tuning
![Final Comparison](https://github.com/rachmaapriyani/FlightPricePrediction/blob/main/acuracy_before.jpg)
### Accuracy After Hyperparameter Tuning
![Final Comparison](https://github.com/rachmaapriyani/FlightPricePrediction/blob/main/accuracy_after.jpg)
