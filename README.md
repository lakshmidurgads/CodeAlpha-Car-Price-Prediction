# CodeAlpha Car Price Prediction

## Project Overview

This project focuses on predicting car selling prices using machine learning. The model uses features such as present price, car age, driven kilometers, fuel type, selling type, transmission, owner, and car name.

## Dataset

The dataset contains information about used cars and their selling prices.

### Features

- Car Name
- Year
- Present Price
- Driven kms
- Fuel Type
- Selling Type
- Transmission
- Owner

### Target

- Selling Price

## Data Preprocessing

The following steps were performed:

- Checked the dataset for missing values
- Removed duplicate records
- Created a new `Car Age` feature
- Converted categorical variables into numerical form using one-hot encoding
- Split the dataset into training and testing sets using an 80-20 split

## Machine Learning Model

A **Random Forest Regressor** was used to predict car selling prices.

## Model Evaluation

The model was evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

The model achieved an **R² score of approximately 0.55** on the test data.

## Visualizations

The project includes:

- Actual vs Predicted Selling Price visualization
- Feature importance analysis

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Conclusion

This project demonstrates the practical application of data preprocessing, feature engineering, categorical encoding, regression, model evaluation, and visualization for predicting car selling prices. The analysis also helps identify the features that contribute most to price prediction.
