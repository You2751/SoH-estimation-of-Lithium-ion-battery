# SOH Estimation of Lithium-ion Battery

![Battery]([battery_image.jpg](https://www.canadianbatteries.com/290120-thickbox_default/37v-li-ion-5200mah-battery-fits-tp-link-tl-tr860-1924wh.jpg))

## Overview

This repository contains the code and resources for predicting the State of Health (SOH) of Lithium-ion batteries. The project utilizes regression techniques and Long Short-Term Memory (LSTM) modeling to provide accurate SOH estimates, facilitating effective battery health monitoring.

## Key Features

- **Regression Modeling:** Initial SOH prediction using regression techniques.
- **LSTM Modeling:** Advanced time-series analysis for SOH prediction using LSTM neural networks.
- **Dataset:** The dataset includes key parameters such as terminal voltage, terminal current, temperature, charge current, charge voltage, time, capacity, cycle, and SOH.

## Prerequisites

Before running the project, ensure you have the following dependencies installed:

- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Pytorch
- Scikit-Learn

## Results

The model's performance on the test set is as follows:

- **Test RMSE (Root Mean Squared Error):** 0.095
- **Test MAE (Mean Absolute Error):** 0.052

These metrics indicate that the model achieves accurate predictions of the State of Health (SOH) for Lithium-ion batteries on the test dataset. Lower values for both RMSE and MAE suggest that the model's predictions are close to the actual SOH values, showcasing its effectiveness in battery health estimation.

