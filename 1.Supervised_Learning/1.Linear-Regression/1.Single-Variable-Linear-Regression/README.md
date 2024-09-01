
# Linear Regression - Single Variable

Linear regression is a data analysis technique that predicts the value of unknown data by using another related and known data value.

## House Price Prediction using Linear Regression

This project demonstrates a basic linear regression model to predict house prices based on square footage using Python's scikit-learn library. 

## Installation

To run this project, you'll need to install the following Python libraries:

- `pandas`
- `matplotlib`
- `scikit-learn`

### IDE
  - ![VS Code](https://img.shields.io/badge/Visual_Studio_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white)
  - ![pyCharm](https://img.shields.io/badge/PyCharm-000000.svg?&style=for-the-badge&logo=PyCharm&logoColor=white)
  - ![Jupyter Notebook](https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white)

You can install these libraries using pip:

```
pip install pandas
pip install matplotlib
pip install scikit-learn
```

## Usage

- `Data Loading`

    The data is loaded from a CSV file named `house-prices.csv`. This dataset contains information about house prices and their corresponding square footage.

- `Model Training`

    A linear regression model is trained using square footage (`SqFt`) as the feature and house price (`Price`) as the target variable. The model is then used to make predictions on test data.

- `Model Evaluation`

    After training, the model's coefficients and intercept are displayed. These values represent the slope and intercept of the regression line, respectively.

- `Prediction`

    The model can predict the price for a house with a given square footage. For example, you can predict the price for a house with 5000 square feet.

- `Visualization`

    The relationship between square footage and price is visualized using a scatter plot with a regression line overlay.

## Example

To predict the price for a house with 5000 square feet, you can use the formula:

`Price = slope × SqFt + intercept`

For the given model, this calculation yields:

`70.22631824 × 5000 + (-10091.129909123061)`

## Results

<img src="https://github.com/user-attachments/assets/cfff3fde-c1c4-4322-a602-5cdd5190dc37" alt="1-1-1" width="400"/>
<img src="https://github.com/user-attachments/assets/44ac7607-09b3-4ebc-898f-4066745036c9" alt="1-1-2" width="400"/>







