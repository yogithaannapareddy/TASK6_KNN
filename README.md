# K-Nearest Neighbors (KNN) Classification

## 1. Choose a Classification Dataset and Normalize Features

The Iris dataset was used for this task. The dataset was downloaded and loaded using Pandas.

The features were normalized using `StandardScaler` before applying the KNN algorithm.

## 2. Use KNeighborsClassifier from Scikit-learn

The `KNeighborsClassifier` from Scikit-learn was used to build the KNN classification model.

## 3. Experiment with Different Values of K

Different K values were tested:

- K = 1
- K = 3
- K = 5
- K = 7
- K = 9

The accuracy for each K value was calculated and compared.

## 4. Evaluate the Model Using Accuracy and Confusion Matrix

The model was evaluated using:

- Accuracy Score
- Confusion Matrix

The K value with the highest accuracy was selected for the model.

## 5. Visualize Decision Boundaries

Two features from the Iris dataset were selected to visualize the KNN decision boundaries.

The visualization shows how the KNN classifier separates different classes based on the selected features.
