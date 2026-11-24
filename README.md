# Weather Trend Forecasting

## Global Weather Analysis, Anomaly Detection, and Short-Term Temperature Forecasting

### Project Overview
This project focuses on analysing global weather patterns, identifying unusual weather observations, and developing machine learning models for short-term temperature forecasting.

The analysis uses the Global Weather Repository dataset, containing 49,111 weather observations across 210 countries and 248 locations.

### Project Objectives
- Analyse global temperature and precipitation patterns.
- Explore relationships between weather variables and air pollutants.
- Detect unusual weather observations using Isolation Forest.
- Develop and evaluate short-term temperature forecasting models.
- Compare forecasting performance using standard evaluation metrics.

### Dataset
- **Dataset:** Global Weather Repository
- **Original records:** 49,111
- **Original features:** 41
- **Geographical coverage:** 210 countries and 248 locations
- **Time period:** May 16, 2024 – January 24, 2025

### Technologies Used
- Python
- Google Colab
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Machine Learning

### Methodology
1. Data inspection and preprocessing
2. Missing and invalid value handling
3. Exploratory Data Analysis (EDA)
4. Geographical weather analysis
5. Anomaly detection using Isolation Forest
6. Time-series feature engineering
7. Temperature forecasting and model evaluation
8. Feature importance analysis
9. Weather and air quality correlation analysis

### Forecasting Models
- Persistence Baseline
- Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor
- Equal-Weight Ensemble

### Key Results

The Persistence Baseline achieved the best forecasting performance on the test dataset.

| Metric | Persistence Baseline |
|---|---:|
| MAE | 1.343°C |
| RMSE | 1.742°C |
| MAPE | 5.664% |

### Repository Contents
- `Global_Weather_Forecasting (1).ipynb` – Complete analysis, visualizations, anomaly detection, and forecasting workflow.

### How to Run
1. Download the notebook from this repository.
2. Open [Google Colab](https://colab.research.google.com/).
3. Upload the notebook.
4. Make the required dataset available in the notebook environment.
5. Run the cells in sequence.

### Project Outcome
This project demonstrates practical applications of Python, exploratory data analysis, anomaly detection, time-series forecasting, and machine learning model evaluation using real-world weather data.
