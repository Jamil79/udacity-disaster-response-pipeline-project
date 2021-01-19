# udacity-disaster-response-pipeline-project

Description This Project is part of Data Science Nanodegree Program by Udacity in collaboration with Figure Eight. The dataset contains pre-labelled tweet and messages from real-life disaster events. The project aim is to build a Natural Language Processing (NLP) model to categorize messages on a real time basis.

This project is divided in the following key sections:

Processing data, building an ETL pipeline to extract data from source, clean the data and save them in a SQLite DB Build a machine learning pipeline to train the which can classify text message in various categories Run a web app which can show model results in real time

Programing Python 3.8 Machine Learning Libraries: NumPy, SciPy, Pandas, Sciki-Learn Natural Language Process Libraries: NLTK SQLlite Database Libraqries: SQLalchemy Model Loading and Saving Library: Pickle Web App and Data Visualization: Flask, Plotly

Additional Material In the data and models folder you can find two jupyter notebook that will help you understand how the model works step by step:

ETL Preparation Notebook: learn everything about the implemented ETL pipeline ML Pipeline Preparation Notebook: look at the Machine Learning Pipeline developed with NLTK and Scikit-Learn You can use ML Pipeline Preparation Notebook to re-train the model or tune it through a dedicated Grid Search section.

Important Files app/templates/*: templates/html files for web app

data/process_data.py: Extract Train Load (ETL) pipeline used for data cleaning, feature extraction, and storing data in a SQLite database

models/train_classifier.py: A machine learning pipeline that loads data, trains a model, and saves the trained model as a .pkl file for later use

run.py: This file can be used to launch the Flask web app used to classify disaster messages

Lcense I hereby put at the disposal of everyone the use of this program for free
