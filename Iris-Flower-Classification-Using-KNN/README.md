# K-Nearest Neighbors (KNN)

K-Nearest Neighbors is a supervised, instance-based algorithm used for classification and regression. For classification, it predicts a new point's class using the labels of its nearest training points.

## How It Works

1. Choose the number of neighbors, `K`.
2. Calculate distances from the new point to training points.
3. Select the `K` nearest points.
4. For classification, use a majority vote; for regression, commonly average their target values.

Euclidean distance is one commonly used distance measure.

## Real-World Example

To classify a fruit using features such as weight and size, KNN finds similar labeled fruits and predicts the class most common among the nearest examples.

## Important Concepts

- **Small K:** can be sensitive to noise.
- **Large K:** can smooth over local patterns.
- **Feature scaling:** important because distance calculations can be dominated by features with large numerical ranges.
- **Lazy learning:** KNN stores training examples and performs much of its work at prediction time.

## Evaluation

For classification, use metrics such as accuracy, precision, recall, and F1-score. Choose `K` using validation data rather than relying only on the test set.

## Tools

Python and Scikit-learn.
