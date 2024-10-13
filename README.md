# Cellphone-price-predition
This repository contains a machine learning model for predicting cellphone prices based on various features using regression techniques. The notebook processes the data, selects important features, and trains a model to predict prices.

Table of Contents
Introduction
Dataset
Requirements
Model Workflow
Usage
Results
License
Introduction
The Cellphone Price Prediction project aims to predict the prices of cellphones based on their features using a supervised machine learning approach. The model utilizes multiple feature selection techniques and regression algorithms to create a reliable predictive model.

Dataset
The dataset used in this project is stored in a CSV file (train.csv) and contains several columns representing different features of cellphones. Some of the features include:

Battery life
RAM
Internal storage
Screen size
Camera quality
Processor speed
The target variable is the Price of the cellphone.

Requirements
The following Python libraries are required to run the notebook:

pandas: For data manipulation and preprocessing.
numpy: For numerical operations.
matplotlib: For data visualization.
sklearn: For machine learning models and feature selection.
To install the required libraries, run:

bash
Copy code
pip install -r requirements.txt
Example requirements.txt:
Copy code
pandas
numpy
matplotlib
scikit-learn
Model Workflow
Data Loading: The dataset is loaded from a CSV file.
Exploratory Data Analysis (EDA): A preliminary analysis of the dataset is performed, including visualizations like box plots, histograms, and pair plots.
Feature Selection: Features are selected using techniques like SelectKBest with a scoring function suited for regression (e.g., f_regression).
Model Training: Different regression models (like Linear Regression, Decision Trees, etc.) are trained to predict the cellphone prices based on selected features.
Model Evaluation: The models are evaluated using metrics like mean squared error (MSE) and R-squared.
Key Techniques Used:
Feature Selection: Uses SelectKBest to select the top 10 most important features.
Regression Algorithms: Trains models like Linear Regression, Decision Trees, or other regressors.
Usage
Clone this repository:
bash
Copy code
git clone https://github.com/yourusername/cellphone-price-prediction.git
cd cellphone-price-prediction
Install the required dependencies:
bash
Copy code
pip install -r requirements.txt
Open the Jupyter Notebook:
bash
Copy code
jupyter notebook
Run the Cellphone Price Prediction.ipynb file step-by-step to build and evaluate the model.
Results
The model successfully predicts cellphone prices with reasonable accuracy based on the given features. The selected features contribute significantly to the price, with the final model achieving good results on the test data.

The final evaluation metrics include:

Mean Squared Error (MSE): The lower, the better.
R-Squared Score: Measures the proportion of variance explained by the model.
