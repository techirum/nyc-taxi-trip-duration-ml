# NYC Taxi Trip Duration Prediction

**Module:** IT5022 Fundamentals of Machine Learning (SLIIT)
**Task:** Supervised regression — predict taxi trip duration at pickup time.
**Algorithms:** Ridge Regression vs Random Forest Regressor

## Dataset
NYC Taxi Trip Duration (Kaggle competition, 2016 NYC TLC records):
https://www.kaggle.com/competitions/nyc-taxi-trip-duration

The data is not stored in this repo (200 MB). Download `train.zip` from the
Kaggle Data tab, extract it, and put `train.csv` in `data/raw/`.

## Setup
    python -m venv .venv
    .venv\Scripts\activate
    pip install -r requirements.txt