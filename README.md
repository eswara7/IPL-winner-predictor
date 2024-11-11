# 🏏 IPL Winner Predictor

The **IPL Winner Predictor** is a machine learning application designed to predict the probability of a particular IPL team winning a match. By using data-driven analysis and machine learning, this app provides cricket enthusiasts, analysts, and bettors with a tool to make informed decisions about match outcomes.

## 📊 Project Overview

The goal of the **IPL Winner Predictor** is to predict the likelihood of an IPL team winning a match based on various match parameters, such as:

- Batting team
- Bowling team
- Host city
- Current score and target
- Number of overs completed
- Number of wickets lost

The app leverages historical data to create a model that estimates the probability of a team winning given the current match conditions.

### How It Works:

- **Input Parameters**: Users can input the batting team, bowling team, host city, target score, current score, overs completed, and wickets lost.
- **Prediction**: The model predicts the probability of each team winning based on these inputs and historical data.
- **Output**: The app displays the probability of the batting team and the bowling team winning.

## 🛠️ Tools and Libraries Used

- **Streamlit**: For creating the interactive web interface where users can input match data and receive predictions.
- **scikit-learn**: Used for building the machine learning model to predict match outcomes.
- **pandas**: Data manipulation and handling of match parameters.
- **pickle**: For saving and loading the trained model.
- **numpy**: Used for numerical operations in the data processing.

## 🚀 How It Works

1. **Collect Data**: Historical match data is collected, including match parameters (batting team, bowling team, city, etc.).
2. **Model Training**: A machine learning model is trained using the historical match data to predict the probability of a team winning.
3. **User Input**: The user provides current match details (such as score, overs, wickets, etc.) through a Streamlit interface.
4. **Prediction**: The model calculates the likelihood of each team winning and displays the results on the interface.

## 📝 Features

- **Team Selection**: Users can select the batting team and bowling team from a predefined list of IPL teams.
- **Match Parameters**: Users can input match parameters like the target score, current score, overs completed, and wickets fallen.
- **Prediction Results**: The app provides the probability of each team winning based on the provided inputs.
- **Interactive Interface**: The web interface allows users to interact with the model easily.
