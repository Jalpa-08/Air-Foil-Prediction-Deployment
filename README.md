# Airfoil-Regression-With-Deployment
This is a  project to elaborate how Machine Learning Models are deployed in production using Flask API

Prerequisites

**Prerequisites**
You must have Scikit Learn, Pandas (for Machine Leraning Model) and Flask (for API) installed.


**Project Structure**

This project has four major parts :


app.py - This contains Flask APIs that receive air foil details through GUI or API calls, computes the precited value based on our model and returns it.


templates - This folder contains the HTML template to allow user to enter employee detail and displays the predicted air foil regression.

**Running the project**

Ensure that you are in the project home directory. Create the machine learning model by running below command -



This would create a serialized version of our model into a file model.pkl



1. Run app.py using below command to start Flask API

2. python app.py

3. By default, flask will run on port 5000.



Navigate to URL http://localhost:5000

You should be able to view the homepage as below :alt text



Enter valid numerical values in all  input boxes and hit Predict.



If everything goes well, you should be able to see the predicted vaule on the HTML page! alt text


