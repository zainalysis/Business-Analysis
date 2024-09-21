# Fred Economic Analysis

This project is a comprehensive analysis of various economic indicators using data from the Federal Reserve Economic Data (FRED) API. The analysis focuses on pulling data such as the S&P 500 index, unemployment rates, and labor force participation rates for different U.S. states, then visualizing these datasets with interactive plots using Plotly.

## Project Overview

This project provides an easy-to-follow demonstration of using the `fredapi` package to fetch economic data and create interactive time series visualizations for various key indicators. The visualizations help provide insight into the state of the U.S. economy between 2020-2022, including:

1. **S&P 500 Index**
2. **U.S. Unemployment Rate**
3. **Unemployment and Labor Force Participation Rate for U.S. States**

## Key Features

- **Data Retrieval**: Connect to the FRED API using the `fredapi` library to retrieve economic data series.
- **Data Wrangling**: Use `pandas` to clean and manipulate the data for analysis.
- **Interactive Visualizations**: Plot economic indicators over time with `plotly`, enabling detailed comparisons between states.
- **Multiple Subplots**: Compare unemployment and participation rates for different U.S. states in a grid format.
- **Customizable Layout**: Interactive plots allow for better exploration and presentation of trends in economic data.

## Installation

To use this project, you'll need to install the necessary dependencies. You can install them using the following command:

```bash
pip install fredapi pandas numpy plotly
```

## Getting Started

1. **FRED API Key**: You need to register for an API key at the [FRED API website](https://fred.stlouisfed.org/) and insert it in the code where `fred_key` is defined.

2. **Run the Project**: After setting up your environment and installing dependencies, you can run the provided code to retrieve and visualize the economic data. The key analysis sections include:
   - S&P 500 Time Series Visualization: Fetch and plot the historical S&P 500 index.
   - US Unemployment Rate: Time series visualization of the U.S. unemployment rate.
   - State-wise Unemployment and Participation Rate: Compare the unemployment and labor force participation rates across various states.

3. **Explore Plots**: Interactive charts can be explored by zooming, panning, and hovering to inspect data points.

## Example Output

- **S&P 500 Time Series**
  

- **US Unemployment Rate**
  

- **State-wise Unemployment and Participation Comparison**


## Project Structure

```bash
|-- Fred_Economic_Analysis.ipynb    # Main Jupyter notebook containing the analysis
|-- README.md                       # Project documentation
|-- requirements.txt                # List of dependencies
```

## Data Sources

- **Federal Reserve Economic Data (FRED)**: This project utilizes data available from FRED, which provides access to a large repository of economic data series. The API allows for seamless integration into Python for analysis.

## Future Work

- **Additional Indicators**: Expand the analysis to include other relevant economic indicators like inflation, GDP growth, or interest rates.
- **State-wise Comparison**: Provide more granular insights and statistical analysis for state-level unemployment and participation rates.

## License

This project is licensed under the MIT License. Feel free to use and modify it as per your needs.

---
