*Note: I will not be uploading the Airbnb "listings" data set due to data protection reasons.*

Airbnb ML Modeling

This repository contains a project focused on the evaluation phase of the machine learning life cycle, using logistic regression on Airbnb listings data. The goal is to perform model selection, hyperparameter tuning, and feature selection to solve a classification problem.

Table of Contents

	•	Project Overview
	•	Data
	•	Tasks
	•	Results

Project Overview

In this lab, we practice the evaluation phase of the machine learning life cycle using logistic regression on Airbnb listings data. We perform model selection, hyperparameter tuning via grid search, feature selection, and plotting precision-recall and ROC curves. The project also includes training, testing, and making the model persistent for future use.

Data

The dataset used in this project is the Airbnb “listings” dataset. The data is preprocessed to define labels and features for the classification problem.

Tasks

	1.	Build DataFrame and Define ML Problem
	•	Load the Airbnb “listings” data set
	•	Define the label and features
	•	Create labeled examples from the data set
	•	Split the data into training and test sets
	2.	Train, Test, and Evaluate Models
	•	Train, test, and evaluate a logistic regression model using default hyperparameters
	•	Perform a grid search to identify the optimal value of C for logistic regression
	•	Train, test, and evaluate a logistic regression model using the optimal value of C
	3.	Plot Evaluation Metrics
	•	Plot a precision-recall curve for both models
	•	Plot the ROC curve and compute the AUC for both models
	4.	Perform Feature Selection
	•	Identify the most important features and refine the model
	5.	Model Persistence
	•	Save and load the model using pickle for future use

Results

	•	Precision-recall curves and ROC curves are plotted to compare model performance.
	•	The optimal hyperparameters are identified using grid search.
	•	Feature selection is performed to enhance model performance.
