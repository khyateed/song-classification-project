# Project 3: Multi-Classification
### Authors: Khyatee Desai and David Shin

![img](./images/banner.jpg)

## Overview

Spotify is always looking to create additional features and playlists to have users discover new artists from different genres and era's. 

## Business Problem

To develop the best features and playlists, we need to understand which features are most important in classifying music. determining unemployment during a time of financial crisis. Once we understand which features are important, we can primarily monitor areas with the highest probability of showing employment loss, saving time and money.

## Data

We utilized a Kaggle Dataset that has Spotify music data from 1921-2020
*  https://www.kaggle.com/yamaerenay/spotify-dataset-19212020-160k-tracks

## Method

### Feature Engineering

We generated new features with feature interaction, natural logs, dummy variables, and polynomials.

### Models

* Logistic

## Results

## Conclusions

The clearest predictors of era classification were popularity, duration, loudness, and acousticness. Because popularity isn't a reliable music attribute, future models would likely leave it out

## Further Research

This project is a first step into developing insights about song attributes. We can utilize this knowledge to further develop classifications and beginning to Other application is to use the insights from this project about song attributes as a launching point into unsupervised learning, for example clustering songs to make a recommendation engine 

## Navigation
├── README.md
├── images
│   ├── banner.jpg
│   ├── variables.png
│   ├── 
│   ├── ge 
│   ├── 
├── datasets
│   ├── datasets.zip
└── pickled
│   ├── grid_forest_model.pickle
│   ├── rfe_features.pickle
│   ├── xgboost_model.pickle
└── modeling_process.ipynb
