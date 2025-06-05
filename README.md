# Air-Quality Forecasting using ML Techniques

This project uses machine learning models to predict the **Air Quality Index (AQI)** based on various air pollutants like PM2.5, PM10, NO2, CO, SO2, and more. It leverages classical regression techniques to understand and estimate AQI from real-world environmental data.

---

## 📁 Dataset
The dataset used in this project is `data.csv`, which contains daily air quality data for various Indian cities. It includes pollutant concentrations and corresponding AQI values.
- **Source:** Government or public repository of air quality data (e.g., CPCB, Kaggle).
- **Features:** Date, City, AQI, PM2.5, PM10, NO2, SO2, CO, O3, Benzene, NO, NOx, NH3, Toluene, Xylene
- **Time Frame:** Yearwise data from 2015 to 2019.

---

## 🧠 Objective

- Investigate air quality trends over time using time series analysis.
- Build multiple machine learning model to predict the Air Quality Index (AQI) based on multiple air pollutant concentration levels recorded in Indian cities.
- Evaluate and visualize model performances.

---

### 📌 Preprocessing Steps:

- Select important features and split dataset for the training.
- Handled missing values using forward-fill and interpolation.
- Performed time series resampling to ensure consistent intervals.
- Applied differencing to remove trends and seasonality.
- Normalized the data for ML models using MinMaxScaler.

---

## 🚀 Getting Started

### 🧾 Prerequisites

- Python ≥ 3.7
- Jupyter Notebook
- Install required libraries:
```bash
pip install -r requirements.txt
```

---

### ⚙️ Running the Project

1. **Clone or Fork the Repository**
   - Go to the top-right corner of the GitHub repository and click `Fork`.
   - Clone it to your system:
   ```bash
   git clone https://github.com/your-username/Air-Quality-Forecasting-Using-ML-Techniques.git
   cd Air-Quality-Forecasting-Using-ML-Techniques
   ```

2. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```
3. Open `aqi_usingML.ipynb` and run the cells step-by-step to train the several ML models and generate forecasts.


---

## 🤝 Contributing

If you'd like to contribute or suggest improvements, feel free to create a pull request or open an issue.

---

## 📧 Contact

For any questions or feedback, reach out at: **divyanshisingh2885@gmail.com**

