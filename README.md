# IPL-WINNING-TEAM-PREDICTION

# IPL Winning Team Prediction

Welcome to the IPL Winning Team Prediction project! This project leverages machine learning to predict the winning probabilities of IPL matches based on real-time match data. It uses Streamlit to provide an interactive web application for users to input match details and view predictions.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Acknowledgements](#acknowledgements)
- [License](#license)

# Overview

The IPL Winning Team Prediction project aims to provide real-time predictions of winning probabilities for IPL matches. Users can input match details such as the batting team, bowling team, venue, target score, current score, overs completed, and wickets lost. The model then predicts the probabilities of winning for both teams.

# Features

- Team Selection: Choose the batting and bowling teams from a list of IPL franchises.
- Venue Selection: Select the match venue from various cities where IPL matches are held.
- Match Details: Input the target score, current score, overs completed, and wickets lost.
- Prediction: Get real-time predictions of winning probabilities for both teams.

# Technologies Used

- Python: For data processing and machine learning model development.
- Pandas: For data manipulation and analysis.
- Pickle: To save and load the trained machine learning model.
- Streamlit: For creating an interactive web application that allows users to input match details and view predictions in real-time.

# Installation

To run this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/IPL-Winning-Team-Prediction.git
    cd IPL-Winning-Team-Prediction
    ```

2. Create a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

4. Ensure the pre-trained model file (`pipe.pkl`) is in the project directory. If not, you may need to train the model or obtain it from a reliable source.

# Usage

To run the Streamlit app, execute the following command in the project directory:

```bash
streamlit run ipl_win_predictor.py
