# Predicting-Player-Performance-Using-Feed-Forward-Neural-Networks


## Overview

This repository contains the code and resources used to train a **Feedforward Neural Network (FNN)** to predict basketball player awards based on their performance. The project uses a dataset of basketball player awards over multiple years, incorporating various performance metrics to predict the likelihood of a player winning awards like "MVP" or "Rookie of the Year."

### Dataset Used

The dataset used in this project is sourced from **Kaggle** and includes historical data of **basketball players** and their awards, including:
- **PlayerID**: Unique identifier for each player.
- **Award**: The award won by the player in a specific year (e.g., "MVP", "Rookie of the Year").
- **Year**: The year the award was given.
- **Position**: The player's position (e.g., guard, forward).
- **League**: The league in which the player participated (NBA, etc.).

Link to the dataset: [Men's Professional Basketball Dataset on Kaggle] https://www.kaggle.com/datasets/open-source-sports/mens-professional-basketball?resource=download&select=basketball_awards_players.csv

## Project Goals

The main goal of this project is to use the dataset to:
- Train a **Feedforward Neural Network (FNN)**.
- Evaluate the model’s performance on predicting player awards.
- Analyze the accuracy and loss trends to optimize the model.

## Steps Involved

1. **Data Preprocessing**: The dataset is cleaned, missing values are handled, and categorical variables are encoded.
2. **Model Development**: We build a Feedforward Neural Network using **Keras** and **TensorFlow**.
3. **Model Evaluation**: The model's performance is evaluated using accuracy and loss graphs.
4. **Results**: The performance of the model is visualized through various plots showing training and validation accuracy/loss.

## Requirements

- Python 3.x
- TensorFlow (Keras)
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

You can install the necessary libraries using the following command:

```bash
pip install -r requirements.txt
