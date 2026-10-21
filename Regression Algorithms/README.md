# California Housing Price Prediction Using Regression Algorithms

Different regression algorithms learn different patterns. Comparing them on the same data split helps identify a model that suits the prediction task.

## Dataset Used

**Dataset Name:** California Housing Dataset

The California Housing Dataset is used to train and compare different regression models for predicting house values in California. It contains 20,640 samples and 8 numerical input features related to housing and demographics. The target variable represents the median house value for each district.

The dataset is loaded directly using Scikit-learn's `fetch_california_housing()` function, so a separate dataset file is not required when the dataset can be fetched successfully.

## Models Covered

- **Linear Regression:** models a linear relationship.
- **Polynomial Regression:** represents curved relationships by adding polynomial features to a regression model.
- **Decision Tree Regression:** predicts using a sequence of feature-based splits.
- **Random Forest Regression:** combines predictions from multiple decision trees.
- **Support Vector Regression (SVR):** fits a function while controlling deviations within a specified tolerance.

## Evaluation Metrics

- **MAE (Mean Absolute Error):** average absolute prediction error; lower is generally better.
- **MSE (Mean Squared Error):** average squared error; penalizes larger errors more strongly; lower is generally better.
- **R² score:** measures performance relative to predicting the target mean; higher is generally better, but it can be negative on test data.

## Recommended Workflow

1. Use the same training and test split for each model.
2. Train each model using the training data.
3. Generate predictions on the test data.
4. Calculate MAE, MSE, and R².
5. Compare results and consider model complexity and generalization.

## Real-World Example

Compare several models that predict house prices, then select one based on test performance and the needs of the application.

## Important Note

There is no universally best regression model. The result depends on the dataset, features, preprocessing, and model settings.
