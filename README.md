# 🪨 Rock vs Mine Prediction

This is a machine learning-based application that predicts whether a given sonar signal represents a **rock** or a **mine**. The system utilizes a dataset of sonar readings and applies a classification model to make accurate predictions.

## 🔍 Features

- Input sonar frequency data (60 attributes)
- Predicts the object type: **Rock** or **Mine**
- Supervised learning model using Logistic Regression
- Trained model saved for future predictions
- Command-line interface for testing with new data

## 🧠 Technologies Used

- **Python**
- **Pandas** and **NumPy** – Data handling
- **Scikit-learn** – Model training and evaluation
- **Joblib** – Model serialization
- **CLI** – User input and prediction via terminal

## 🚀 Workflow

1. Load and preprocess the sonar dataset
2. Split data into training and testing sets
3. Train the Logistic Regression model
4. Save the trained model using `joblib`
5. Load the model and make predictions on new input

