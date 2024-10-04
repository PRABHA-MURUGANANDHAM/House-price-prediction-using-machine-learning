# House-price-prediction-using-machine-learning
House Price Prediction using Logistic Regression
Table of Contents
Introduction
Dataset
Prerequisites
Installation
Project Structure
Features
Model Training
Evaluation
How to Use
Conclusion
1. Introduction
This project is aimed at predicting house prices based on various features using Logistic Regression. Instead of predicting the exact price, the houses are categorized into price ranges (e.g., Low, Medium, High). The model classifies houses into these categories based on input features such as the number of bedrooms, location, size, etc.

2. Dataset
The dataset used for this project consists of various attributes of houses, such as:
Number of Bedrooms
Area (in square feet)
Number of Bathrooms
Location
Year Built
Each house also has a corresponding price, which is categorized into different price ranges (e.g., Low: <$100,000, Medium: $100,000 - $500,000, High: >$500,000).
3. Prerequisites
Before you begin, ensure you have the following installed:

Python 3.x
Required libraries (listed in requirements.txt)
4. Project Structure
data/: Folder containing the dataset used for the project.
notebooks/: Jupyter notebooks for exploratory data analysis and model building.
models/: Saved models after training.
src/: Python scripts for data preprocessing, feature selection, model training, and evaluation.
requirements.txt: List of dependencies.
README.md: Project documentation.
5. Features
Data Preprocessing: The dataset is cleaned, and missing values are handled. Features are normalized or encoded as needed.
Feature Selection: Key features contributing to the house price prediction are selected.
Logistic Regression Model: A Logistic Regression classifier is trained to categorize house prices into different ranges.
Evaluation: The model is evaluated using various classification metrics such as accuracy, precision, recall, and F1-score.
6. Model Training
Data Preprocessing:
Normalize the continuous features (like area).
Encode categorical features (like location).
Feature Selection:
Use methods like correlation analysis and feature importance to select the most relevant features.
7.Evaluation
Once the model is trained, it is evaluated on the test set using classification metrics:

Accuracy: Measures the percentage of correct predictions.
Confusion Matrix: Shows the number of true positives, false positives, true negatives, and false negatives.
Precision, Recall, and F1-score: Provide insights into the model's performance for each price range.
8. Conclusion
This project demonstrates the use of Logistic Regression to classify house prices into different price ranges. It can be extended to use more advanced models such as Random Forest or XGBoost for better performance.

