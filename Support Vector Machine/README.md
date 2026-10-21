# Iris Flower Classification Using Support Vector Machine (SVM)

Support Vector Machine is a supervised learning method commonly used for classification. It seeks a decision boundary that separates classes while maximizing the margin between the boundary and the closest training points.

## Dataset Used

**Dataset Name:** Iris Dataset

The Iris Dataset is used to train and test the Support Vector Machine (SVM) classification model. It contains 150 samples of iris flowers, with four features: sepal length, sepal width, petal length, and petal width. The target variable represents three flower species: Setosa, Versicolor, and Virginica.

The dataset is loaded directly in the notebook using Python code, so a separate dataset file is not required if the notebook downloads or loads it automatically.

## Key Concepts

- **Hyperplane:** the decision boundary separating classes.
- **Margin:** the distance between the boundary and the closest points from each class.
- **Support vectors:** points that help determine the boundary.
- **Kernel:** a function that enables SVM to model certain non-linear decision boundaries.
- **RBF kernel:** a commonly used kernel for non-linear classification.

## Typical Workflow

1. Prepare features and labels.
2. Split data into training and testing sets.
3. Scale features, often using `StandardScaler`.
4. Train an SVM classifier with a suitable kernel.
5. Predict test labels and evaluate the model.

## Real-World Example

An SVM could classify messages as spam or not spam using features extracted from their text.

## Important Notes

Feature scaling is often important for SVM. Model performance depends on choices such as the kernel and hyperparameters, including `C` and `gamma`.

## Tools

Python and Scikit-learn.
