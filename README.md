# 🏡 Airbnb Price Predictor

This project predicts the price of Airbnb listings based on features such as location, availability, and room type using machine learning models like Linear Regression and XGBoost.

## 📌 Project Overview

The goal of this project is to build a regression model that can accurately predict the price of an Airbnb listing in Singapore based on structured data. It also demonstrates strong skills in exploratory data analysis (EDA), feature engineering, and model evaluation.

## 📂 Dataset

The dataset was obtained from [Kaggle Singapore Airbnb]((https://www.kaggle.com/datasets/jojoker/singapore-airbnb) and includes:
- `price`: Target variable (cleaned to remove symbols and converted to float)
- `neighbourhood`: The region of the listing
- `room_type`: Type of the room (e.g., Private room, Shared room)
- `availability_365`: Number of days the property is available per year

## 🔧 Technologies Used

- **Python**
- **Pandas** — for data manipulation
- **Matplotlib / Seaborn** — for data visualization
- **Scikit-learn** — for Linear Regression and evaluation
- **XGBoost** — for advanced regression modeling

## 📊 Model Building

Two models were implemented:
- **Linear Regression**: As a baseline model to understand relationships and interpret results
- **XGBoost Regressor**: To capture complex patterns and improve predictive accuracy

### Model Evaluation Metrics:
- **R² Score**: Measures the proportion of variance explained
- **RMSE (Root Mean Squared Error)**: Measures average prediction error

## 🚀 Results

- XGBoost achieved better performance than Linear Regression, indicating the presence of nonlinear patterns in the data.
- Feature importance from XGBoost highlighted `room_type` and certain neighborhoods as key drivers of price.

## 📈 Visualizations

- Price distribution plots
- Heatmaps showing feature correlations
- Actual vs Predicted price comparison

## 📁 Project Structure

