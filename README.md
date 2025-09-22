# MADRID WEATHER FORECASTING PROJECT (1997-2025)
This project uses historical weather data to predict the **Mean Temperature (°C)** using a **Random Forest Regressor**.

---

## Project Overview

The goal is to build a machine learning model that can accurately predict the mean daily temperature based on various weather related features such as:

- Humidity
- Dew Point
- Wind Speed
- Visibility
- Atmospheric Pressure
- Cloud Cover
- and more...

---

## Files Included

- `temperature_prediction.ipynb`: Main Jupyter Notebook containing all the code and analysis.
- `weather_data.csv` *(or your actual file name)*: Dataset used for training the model.
- `README.md`: This file.

---

## Steps Performed

1. **Data Loading**
2. **Exploratory Data Analysis (EDA)**  
   - Summary stats  
   - Correlation heatmap  
   - Distribution plots
3. **Data Preprocessing**  
   - Missing value handling  
   - Feature selection
4. **Model Building**  
   - Train/test split  
   - Random Forest Regressor in a pipeline with scaling
5. **Model Evaluation**  
   - MAE: **0.37°C**  
   - R² Score: **0.993**
6. **Prediction on New Data**

---

##  Model Performance

- **Mean Absolute Error (MAE):** 0.37°C  
- **R² Score:** 0.993  
This shows the model is very accurate in predicting mean temperatures based on the given weather features.

---

## Future Improvements

- Test with more models (e.g., Gradient Boosting, XGBoost)
- Add time series modeling
- Deploy with a dashboard or API
- Perform feature importance analysis

---

## How to Run

1. Clone this repo or download the notebook.
2. Make sure you have the required libraries:
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```
3. Run the notebook in Jupyter or VS Code.

---

## Contact

Feel free to connect or message me if you have feedback or questions!

