# Wind Generation Forecasting Based on Meteorological Information 🌬️⚡

A machine learning project in R for predicting wind power generation using meteorological data, achieving superior accuracy compared to basic time series models.

## Table of Contents

* [Project Overview](#project-overview)
* [Dataset](#dataset)
* [Features](#features)
* [Installation](#installation)
* [Usage](#usage)
* [Models](#models)
* [Results](#results)
* [Future Work](#future-work)
* [License](#license)

## Project Overview

This project develops a machine learning model for forecasting wind power generation based on meteorological inputs. By handling non-stationary data and adapting quickly to different wind farms, the model provides reliable 48-hour forecasts with higher accuracy than traditional persistence models.

Key components include:

* Forecasting wind power generation using meteorological data.
* Handling non-stationarity in time series data.
* Deploying a hybrid model combining BCD classifier and SVR network for accurate predictions.

## Dataset

* Meteorological data from wind farms including wind speed, direction, temperature, and other relevant parameters.
* Historical wind power generation data for supervised training.
* Preprocessed to handle missing values and normalized for modeling.

## Features

* **Wind Power Forecasting:** Predicts generation over 48-hour periods.
* **Non-Stationarity Handling:** Models account for changes in wind patterns.
* **Hybrid Model:** Combines BCD classifier for classification tasks and SVR for regression tasks.
* **Adaptable to Multiple Sites:** Can quickly modify input data for different wind farms.

## Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/wind-forecasting.git
cd wind-forecasting

# Install required R packages
install.packages(c("e1071", "caret", "ggplot2"))
```

## Usage

1. Load the dataset in R.
2. Run the forecasting script:

```R
source("wind_forecasting.R")
```

3. Model outputs wind power predictions for the next 48 hours.
4. Visualizations of predicted vs actual generation are generated automatically.

## Models

* **BCD Classifier:** Handles classification of non-stationary patterns in wind data.
* **SVR Network (Support Vector Regression):** Provides precise regression-based predictions for wind power.
* Hybrid approach improves accuracy over basic time series and persistence models.

## Results

* Achieved higher accuracy than persistence models for 48-hour forecasts.
* Model adapts quickly to different wind farm data.
* Predictions improve in accuracy over longer forecast durations.

## Future Work

* Extend forecasting to longer time horizons.
* Integrate additional meteorological variables for better performance.
* Deploy as a real-time forecasting system for operational wind farms.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

Do you want me to do that?
