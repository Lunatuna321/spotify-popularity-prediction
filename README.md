# Spotify Popularity Prediction

This project explores Spotify audio features and uses machine learning
models to predict track popularity.

## Dataset

The dataset contains Spotify tracks and audio features such as:

- danceability
- energy
- loudness
- acousticness
- tempo
- valence

## Project Goals

- Explore relationships between audio features and popularity
- Analyze popularity trends across genres
- Train a machine learning model to predict popularity
- Identify the most important audio features

## Genre Popularity Analysis

![Genre Popularity](images/top_genres_popularity.png)

## Feature Importance

![Feature Importance](images/feature_importance.png)

## Correlation Heatmap

![Correlation Heatmap](images/correlation_heatmap.png)

## Machine Learning Model

A Random Forest Regressor was trained using Spotify audio features
to predict track popularity.

### Model Performance

- Mean Absolute Error (MAE): 15.37
- R² Score: 0.125

## Key Insights

- Loudness and energy were among the most important predictive features
- Popularity showed weak correlations with individual audio features
- Song popularity is influenced by many external factors beyond audio features alone

## Tools Used

- Python
- pandas
- matplotlib
- seaborn
- scikit-learn
- Jupyter Notebook