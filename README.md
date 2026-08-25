Iris Species Classification using Random Forest
A beginner-friendly machine learning project that classifies Iris flowers into their species using the Random Forest Classifier from Scikit-learn.
Iris dataset is sourced from OpenML


Project Overview
The Iris dataset is a classic classification dataset containing measurements of Iris flowers. The goal of this project is to train a machine learning model that can predict the species of an Iris flower based on its physical measurements.
The dataset was divided into:
80% training data — used to train the model
20% testing data — used to evaluate the trained model

A Random Forest Classifier was then trained on the training data and used to predict the species of the unseen test data.
Dataset
The Iris dataset contains four input features:
Feature	Description
Sepal Length	Length of the sepal
Sepal Width	Width of the sepal
Petal Length	Length of the petal
Petal Width	Width of the petal
The target variable is the Iris species:
Iris Setosa
Iris Versicolor
Iris Virginica

Machine Learning Approach
1. Data Preparation
The Iris dataset was loaded and separated into features (`X`) and target labels (`y`).
2. Train-Test Split
The dataset was divided into an 80:20 ratio.
3. Model Training
A Random Forest Classifier was trained using the training data.
Random Forest is an ensemble learning algorithm that combines multiple decision trees to make a final prediction.
4. Prediction
The trained model was used to predict the classes of the test dataset.
5. Evaluation
The predicted labels were compared with the actual test labels using classification accuracy.
Result
The model achieved an accuracy of:
97.05%

This represents the accuracy obtained on the held-out test dataset.
Technologies Used
Python
Scikit-learn
Pandas
NumPy
Jupyter Notebook
```
Project Workflow

Iris Dataset
     ↓
Data Preparation
     ↓
80% Training / 20% Testing
     ↓
Random Forest Classifier
     ↓
Train Model
     ↓
Predict Test Data
     ↓
Compare Predictions with Actual Values
     ↓
97.05% Test Accuracy
```

How to Run
Clone the repository.
Open the Jupyter Notebook.
Install the required Python libraries if necessary.
Run the notebook cells sequentially.
View the model predictions and accuracy at the end.
Future Improvements
Generate a confusion matrix.
Display precision, recall, and F1-score.
Compare Random Forest with other classification algorithms.
Visualize feature importance.
Experiment with different train-test split ratios and Random Forest parameters.
Learning Outcome
This project demonstrates the basic machine learning workflow:
Dataset → Train/Test Split → Model Training → Prediction → Evaluation
It also provides hands-on experience with the Random Forest Classifier and evaluating a classification model using test data.
