# Weather-Based Traffic Volume Prediction

## Project Overview
This project analyzes the relationship between weather conditions and traffic volume using machine learning. The dataset includes various weather metrics and corresponding traffic measurements.

## Dataset Description
The project uses three main datasets in the Dataset directory:

### Train.csv
Training data containing:
* Holiday indicator
* Temperature
* Rainfall/Snowfall measurements
* Cloud Cover
* Weather conditions and descriptions
* Timestamp information
* Traffic volume

### Test.csv
Test dataset with similar features

### Submission.csv
Template for predictions

## Features
* **Holiday**: Binary indicator for holidays
* **Temperature**: Recorded in Kelvin
* **Rainfall_last_hour**: Precipitation amount
* **Snowfall_last_hour**: Snowfall amount
* **Cloud_Cover**: Percentage of cloud coverage
* **Weather & Weather_Desc**: Weather condition descriptions
* **TimeStamp**: Date and time of recording
* **Traffic_Vol**: Target variable - traffic volume

## Analysis
The `EDA.ipynb` notebook contains:
* Data preprocessing
* Feature engineering
* Label encoding of weather conditions
* Correlation analysis
* Data visualization