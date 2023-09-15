# Overview
This repository contains the dataset which deals with cancellations at the hotel/resort. This was used for a machine learning project in R. The project aimed to build a Shiny web application for exploring and visualizing the data. This README file provides an overview of the dataset, the machine learning process, and the Shiny app.

## Dataset Description
Dataset Name: Resort01
File: Resort01.csv
Description: The Resort01 dataset contains information about a fictional resort. It includes various features such as customer demographics, resort amenities, booking details, and customer satisfaction ratings.

## Machine Learning Process
### Data Preprocessing
  1. Data Loading: The dataset was loaded into R using the read.csv() function.
  2. Data Cleaning: Data cleaning involved handling missing values, removing duplicates, and ensuring data consistency.
  3. Feature Engineering: New features were created as needed to enhance model performance.

### Exploratory Data Analysis (EDA)
Exploratory data analysis was conducted to understand the dataset's characteristics, identify patterns, and gain insights into customer behavior.

## Model Building
Machine learning models were developed to predict customer satisfaction based on the provided features. Common libraries like caret, randomForest, and svm were used to build and evaluate the models.

## Model Evaluation
Model performance was assessed using various metrics, such as accuracy, precision, recall, and F1-score. Cross-validation and hyperparameter tuning were employed to optimize the models.

## Shiny App
A Shiny web application was developed to showcase the results of the machine learning models and allow users to interact with the data.

## App Features
 1. Visualization: Users can explore interactive visualizations of customer satisfaction trends and demographic distributions.
 2. Prediction: The app provides the ability to make real-time predictions of customer satisfaction based on user input.
 3. Insights: Additional insights and recommendations derived from the models are presented to users.
