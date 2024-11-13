# CodeAlpha_Car_Price_Prediction
## Brief Discription
Machine Learning Project that predicts selling prices of cars based on specific features.
## Detailed Description
The goal of this project is to use machine learning models to predict the selling price of cars based on various features, such as the year of manufacture, fuel type, transmission, kilometers driven, and the car's present price. We explore data preprocessing, model training, and evaluation techniques.

Dataset
The dataset can be be found on Kaggle under: `Car price prediction(used cars)`, and it includes the following features:

`Year`: Year the car was manufactured

`Present Price`: Current market price of the car

`Driven_kms`: Kilometers driven

`Fuel_Type`: Fuel type of the car (CNG, petrol, or diesel)

`Selling Type`: Selling method of the car (Dealer or Individual)

`Transmission`: Transmission type (manual or automatic)

`Owner`: Number of previous owners

The target variable for prediction is the `Selling Price` of the car.

### Workflow and Methods

1. Data Preprocessing

   Handling Missing Values: The dataset is checked and cleaned for any missing values.

   Encoding Categorical Variables: Categorical variables, such as Fuel_Type and Transmission, are transformed using label encoding based on the number of unique values to make them usable by machine learning algorithms.

   Feature Selection: We remove unnecessary or redundant features, focusing on those most relevant to car price prediction.

3. Model Selection

   Linear Regression: A baseline model to understand the relationship between features and the selling price.

   Random Forest Regressor: An ensemble model is also trained to capture non-linear patterns in the data, potentially improving predictive accuracy.

5. Evaluation

   R-Squared: The coefficient of determination is used to evaluate the model’s accuracy and interpretability.

   Model Interpretation: We analyze the coefficients and feature importances from linear regression model to understand how each feature impacts car pricing.

