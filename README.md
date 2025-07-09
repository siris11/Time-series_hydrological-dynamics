# SHAP Analysis for Streamflow Prediction

This project explains how different hydrological features influence LSTM-based streamflow predictions using SHAP (SHapley Additive exPlanations).

##  Objective

To interpret the predictions made by a trained LSTM model using SHAP values and understand how feature importance changes **before and after a detected change point**.

##  Methods Used

- **SHAP**: Model explainability for time series
- **Sequential Mann-Kendall (SMK)**: Detect trend shifts in streamflow
- **CAMELS Dataset**: Catchment attributes and streamflow records

##  Key Insight

Used SHAP to reveal how the importance of features like **precipitation, temperature, and Land use land cover** changes across time and climate events.

