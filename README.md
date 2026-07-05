# IPL Win Predictor

This project is a Streamlit web app that predicts the probability of an IPL team winning a match based on live match conditions such as batting team, bowling team, host city, target score, current score, overs completed, and wickets lost.

## Project Overview

The app uses a trained machine learning model stored in `pipe.pkl` and provides real-time win/loss probability predictions for a cricket match scenario.

## Features

- Select batting and bowling teams
- Choose the host city
- Enter target score, current score, overs completed, and wickets
- Predict win probability for both teams instantly

## Project Structure

- `app.py` - Streamlit application
- `pipe.pkl` - Trained prediction model
- `Week3_project.ipynb` - Notebook used for analysis and model development
- `dataset/` - IPL match and delivery datasets used in the project

## Installation

1. Clone the repository
2. Create and activate a virtual environment (optional but recommended)
3. Install the required dependencies:

```bash
pip install streamlit pandas scikit-learn
```

## Run the App

```bash
streamlit run app.py
```

Then open the local URL shown in the terminal in your browser.

## Usage

1. Select the batting team and bowling team
2. Choose the host city
3. Enter the target score, current score, overs completed, and wickets
4. Click the Predict Probability button to view the predicted win/loss percentages

## Dataset

The project uses IPL match-related datasets from the `dataset/` folder, including information about matches, deliveries, and teams.

## License

This project is for educational and demonstration purposes.
