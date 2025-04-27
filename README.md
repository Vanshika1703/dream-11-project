# dream-11-project
AI-driven fantasy points prediction for Dream11 players — enhancing fantasy team strategy!
# Dream11 Fantasy Points Prediction

## Overview
This project was developed as part of the Dream11 Gamethon event.  
The goal was to build Machine Learning models capable of predicting fantasy points for players based on pre-match data (before toss) and match-time data (after toss).

## Problem Statement
Fantasy sports apps like Dream11 require accurate predictions of player performance to enhance user engagement and improve team-building strategies.  
We aimed to predict the fantasy points for each player, using historical data and various match-specific features.

## Notebooks
- **Dream_11_Final_Model_Training_and_Prediction.ipynb**: Predicts fantasy points considering toss and match updates.
- **Dream_11_(Pre_Toss)_Final_Model_Training_and_Prediction.ipynb**: Predicts fantasy points *before the toss* based only on initial match information.

## Features
- Data preprocessing and feature engineering on player and match data.
- Model training using Machine Learning algorithms.
- Evaluation metrics for model accuracy.
- Separate models for Pre-Toss and Post-Toss scenarios.
- Fantasy point prediction based on player attributes and match conditions.

## Tech Stack
- Python
- Jupyter Notebook
- Pandas
- Scikit-learn
- XGBoost
- Matplotlib / Seaborn (for visualization)

## Installation
```bash
git clone https://github.com/your-username/dream11-fantasy-points-prediction.git
cd dream11-fantasy-points-prediction
pip install -r requirements.txt
