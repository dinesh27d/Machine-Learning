# House Price Prediction using Multiple Linear Regression

## Overview

This project involves predicting house prices using multiple linear regression. The model uses several features such as square feet (SqFt), the number of bedrooms, the number of bathrooms, and the number of offers to predict the price of a house.

## Data Handling

- The dataset is loaded from a CSV file named `House-prices.csv`.
- Missing values in the dataset, particularly in the `Bedrooms` column, are handled by filling them with the median value of the column. This ensures that the data is clean and ready for model training.

## Model Training

A multiple linear regression model is trained using the features:
- **SqFt**: Square feet of the house.
- **Bedrooms**: Number of bedrooms.
- **Bathrooms**: Number of bathrooms.
- **Offers**: Number of offers made on the house.

The target variable for the model is the house price (`Price`).

## Model Coefficients and Intercept

After training, the model's coefficients and intercept are calculated. These represent the influence of each feature on the house price:
- The coefficients correspond to the slope values for each feature.
- The intercept is the base price when all feature values are zero.

## Prediction

The model can be used to predict the price of a house given specific values for square feet, bedrooms, bathrooms, and offers. For example, to predict the price of a house with 2500 square feet, 4 bedrooms, 4 bathrooms, and 2 offers, the model applies the linear regression formula:

y = (m1 * x1 + m2 * x2 + m3 * x3 + m4 * x4) + b

i.e.,

y = (63.59111634 * 2500 + 8329.83542667 * 4.0 + 13203.47774912 * 4 + -13588.97635016 * 2) + -19316.868774358358

Where:
- \( m_1, m_2, m_3, m_4 \) are the coefficients for SqFt, Bedrooms, Bathrooms, and Offers respectively.
- \( x_1, x_2, x_3, x_4 \) are the feature values.
- \( b \) is the intercept.

This formula provides the estimated house price.

## Conclusion

This model serves as a basic example of how multiple linear regression can be applied to predict house prices based on various features. It can be further improved with more complex models or additional features.

