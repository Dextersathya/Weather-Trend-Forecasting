# 🌦️ Weather Data Analysis & Forecasting

This project involves data cleaning, exploratory data analysis (EDA), visualization, and time series forecasting on weather data. The dataset used is **GlobalWeatherRepository.csv**.

---

## 📌 Project Overview

- **Data Cleaning & Preprocessing**: Handling missing values and outliers.
- **Exploratory Data Analysis (EDA)**: Understanding distributions, correlations, and trends.
- **Feature Engineering**: Scaling and transformation of numerical features.
- **Modeling**:
  - Regression models (Random Forest, Linear Regression, Decision Trees, Gradient Boosting)
  - Time series forecasting using **Facebook Prophet**
- **Visualization**:
  - Distribution plots, correlation heatmaps, time series trends.

---

## 📂 Dataset

- **GlobalWeatherRepository.csv**
- Contains weather attributes like temperature, humidity, wind speed, precipitation, and air quality.
- **Key features**:
  - `temperature_celsius`
  - `humidity`
  - `wind_kph`
  - `precip_mm`
  - `air_quality_Ozone`
  - `last_updated` (timestamp for time-series analysis)

---

## 📊 Data Analysis & Visualizations

### 🔹 Correlation Heatmap
![Heatmap](path/to/your/image.png)

### 🔹 Temperature Trends Over Time
![Temperature Trend](path/to/your/image.png)

---
# Weather Data Prediction

This project predicts weather parameters such as temperature, humidity, and air quality using machine learning models. 

## 📊 Model Performance on Fake Data  
To evaluate model robustness, we generated **100 synthetic weather records** using the `Faker` library and tested the models on this dataset.

| Model | MAE | RMSE | R² Score |
|--------|-------|-------|---------|
| Random Forest Regressor | `0.2716` | `0.2370` | `0.9972` |
| Linear Regression | `0.9081` | `1.2757` | `0.9824` |
| Decision Tree Regressor | `0.4969` | `0.7206` | `0.9944` |
| Gradient Boosting | `1.0522` | `1.4291` | `0.9780` |

📌 **Note:** The values above are derived from `model_performance_fake_data.csv`.

## 🛠️ How to Run  
1. Install dependencies:  
   ```bash
   pip install -r requirements.txt


## 🔮 Time Series Forecasting

Using **Facebook Prophet**, the model forecasts temperature trends for the next 30 days.

**Example Forecast Plot:**
![Forecast Plot](path/to/your/image.png)

---

## 🛠️ Installation & Usage

1️⃣ Clone the repository:
```sh
git clone https://github.com/Dextersathya/Your-Repo-Name.git
