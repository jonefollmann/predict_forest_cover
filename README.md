
# Predicts the type of forest cover from cartographic data using custom containers with AI Platform Training

Objectives:

Create a train and a validation split with BigQuery
Wrap a machine learning model into a Docker container and train in on AI Platform
Use the hyperparameter tunning engine on Google Cloud to find the best hyperparameters
Deploy a trained machine learning model Google Cloud as a rest API and query it
In this lab, you develop a multi-class classification model, package the model as a docker image, and run on AI Platform Training as a training application. The training application trains a multi-class classification model that predicts the type of forest cover from cartographic data. The dataset used in the lab is based on Covertype Data Set from UCI Machine Learning Repository.

Scikit-learn is one of the most useful libraries for machine learning in Python. The training code uses scikit-learn for data pre-processing and modeling.

The code is instrumented using the hypertune package so it can be used with AI Platform hyperparameter tuning job in searching for the best combination of hyperparameter values by optimizing the metrics you specified.

Note: project developed during GCP studies.
