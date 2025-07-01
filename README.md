# Task 6: K-Nearest Neighbors (KNN) Classification – Iris Dataset

## Objective
This task focuses on implementing the K-Nearest Neighbors (KNN) algorithm for classification. The model is trained to classify flower species based on the Iris dataset features.

## Dataset
- Source: [Iris Dataset – UCI](https://www.kaggle.com/datasets/uciml/iris)
- Loaded using `sklearn.datasets.load_iris()`

## Tools Used
- Python
- Pandas
- Scikit-learn
- Matplotlib

## What Was Done
- Loaded and standardized the Iris dataset
- Split the data into training and test sets
- Trained a KNN model with different values of K (1 to 10)
- Evaluated each model using accuracy and confusion matrix
- Plotted a line graph of K vs Accuracy
- Visualized decision boundaries using first two features

## Output
- `Task 6: K-Nearest Neighbors (KNN) Classification – Iris Dataset.ipynb` – includes code, plots, and model evaluation
- Identified K=3 as a good performing value
- Displayed confusion matrix and accuracy for final evaluation
