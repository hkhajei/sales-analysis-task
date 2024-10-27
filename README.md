# Sales Forecasting Project

## Overview

This project implements a sales forecasting model designed to predict future sales for the stationery category. Utilizing historical data and advanced machine learning techniques, it provides detailed monthly and daily sales predictions. The goal is to assist in strategic planning and inventory management for e-commerce operations.


## Table of Contents
1. [Overview](#overview)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Methodology](#methodology)
6. [Results](#results)
7. [Contributing](#contributing)

## Overview
This project demonstrates a practical approach to sales forecasting, with particular emphasis on the "Stationery" product category. The analysis uses historical sales data to predict monthly sales, further breaking down the predictions into daily estimates.

## Features
- **Data Filtering**: Focuses on the "Stationery" category for a specialized forecast.
- **Monthly Forecasting**: Predicts sales for the first three months of the year.
- **Daily Breakdown**: Distributes monthly sales predictions into daily estimates.
- **Weekday Adjustments**: Accounts for weekday-specific sales patterns to refine daily predictions.
- **Visualizations**: Provides line charts to visualize the monthly and daily sales forecasts.


## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/hkhajei/sales-forecasting-project.git
   cd sales-forecasting-project
   ```
2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```
## Usage
 * **Data Preparation** : Make sure you have the necessary historical sales data in the ```Planning_Task.csv``` file.
 * **Run Analysis** : Execute the Python scripts in the ```PlanningTask.ipynb``` file to process data and generate forecasts.
 * **Daily Sales Breakdown**: The daily sales breakdown for the first three months is saved in an Excel file (```daily_sales_breakdown.xlsx```) after running the script.
 * **Visualization** : View charts of the forecast using Jupyter notebooks by running the main script.

## Methodology
* **Data Preprocessing**: Filters data to focus on the "Stationery" category and prepares monthly and daily sales data.
* **Forecasting**: Calculates monthly forecasts based on historical averages and predicted sales growth.
* **Daily Distribution**: Breaks down monthly predictions into daily sales using weekday sales patterns.
* **Visualization**: Plots daily and monthly sales trends for the first three months of the Persian year 1399.

## Results
The forecasting results include:

* A daily sales breakdown in Excel format for easy access.
* Visualizations showing the distribution of sales over time, highlighting weekday-based fluctuations.

## Contributing
Contributions are welcome! If you have ideas to improve the forecasting methods or the code structure, please submit a pull request.
