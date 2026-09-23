# Electric Vehicle Specification Analysis and Range Prediction using Machine Learning

## AIS Solution – AI Internship Project

## Project Overview

This project focuses on analyzing Electric Vehicle (EV) specifications and developing Machine Learning models to predict the driving range of electric vehicles.

The project follows an end-to-end Data Analysis and Machine Learning workflow, including data cleaning, exploratory data analysis, visualization, outlier detection, feature engineering, model training, evaluation, and prediction.

## Objective

The main objective is to analyze different EV specifications and use Machine Learning techniques to predict the driving range of an electric vehicle.

### Target Variable

`range_km`

## Dataset

The dataset contains specifications of **478 electric vehicles** with **22 columns**.

Important features include:

- Battery Capacity
- Number of Cells
- Torque
- Energy Efficiency
- Top Speed
- Acceleration
- Fast Charging Power
- Towing Capacity
- Seats
- Vehicle Dimensions
- Drivetrain
- Battery Type
- Vehicle Segment
- Car Body Type

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy
- Jupyter Notebook
- GitHub

## Project Workflow

### 1. Data Loading
- Loaded the EV dataset using Pandas.
- Examined dataset shape and structure.
- Displayed first and last records.

### 2. Data Cleaning
- Checked data types.
- Checked missing values.
- Checked duplicate records.
- Removed duplicate rows.
- Handled missing numerical values using the median.
- Handled missing categorical values using the mode.

### 3. Exploratory Data Analysis

Performed analysis of:

- EV brands
- Battery types
- Drivetrain types
- Car body types
- Vehicle segments
- Driving range

### 4. Data Visualization

Created:

- Histograms
- Bar charts
- Scatter plots
- Boxplots
- Correlation heatmap

### 5. Correlation Analysis

Analyzed the correlation between numerical EV specifications and driving range.

### 6. Outlier Detection

Two methods were used:

- IQR / Tukey Method
- Z-Score Method

Box-and-whisker plots were also used to visually identify potential outliers.

### 7. Feature Engineering

Created additional features:


### 8. Machine Learning

The dataset was divided using an **80:20 train-test split**.

Two regression models were trained:

1. Linear Regression
2. Random Forest Regression

### 9. Model Evaluation

Models were evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

### 10. Feature Importance

Random Forest feature importance was used to analyze which EV specifications contributed most to range prediction.

### 11. New EV Prediction

The trained Random Forest model was also used to predict the driving range of a hypothetical new electric vehicle.
