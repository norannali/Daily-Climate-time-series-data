# 📊 Daily Climate Time Series Data – Delhi (2013–2017)

## 📘 Description

This dataset contains **daily climate records** from **Delhi, India**, collected over a period of approximately **4 years (January 1, 2013 – April 24, 2017)**. It is ideal for **weather forecasting, time series analysis, and climate modeling**, particularly focused on the Indian subcontinent.

The data was originally gathered as part of an assignment for the **Data Analytics Course at PES University, Bangalore**, and sourced via the **Weather Underground API**.

---

## 📦 Features

The dataset includes the following **four key weather parameters**:

| Column Name     | Description                         |
|-----------------|-------------------------------------|
| `meantemp`      | Mean temperature in Celsius          |
| `humidity`      | Humidity in percentage               |
| `wind_speed`    | Wind speed in km/h                   |
| `meanpressure`  | Mean atmospheric pressure in millibars |

All values are recorded **daily**, making this a suitable dataset for time-series forecasting tasks.

---


---

## 🔍 Sample Data Preview

| date       | meantemp | humidity | wind_speed | meanpressure |
|------------|----------|----------|------------|--------------|
| 2013-01-01 | 21.0     | 58.0     | 11.0       | 1013.0       |
| 2013-01-02 | 20.5     | 62.0     | 9.0        | 1014.0       |
| 2013-01-03 | 20.0     | 65.0     | 8.0        | 1015.0       |

---

## 🛠️ Use Cases

- Weather forecasting using **time series models** (e.g., ARIMA, SARIMA, LSTM)
- Exploratory Data Analysis (EDA) of climate trends
- Regression modeling to predict future temperature or pressure
- Seasonal pattern detection and anomaly detection
- Educational purposes in machine learning and data science courses

---

## 📚 Acknowledgements

- Dataset Source: [Kaggle - Daily Climate Data](https://www.kaggle.com/datasets/sumanthvrao/daily-climate-time-series-data) 
- API Source: [Weather Underground API](https://www.wunderground.com/weather/api)  (archived)

---

## 🧪 How to Use

### Requirements:
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook or any IDE (VS Code, Colab, etc.)

### Load the Data:

```python
import pandas as pd
df = pd.read_csv("delhi_weather.csv")
df.head()
