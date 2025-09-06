# IPL player price predictor

## Project Overview
The IPL PLayer Price Predictor is a machine learning project designed to estimate the likely auction price of an IPL player based on their overall performances, previous prices, current form, profile, and playing conditions.

Every year, IPL franchises compete fiercely in auctions, bidding for players whose value is influenced by skillset, form, team balance, and market demand. This project combines historical auction data and player performance statistics to build predictive models that can simulate what price a player might fetch in an auction

## Features
- Collects & processes IPL player and auction data
- Feature engineering (batting, bowling, venues, form, overseas/home, consistency)
- Machine learning modeling (Linear Regression, Random Forest, XGBoost)
- Model evaluation with metrics like RMSE and MAE
- Deployment as an interactive Streamlit app where users can test hypothetical player profiles
- backtesting to evaluate models and improve

## Objectives
- Predict likely auction orice of IPL players based on their stats and role
- Identify which features (eg batting strike rate, wickets, international experience, venue performance) most influence price
- Provide a user-friendly tool for cricket fans, analysts or aspiring franchise strategists to explore hypothetical player valuations

## Tech Stack
- Python, Pandas, Scikit-learn
- XGBoost/LightGBM
- PuLP / OR-Tools
- Streamlit for deployment


