## Weather Data Analysis Project

This project analyses weather data from the National Centers for Environmental Information (NCEI) Global Historical Climatology Network daily (GHCNd) dataset, focusing on observations from the Ann Arbor Michigan location. The dataset is stored in the file `NCEIclimaterecords.csv`.

## Dataset Overview

The dataset contains daily climate records from various weather stations across the globe. Each row represents a single observation from a weather station and includes the following variables:

- `id`: Station identification code
- `date`: Date in YYYY-MM-DD format (e.g., 2012-01-24 = January 24, 2012)
- `element`: Indicator of element type
- `TMAX`: Maximum temperature (tenths of degrees Celsius)
- `TMIN`: Minimum temperature (tenths of degrees Celsius)
- `value`: Data value for element (tenths of degrees Celsius)

## Project Objective

For this project, the following tasks are performed:

Plot line graphs of the record high and record low temperatures by day of the year over the period 2005-2014. Overlay a scatter plot of the 2015 data for any points (highs and lows) for which the ten-year record (2005-2014) record high or record low was broken in 2015.


## Files

- `NCEIclimaterecords.csv`: Dataset containing daily climate records from weather posts in the Michigan area.
- `Temperature_Trends.ipynb`: Jupyter Notebook containing code for training and evaluating the model.

## Usage

To run the notebook:

1. Ensure you have Jupyter Notebook installed.
2. Clone or download the repository containing the notebook and the dataset.
3. Open the notebook using Jupyter Notebook.
4. Execute each cell in the notebook sequentially to load the data, train the model, and evaluate its performance.
## Dependencies

The following Python libraries are required to run the notebook:

- `pandas`: For data manipulation and analysis.
- `matplotlib`: For data visualisation.
- `numpy`: For numerical operations.
