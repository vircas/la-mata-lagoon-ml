# Machine Learning for Environmental Monitoring and Historical Reconstruction of La Mata Lagoon

This repository contains the full data processing pipeline, exploratory analysis, forecasting experiments, and historical reconstruction developed for the study of **La Mata Lagoon** (Alicante, Spain).  
The project integrates IoT sensor data, time-series analytics, and machine learning models to understand lagoon dynamics and reconstruct historical temperature records.

## Repository Structure

```
LA-MATA-LAGOON-ML/
│
├── data_analysis/
│   ├── data_preprocessing.ipynb
│   ├── lagoon_data_overview.ipynb
│   └── time_series_analysis.ipynb
│
├── data_loading/
│   ├── load_historical_data.ipynb
│   └── load_lagoon_data.ipynb
│
├── future_predictive_modeling/
│   ├── experiment_1/
│   │   ├── experiment_1.ipynb
│   │   ├── auto_arima_diagnostics.ipynb
│   │   └── results_exp_1.xlsx
│   ├── experiment_2/
│   │   ├── experiment_2.ipynb
│   │   └── results_exp_2.xlsx
│   ├── experiment_3/
│   │   ├── experiment_3.ipynb
│   │   ├── results_exp_3.xlsx
│   │   └── air_temp_and_level/
│   │       ├── auto_arima_diagnostics_air_temp.ipynb
│   │       ├── auto_arima_diagnostics_level.ipynb
│   │       ├── experiment_1_air_temp.ipynb
│   │       └── experiment_1_level.ipynb
│   ├── experiment_4/
│   │   └── experiment_4.ipynb
│   └── experiment_5/
│       └── experiment_5.ipynb
│
├── historical_reconstruction/
│   └── historical_reconstruction.ipynb
│
└── data/
    ├── preprocessed/
    │   ├── historical_air_temp.csv
    │   └── lagoon_hourly_filled.csv
    └── raw/
        ├── air_temp_*.csv
        ├── bottom_*.csv
        ├── surface_*.csv
        ├── lagoon_level.csv
        ├── lagoon_level-data-20_07_2023-11_04_02.csv
        ├── lagoon_historical_temperature_complete.csv
        └── other IoT and historical files
```

## Reproducibility Guide

### Clone the repository
```
git clone https://github.com/vircas/la-mata-lagoon-ml.git
cd la-mata-lagoon-ml
```

### Requirements
- python >= 3.10
- pandas
- numpy
- matplotlib
- scikit-learn
- statsmodels
- pmdarima

### Notebook execution order
1. data_loading  
2. data_analysis  
3. future_predictive_modeling  
4. historical_reconstruction

## Citation

```
Sánchez V.C., González M., López-Espín J.J., Calafate C.T., Cecilia J.M.
Machine Learning-Based Environmental Monitoring and Historical Reconstruction
of a Protected Mediterranean Lagoon (2025).
```

## Contact
For questions or collaboration, please reach out to the study authors.
