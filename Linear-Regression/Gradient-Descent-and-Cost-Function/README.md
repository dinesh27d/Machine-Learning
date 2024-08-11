# Gradient Descent for Linear Regression

## Introduction

Gradient Descent is an optimization algorithm used to minimize a function by iteratively moving towards the minimum value of the function. It is widely used in machine learning and statistics to fit models to data. In the context of linear regression, Gradient Descent helps in finding the best-fit line for a given set of data points by minimizing the cost function.

<img width="870" alt="Gradient-Decent-Graph" src="https://github.com/user-attachments/assets/17583ecb-5a7e-4f99-95e7-8b8d97e52434">

### Cost Function

For linear regression, the cost function is typically the Mean Squared Error (MSE), which measures the average squared difference between the actual and predicted values. The goal of Gradient Descent is to minimize this cost function by adjusting the model parameters, `m` (slope) and `b` (intercept).

<img width="921" alt="Mean-squared-error" src="https://github.com/user-attachments/assets/0020f2a5-2f64-4376-8a72-705f5a73e7a2">

## Code Explanation

The provided Python code demonstrates how Gradient Descent can be used to fit a linear regression model to a set of data points. 

### Gradient Descent Function (First Implementation)

- **Initial Values**: Initializes `m` (slope) and `b` (intercept) to zero.
- **Iterations**: Iteratively updates `m` and `b` to minimize the cost function using the gradients.
- **Outputs**: Prints the current values of `m`, `b`, cost, and iteration number.

### Gradient Descent Function (Second Implementation with Visualization)

- **Initial Values**: Initializes `m_curr` and `b_curr` to zero.
- **Updates**: Iteratively updates `m_curr` and `b_curr` while plotting the regression line and data points.
- **Plotting**: Displays a plot showing the data points and the line of best fit.

<img width="588" alt="Visualization_for_gradient_decent" src="https://github.com/user-attachments/assets/7a1364e6-2090-4f9e-a02f-0d3aa465f961">

## Visualization

1. **Cost Function Formula**: 
<img width="916" alt="Cost-function" src="https://github.com/user-attachments/assets/1364fecd-47b7-455a-9696-259ac9460d23">

2. **Gradient Formulas**:
<img width="1043" alt="slope-and-intercept-derivative-formula" src="https://github.com/user-attachments/assets/8c76864b-7215-4f62-bb05-f9328bd1d869">
<img width="1250" alt="slope-and-intercept-formula" src="https://github.com/user-attachments/assets/72069527-257b-43e1-8d07-259914774852">

## Requirements

- `Python`
- `NumPy`
- `Matplotlib`

You can install the required packages using:

```bash
pip install numpy matplotlib

