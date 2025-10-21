# Built-Descriptive-Regression-Decision-Tree
The notebook explores the fundamentals of regression trees—how they fit non-linear data, adjust based on depth, and perform predictions on continuous values.
It provides a strong understanding of model interpretability and bias-variance trade-offs in tree-based regressors.


# Dataset

A synthetic dataset was generated using NumPy for simplicity and reproducibility:

Input feature (X): Random values between 0 and 1

Target (y): Quadratic function with added Gaussian noise

𝑦=4∗(𝑋−0.5)^2+noise
y=4∗(X−0.5)^2+noise

This helps visualize how the regression tree learns non-linear relationships without overfitting.



# Implementation Steps

Data Generation
Synthetic dataset created using NumPy random functions.
Data Visualization
Scatter plot to visualize input-target relationship.
Model Building
Implemented Decision Tree Regression using sklearn.tree.DecisionTreeRegressor.
Training
Fit the model on generated data.
Prediction & Visualization
Compared predictions for various tree depths (e.g., depth=2, depth=3, etc.).
Visualized predicted vs actual data using Matplotlib.
Interpretation
Showed how increasing tree depth improves fit but risks overfitting.
Illustrated the bias-variance trade-off.
