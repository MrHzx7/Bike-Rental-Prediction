# Bike-Rental-Prediction
End-to-end bike rental prediction project featuring EDA, preprocessing, and Random Forest modeling.
# 🚲 Bike Rental Prediction

This project aims to predict daily bike rental counts based on environmental and seasonal features using the `day.csv` dataset. This dataset was part of a bike-sharing system study, where rentals were automatically tracked.

## 📌 Objective
To build a machine learning model that accurately forecasts bike rental counts (`cnt`) using environmental and temporal data.

---

## 📊 Dataset Overview

| Feature       | Description                                                  |
|---------------|--------------------------------------------------------------|
| dteday        | Date of record                                               |
| season        | Season (1:spring, 2:summer, 3:fall, 4:winter)                |
| yr            | Year (0:2011, 1:2012)                                        |
| mnth          | Month (1 to 12)                                              |
| holiday       | Is the day a holiday?                                        |
| weekday       | Day of the week                                              |
| workingday    | Is the day a working day?                                    |
| weathersit    | Weather situation (1 to 4)                                   |
| temp          | Normalized temperature                                       |
| atemp         | Normalized "feels like" temperature                          |
| hum           | Normalized humidity                                          |
| windspeed     | Normalized windspeed                                         |
| casual        | Count of casual users                                        |
| registered    | Count of registered users                                    |
| cnt           | Total count of bike rentals                                  |

---

## 🔍 Steps Performed

1. **Exploratory Data Analysis (EDA)**
   - Data cleaning and missing value analysis
   - Data type conversions
   - Visualizations (monthly, yearly trends, outliers)

2. **Data Preprocessing**
   - Feature selection
   - Train-test split

3. **Model Building**
   - Used Random Forest Regressor for prediction
   - Evaluated using RMSE and R²

4. **Results & Insights**
   - The model showed strong performance with minimal overfitting.
   - Environmental factors (temp, humidity) strongly influence rentals.

---

## 📈 Sample Visualizations
*(Add plots from your notebook here)*

---

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---

## 📁 How to Run
1. Clone the repo
```bash
git clone https://github.com/your-username/bike-rental-prediction.git
cd bike-rental-prediction
