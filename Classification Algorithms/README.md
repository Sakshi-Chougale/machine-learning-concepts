# Comparison of Classification Algorithms

Classification models predict categories, such as spam/not spam or approved/rejected. Comparing several algorithms helps reveal which model is most suitable for a particular dataset and objective.

## Models Covered

- **Logistic Regression:** estimates class probabilities using a linear decision function.
- **Decision Tree:** makes predictions through feature-based decision rules.
- **Random Forest:** combines multiple decision trees.
- **Support Vector Machine (SVM):** separates classes using a decision boundary.
- **K-Nearest Neighbors (KNN):** predicts from nearby labeled examples.
- **Naïve Bayes:** applies Bayes' theorem with a conditional-independence assumption.

## Evaluation Metrics

- **Accuracy:** proportion of all predictions that are correct.
- **Precision:** among predicted positive cases, the proportion that are truly positive.
- **Recall:** among actual positive cases, the proportion correctly identified.
- **F1-score:** harmonic mean of precision and recall; useful when both matter.

## Recommended Workflow

1. Prepare features and labels.
2. Split the data into training and test sets.
3. Train each classifier using the same split.
4. Generate predictions and calculate evaluation metrics.
5. Compare results in a table and consider class balance and the cost of different errors.

## Real-World Example

A bank may compare classifiers for flagging potentially fraudulent transactions. High recall may help catch more fraud, while high precision may reduce false alarms.

## Important Note

Accuracy alone can be misleading on imbalanced datasets. Choose metrics based on the real cost of false positives and false negatives.
