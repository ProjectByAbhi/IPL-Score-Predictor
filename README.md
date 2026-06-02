# 🏏 IPL Score Predictor

A Machine Learning based IPL Score Predictor built using Python, Streamlit, and Scikit-Learn.

## Features

- Predicts final IPL innings score
- User-friendly Streamlit interface
- Real-time score prediction
- Uses team information, current runs, wickets, overs, and recent performance

## Input Parameters

- Batting Team
- Bowling Team
- Current Runs
- Current Overs
- Wickets Fallen
- Runs Scored in Last 5 Overs
- Wickets Lost in Last 5 Overs

## Technologies Used

- Python
- Streamlit
- NumPy
- Pandas
- Scikit-Learn

## Run Locally

```bash
pip install -r requirements.txt
python -m streamlit run ipl_score_predictor.py
```

## Project Structure

IPLScorePredictor/
│
├── ipl_score_predictor.py
├── ml_model.pkl
├── ipl_data.csv
├── requirements.txt
└── README.md

## Author

Abhishek Rai
