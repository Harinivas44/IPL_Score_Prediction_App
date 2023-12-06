# IPL_Score_Prediction_App

## Overview

Welcome to the IPL Score Prediction App! This project aims to provide a user-friendly interface for predicting the total score in an IPL cricket match based on various input parameters. The prediction model is built using a Linear Regression algorithm, and the app is developed using Flask, a web framework for Python.

## Features

1. Predictions Made Easy
Input the batting and bowling teams, overs, runs, wickets, runs in the last 5 overs, and wickets in the last 5 overs.
Click the "Predict" button to get an estimated total score for the match.
2. User-Friendly Interface
The app features a simple and intuitive interface, making it accessible for users with varying levels of technical expertise.
3. Model Accuracy
The prediction model is trained on a comprehensive dataset, ensuring reliable and accurate predictions for a wide range of scenarios.

## Usage
To use the IPL Score Prediction App:

* Clone the repository to your local machine.
* Install the required dependencies by running pip install -r requirements.txt.
* Run the Flask app using python app.py.
* Access the app through your web browser at http://127.0.0.1:5000/.
* Input the relevant details and get instant score predictions!

## Code Structure
The project is structured as follows:

app.py: Contains the Flask application code for handling web requests and rendering HTML templates.

model_ipl.pkl: Pickle file containing the trained Linear Regression model for score predictions.

ipl.csv: Dataset used for training the model, containing match details such as teams, runs, wickets, overs, and more.

ipl_prediction.ipynb: Jupyter Notebook containing the data preprocessing, model training, and evaluation steps.

## Model Training
The Linear Regression model is trained on a cleaned and preprocessed dataset derived from the IPL matches. The training data includes features such as batting and bowling teams, overs, runs, wickets, and historical performance in the last 5 overs.

The model achieves a training score of approximately 65% and a testing score of about 75%, demonstrating its effectiveness in predicting IPL match scores.
