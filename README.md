# Taxi-Ride-Price-Prediction
# 🚖 Taxi Ride Price Prediction

This machine learning project predicts the final fare of a taxi ride based on features like distance, time, traffic, and weather. It uses regression models to estimate the price accurately.

## 📁 Dataset Features
- `Trip_Distance_km`
- `Time_of_Day` (Morning, Afternoon, Night)
- `Day_of_Week`
- `Passenger_Count`
- `Traffic_Conditions` (Low, Medium, High)
- `Weather` (Clear, Rainy, Foggy)
- `Base_Fare`
- `Per_Km_Rate`
- `Per_Minute_Rate`
- `Trip_Duration_Minutes`

## 📊 Algorithms Used
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

## 📈 Evaluation Metrics
- R² Score
- Mean Squared Error (MSE)

## 🏁 Final Result
The **Random Forest Regressor** gave the best performance with:
- R² Score: **0.96**
- MSE: **46.84**

## 🔧 Tools Used
- Python, Pandas, Scikit-learn, Matplotlib, Seaborn
