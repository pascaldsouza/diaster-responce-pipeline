# Disaster Response Pipeline Project
by Pascal dsouza

## Table of Contents


1 Installation

2 Project Motivation

3 File Descriptions

4 Results

5 Licensing, Authors, and Acknowledgements

6 Instructions

# Project Description



In this course, we will built on your data engineering skills to expand your opportunities and potential as a data scientist. In this project, we will apply these skills to analyze disaster data from Figure Eight to build a model for an API that classifies disaster messages.

# Project Description

There are three components  to complete for this project.

1ETL Pipeline

An ETL pipleline was built to read data from two csv files, clean data, and save data into a SQLite database.

process_data.py: ETL pipeline scripts to read, clean, and save data into a database

 DisasterResponse.db:  output of the ETL pipeline, i.e. SQLite database containing messages and categories data

2 ML Pipeline

train_classifier.py: machine learning pipeline scripts to train and export a classifier
    
classifier.pkl: output of the machine learning pipeline, i.e. a trained classifer


3 Flask Web App

run.py: Flask file to run the web application
    
templates contains html file for the web applicatin

# Output 

1.An ETL pipleline was built to read data from two csv files, clean data, and save data into a SQLite database.

2.A machine learning pipepline was developed to train a classifier to performs multi-output classification on the 36 categories
in the dataset.

3. A Flask app was created to show data visualization and classify the message that user enters on the web page.

# Instructions 


1. Run the following commands in the project's root directory to set up your database and model.

    - To run ETL pipeline that cleans data and stores in database
        `python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/DisasterResponse.db`
    - To run ML pipeline that trains classifier and saves
        `python models/train_classifier.py data/DisasterResponse.db models/classifier.pkl`

2. Run the following command in the app's directory to run your web app.
    `python run.py`

3. Go to http://0.0.0.0:3001/

# Screenshots

5 screen shots are of the data visualisation is attached 

# gitHub links to access my files

https://github.com/pascaldsouza/diaster-responce-pipeline
