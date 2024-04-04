---
# Unemployment Analysis

This project focuses on analyzing unemployment data in India using various visualization techniques.

## Dataset
The dataset used for this analysis is stored in "Unemployment_in_India.csv". It contains the following columns:
- **Region**: Region in India
- **Date**: Date of observation
- **Frequency**: Frequency of data collection
- **Estimated Unemployment Rate (%)**: Percentage of estimated unemployment
- **Estimated Employed**: Estimated number of employed individuals
- **Estimated Labour Participation Rate (%)**: Labour participation rate
- **Area**: Area details

## Dependencies
- pandas
- matplotlib
- seaborn
- plotly

## Project Overview
1. Imported necessary libraries including pandas, matplotlib, seaborn, and plotly.
2. Loaded the dataset from "Unemployment_in_India.csv".
3. Preprocessed the data:
   - Checked for null values and removed them.
   - Checked for duplicate entries and removed them.
4. Explored the dataset:
   - Reviewed the shape, columns, and basic statistics of the data.
   - Examined the distribution of data based on regions and areas.
5. Visualized the data using different plots:
   - Heatmap to show correlations between unemployment rate, employment, and labour participation.
   - Histograms to visualize the distribution of unemployment rate and employment across different areas.

## Running the Code
1. Ensure you have the required dependencies installed.
2. Place the dataset file "Unemployment_in_India.csv" in the same directory as the code file.
3. Run the Python code provided to perform data analysis and visualization.

## Sample Visualizations
### Heatmap
The heatmap visualizes the correlations between different variables in the dataset. It helps in understanding how the estimated unemployment rate, estimated employed individuals, and estimated labour participation rate are related to each other. Higher correlation values (closer to 1 or -1) indicate stronger relationships between the variables.


### Unemployment Rate Distribution
The histogram displays the distribution of estimated unemployment rates across different areas in India. It provides insights into the range of unemployment rates and their frequency of occurrence in each area.


### Employment Distribution
The histogram illustrates the distribution of estimated employed individuals across different areas in India. It shows the variation in the number of employed individuals in each area, helping to identify areas with higher or lower employment rates.


## Note
The dataset used in this analysis is almost cleaned and doesn't require extensive preprocessing tasks. However, for real-world datasets, additional preprocessing such as handling missing values, outliers, and feature engineering may be necessary.
