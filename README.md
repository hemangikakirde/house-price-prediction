# California House Price Prediction

This project predicts house prices using the California Housing Dataset and a Linear Regression model in a Jupyter Notebook.

## About the Project

The goal of this project is to predict house prices based on features like median income, location, and other factors. The dataset used is the **California Housing Dataset**, which contains 20,640 samples and 8 features.

## Features

The dataset includes the following features:
- 'MedInc': Median income in the block group
- 'HouseAge': Median house age in the block group
- 'AveRooms': Average number of rooms per household
- 'AveBedrms': Average number of bedrooms per household
- 'Population': Block group population
- 'AveOccup': Average number of household members
- 'Latitude': Latitude of the block group
- 'Longitude': Longitude of the block group

The target variable is:
- 'MedHouseVal': Median house value for households in the block group (in hundreds of thousands of dollars)

# How It Works

1. The dataset is loaded and split into training and testing sets.
2. A Linear Regression model is trained on the training data.
3. The model predicts house prices for the test data.
4. The model's performance is evaluated using **Mean Squared Error (MSE)** and **R-squared (R²)**.

# Results

After running the code, you will see:
- The Mean Squared Error (MSE) and R-squared values.
- The coefficients of the model, which show the impact of each feature on house prices.

# How to Use

1. Clone this repository.
2. Open the 'house_price_prediction.ipynb' file in Jupyter Notebook.
3. Run the cells to see the results.

# Requirements

- Python 3.x
- Libraries: 'numpy', 'scikit-learn', 'jupyter'
