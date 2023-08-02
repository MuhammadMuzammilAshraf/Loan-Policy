# Loan Status Prediction
This repository contains code and data for a Data Science project that aims to predict the loan status of applicants based on various attributes. The dataset used in this project is provided in the data.csv file.
## Project Structure
The project is organized as follows:
data.csv: The dataset containing information about loan applicants and their loan status.
loan policy.ipynb: Jupyter Notebook containing the entire Data Science pipeline, from data loading to model evaluation.
Decision Tree _model.sav: Saved Decision Tree model obtained from training on the dataset.
Knn Tree _model.sav: Saved K-nearest neighbors (KNN) model obtained from training on the dataset.
Naive Bayes Tree _model.sav: Saved Gaussian Naive Bayes model obtained from training on the dataset.
Data Analysis and Preprocessing
The main.ipynb notebook starts with data analysis and preprocessing. It includes steps like handling missing values, removing irrelevant columns, and detecting and removing outliers.

## Exploratory Data Analysis
The EDA section in the notebook involves visualizations to understand the distribution of different attributes and their relationships with the target variable, loan status.

## Feature Engineering
After preprocessing and EDA, the notebook applies feature engineering techniques to prepare the data for modeling. This includes encoding categorical variables using one-hot encoding and label encoding.

## Model Training
Three different classifiers are used for the loan status prediction:

Decision Tree Classifier
K-nearest neighbors (KNN) Classifier
Gaussian Naive Bayes Classifier
Each model is trained and evaluated using appropriate metrics.

## Model Evaluation and Saving
The models are evaluated on a test set, and their performance metrics (e.g., accuracy) are displayed. The trained models are then saved as pickled files for later use.

Conclusion
This project demonstrates how to use various Data Science techniques to predict loan status based on applicant attributes. Feel free to explore the code, modify the models, and experiment with different features to improve the prediction performance.

For any questions or feedback, please don't hesitate to contact the project owner.
