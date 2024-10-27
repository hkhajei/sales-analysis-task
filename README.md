# Sales Forecasting Project

This repository contains a comprehensive sales forecasting solution aimed at predicting sales figures for the first three months of the Persian calendar year 1399. Using a combination of time-series analysis, Python, and visualization tools, this project breaks down monthly predictions into daily sales estimates, accounting for both general trends and weekday-specific sales patterns.

## Table of Contents
1. [Overview](#overview)
2. [Features](#features)
3. [Project Structure](#project-structure)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Methodology](#methodology)
7. [Results](#results)
8. [Contributing](#contributing)

## Overview
This project demonstrates a practical approach to sales forecasting, with particular emphasis on the "Stationery" product category. The analysis uses historical sales data to predict monthly sales, further breaking down the predictions into daily estimates.

## Features
- **Data Filtering**: Focuses on the "Stationery" category for a specialized forecast.
- **Monthly Forecasting**: Predicts sales for the first three months of the year.
- **Daily Breakdown**: Distributes monthly sales predictions into daily estimates.
- **Weekday Adjustments**: Accounts for weekday-specific sales patterns to refine daily predictions.
- **Visualizations**: Provides line charts to visualize the monthly and daily sales forecasts.

## Project Structure
The project structure is as follows:

```
├── data/              # Historical and predicted sales data
├── notebooks/         # Jupyter notebooks for exploration and analysis
├── src/               # Main Python scripts for data processing and forecasting
├── README.md          # Project overview
└── requirements.txt   # Required Python packages
```

```bash
git clone https://github.com/yourusername/sales-forecasting-project.git
cd sales-forecasting-project
```

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/sales-forecasting-project.git
   cd sales-forecasting-project
   ```
2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```
## Usage
 * **Data Preparation** : Make sure you have the necessary historical sales data in the ```data/``` folder.
 * **Run Analysis** : Execute the Python scripts in the ```src/``` folder to process data and generate forecasts.
 * **Daily Sales Breakdown**: The daily sales breakdown for the first three months is saved in an Excel file (```daily_sales_breakdown.xlsx```) after running the script.
 * **Visualization** : View charts of the forecast using Jupyter notebooks in ```notebooks/``` or by running the main script.

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
