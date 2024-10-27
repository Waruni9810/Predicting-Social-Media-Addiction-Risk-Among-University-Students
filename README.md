# Predicting Social Media Addiction Risk Among University Students

## Overview
This project uses machine learning techniques to predict social media addiction risk among university students based on behavioral, emotional, and demographic data. By identifying students at risk, educational institutions can proactively support mental health initiatives.

The project was developed using Python, with data preprocessing, feature engineering, model training, and evaluation conducted in a Google Colab notebook. The final Logistic Regression model was selected for its balance of accuracy and interpretability, and it has been deployed for real-time predictions using FastAPI on Heroku.

## Project Structure
- **notebooks/**: Contains the main Google Colab notebook with data processing, modeling, and visualizations.
- **model/**: Stores the trained Logistic Regression model (`social_media_addiction_model.pkl`).
- **data/**: Placeholder for the original and processed datasets.

## Dataset
The dataset was sourced from Kaggle and includes the following key features:
- **Demographics**: Age, gender
- **Behavioral Metrics**: Daily usage time, posts per day, likes and comments received, messages sent
- **Emotional Engagement**: Happiness, anxiety, sadness

### Data Processing
1. **Data Cleaning**: Handling missing values, outliers, and incorrect entries.
2. **Feature Engineering**: Encoding categorical variables, normalizing numerical features.
3. **Exploratory Data Analysis (EDA)**: Visualizations including histograms, box plots, and correlation heatmaps to identify relationships and key predictors.

## Model Selection
Various machine learning models were evaluated, including:
- **Logistic Regression**: Selected for deployment due to high accuracy and interpretability.
- **Random Forest**
- **Gradient Boosting**
- **Support Vector Machine (SVM)**

The Logistic Regression model achieved a test accuracy of 0.98. Feature importance analysis identified daily usage time, posts per day, and specific emotional states as significant predictors of addiction risk.
