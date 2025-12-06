# Fitness-Tracker-Project-Group12

## Daily Calorie Burn Prediction

This project builds a machine learning model to predict end-of-day calorie burn early in the day using wearable activity data such as steps, heart rate, sleep duration, hydration, temperature, and user habits.
The goal is to help provide real-time recommendations to users who may fall short of their daily activity targets.

## Project Overview

Many users check their activity progress only late in the day — often after it’s too late to take meaningful action.

This project solves that by:

* Using early-day activity data to estimate daily calorie burn
* Identifying whether a user is on track or at risk
* Enabling the app to send actionable nudges such as:
  “You may need ~20 more minutes of walking to meet your daily goal.”

## Objectives

* Build a supervised regression model for calorie prediction
* Compare linear and non-linear models (Linear Regression, Random Forest Regressor, Gradient Boosting Model)
* Avoid any form of participant-level data leakage

## Dataset

https://www.kaggle.com/datasets/jijagallery/fitlife-health-and-fitness-tracking-dataset

## Modeling Approach

* Preprocessing
* Train/Test Split
* Model Performance Comparison

| Model               | MAE   | RMSE  | R²     |
|---------------------|-------|--------|--------|
| Linear Regression   | 2.31  | 11.08  | 0.889  |
| Random Forest       | **0.25** | **0.47** | **0.998** |
| Gradient Boosting   | 0.35  | 0.47   | 0.998  |


Random Forest delivered the best average performance and is selected as the final model.
