# Optimal Price Detection

## Project Overview
The "Optimal Price Detection" project is designed to assist Bilboardly, a company managing 10,000 billboards across the country. The primary goal is to determine the optimal weekly prices for renting out these billboards in order to maximize the weekly revenue. The company records data weekly, including the set daily price for each billboard and its booking ratio (the proportion of the week for which the billboard was rented out).

## Data Description
The dataset includes the following features for each billboard:
- `Billboard ID`: Unique identifier for each billboard.
- `Long` and `Lat`: Longitude and latitude coordinates of the billboard's location.
- `Light`: Indicates if the billboard is illuminated (1) or not (0).
- `Size_large`, `Size_medium`, `Size_small`: Categorical size of the billboard.
- `Week`: The week number for the data record.
- `Price`: The average daily price set for the billboard for that week.
- `Booking Ratio`: The ratio of days the billboard was booked to the total days in the week.

## Methodology
The project utilizes neural networks to predict the booking ratio based on various features. An NeuralNetwork model is considered to capture the temporal dynamics and dependencies in weekly data, which is crucial for making accurate price predictions.

## Expected Outcomes
The expected output of the project is a set of recommended prices for each billboard for the specified target week, aimed at maximizing the overall revenue.


## Table of Contents

- [Data Preparation](#1)
- [Model Training](#2)
- [Evaluation](#3)
- [Prediction](#4)

## Data Preparation
Load your data and preprocess it as required for the model. This includes scaling, normalization, and encoding categorical variables.

## Model Training
Run the training script to train the model on historical data. You can adjust parameters such as the number of epochs, learning rate, and batch size for optimization.

## Evaluation
Evaluate the model's performance on a validation set to check its accuracy in predicting booking ratios.

## Prediction
Use the trained model to predict optimal prices for the upcoming week.
