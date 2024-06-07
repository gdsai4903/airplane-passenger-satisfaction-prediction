# Airline Passenger Satisfaction Analysis

This repository contains an analysis of an airline passenger satisfaction survey dataset. The goal of this project is to identify factors that are highly correlated with passenger satisfaction and to build predictive models to classify passenger satisfaction.

## Table of Contents
- [Project Description](#project-description)
- [Dataset](#dataset)
- [Data Cleaning](#data-cleaning)
- [Model Selection](#model-selection)
- [Results](#results)

## Project Description
The dataset contains survey responses from airline passengers. The objective of the project is to analyze the data to determine the factors contributing to passenger satisfaction and to predict whether a passenger is satisfied based on these factors. This analysis includes data cleaning, exploratory data analysis (EDA), feature engineering, and building machine learning models.

## Dataset
The dataset used in this project contains various features related to passenger demographics, flight details, and satisfaction levels. Here are the features included in the dataset:

- **Gender**: Gender of the passengers (Female, Male)
- **Customer Type**: The customer type (Loyal customer, disloyal customer)
- **Age**: The actual age of the passengers
- **Type of Travel**: Purpose of the flight (Personal Travel, Business Travel)
- **Class**: Travel class (Business, Eco, Eco Plus)
- **Flight distance**: The flight distance of this journey
- **Inflight wifi service**: Satisfaction level (0:Not Applicable; 1-5)
- **Departure/Arrival time convenient**: Satisfaction level
- **Ease of Online booking**: Satisfaction level
- **Gate location**: Satisfaction level
- **Food and drink**: Satisfaction level
- **Online boarding**: Satisfaction level
- **Seat comfort**: Satisfaction level
- **Inflight entertainment**: Satisfaction level
- **On-board service**: Satisfaction level
- **Leg room service**: Satisfaction level
- **Baggage handling**: Satisfaction level
- **Check-in service**: Satisfaction level
- **Inflight service**: Satisfaction level
- **Cleanliness**: Satisfaction level
- **Departure Delay in Minutes**: Minutes delayed at departure
- **Arrival Delay in Minutes**: Minutes delayed at arrival
- **Satisfaction**: Airline satisfaction level (Satisfied, neutral or dissatisfied)

## Data Cleaning
The data cleaning process includes handling missing values, encoding categorical variables, and normalizing numerical features. Detailed steps can be found in the `data_cleaning.ipynb` notebook.

## Model Selection
Two machine learning models were evaluated to predict passenger satisfaction:
- **Decision Tree Classifier**
- **Support Vector Machine (SVM)**

The model selection process, including hyperparameter tuning and evaluation metrics, is documented in the `model_selection.ipynb` notebook.

## Results
The results of the analysis, including model performance metrics such as accuracy, precision, recall, and F1-score, are summarized in the `model_melection.ipynb` notebook. Visualizations and comparisons of the models' performance are also provided.
