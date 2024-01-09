# phone-price-prediction-ml-kaggle-ex

# Phone Price Prediction Project

## Overview

This project focuses on building a machine learning model to predict the prices of mobile phones based on various features. The dataset used for training and evaluation is https://www.kaggle.com/datasets/berkayeserr/phone-prices.

## Table of Contents

- [Project Description](#project-description)
- [About Dataset](#dataset)
- [Requirements](#requirements)

## Project Description

### Objective

The main objective of this project is to create an accurate and reliable predictive model for estimating the prices of mobile phones. By analyzing features
### Key Features

- **Data Preprocessing**: The dataset is cleaned, and relevant features are selected for model training.
- **Machine Learning Model**: A regression algorithm (e.g., multiple linear regression, xgboost, catboost, lightgbm etc.) is employed to train the predictive model.
- **Evaluation**: The model's performance is evaluated using appropriate metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared.

## About Dataset

This dataset contains phone features including price of popular brands. Every phone in this dataset continues to be manufactured. Does not include discontinued phones.

    phone_name: name of the phone
    brand: brand of the phone
    os: operating system of the phone
    inches size of the phone screen as inches
    resolution: resolution of the phone screen
    battery: battery capacity of the phone
    battery_type: battery type of the phone
    ram(GB): ram of the phone as GB
    announcement_date: the date of the announcement of the phone
    weight(g): weight of the phone as gram
    storage(GB): storage capacity of the phone as GB
    video_720p: does phone camera has 720p feature
    video_1080p: does phone camera has 1080p feature
    video_4K: does phone camera has 4K feature
    video_8K: does phone camera has 8K feature
    video_30fps: does phone camera has 30fps feature
    video_60fps: does phone camera has 60fps feature
    video_120fps: does phone camera has 120fps feature
    video_240fps: does phone camera has 240fps feature
    video_480fps: does phone camera has 480fps feature
    video_960fps: does phone camera has 960fps feature
    price(USD): price of the phone as USD

NOTE : The purpose of this dataset is training and practice. It can never be used for commercial purposes.
Usability

### Target Variable

- Price (in currency)USD

## Requirements

- Python (>=3.6)
- Libraries (NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn, etc.)
