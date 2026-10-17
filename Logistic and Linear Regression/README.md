# Linear and Logistic Regression

Linear Regression and Logistic Regression are supervised learning algorithms, but they solve different types of problems.

## Linear Regression

Linear Regression predicts a continuous numerical value, such as a house price or delivery time. A simple model can be represented as:

`y = mx + c`

Here, `x` is an input feature, `y` is the predicted value, `m` is the slope, and `c` is the intercept.

## Logistic Regression

Logistic Regression is commonly used for classification. It estimates the probability of a class, often using the sigmoid function, and a decision threshold can convert that probability into a class label.

## Typical Workflow

1. Select input features and a target.
2. Split the data into training and testing sets.
3. Train the appropriate model.
4. Generate predictions.
5. Evaluate the results using metrics suited to the task.

## Real-World Examples

- **Linear Regression:** estimate a house price from its size and other features.
- **Logistic Regression:** predict whether an email is spam or not spam.

## Evaluation

For Linear Regression, common metrics include MAE, MSE, and R². For Logistic Regression, common metrics include accuracy, precision, recall, and F1-score.

## Tools

Python and Scikit-learn.
