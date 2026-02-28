README.md

# Waiter Tip Prediction Using Linear Regression

## Project Overview

This project predicts the tip amount given to a waiter using a Linear Regression model. The model analyzes customer and transaction details to estimate how much tip is likely to be given. The goal is to understand tipping behavior and build a reliable regression model for prediction.

## Dataset Description

### Input Features

* Total Bill. Total bill amount in dollars.
* Sex. Gender of the customer.
* Smoker. Smoking status of the customer.
* Day. Day of the week.
* Time. Lunch or Dinner.
* Size. Number of people at the table.

### Target Variable

* Tip. Tip amount in dollars.

## Tech Stack

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Project Workflow

1. Data loading and initial exploration.
2. Handling categorical variables using encoding.
3. Splitting dataset into training and testing sets.
4. Training Linear Regression model.
5. Evaluating model using Mean Squared Error and R squared score.

## Model Evaluation Metrics

* Mean Squared Error
* R squared Score

## Results

The model estimates the tip amount based on given inputs and provides insights into how total bill, group size, and other customer attributes affect tipping behavior.

## How to Run

1. Clone this repository.
2. Install dependencies from requirements.txt.
3. Open the Jupyter Notebook file.
4. Run all cells to train and evaluate the model.

scikit-learn
jupyter
