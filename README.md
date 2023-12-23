# Analysing-Economic-Factors-Python
Here is a jupyter notebook I created for the analysis of economic factors with python using the FRED dataset!

This project involves data scraping, data cleaning and exploration

- Include photographs of the plots
- Include overview and all the steps
- Include acknowledgement of FRED Api at last
- Include all the tech used

# Economic Data Analysis using FRED API and Python

## Overview

This Jupyter Notebook explores economic data analysis using the Federal Reserve Economic Data (FRED) API in Python. The project involves data scraping, data cleaning, and exploration. It includes data retrieval, manipulation, and visualization to analyze various economic indicators, focusing on unemployment rates, participation rates, and their comparison across different U.S. states.

## Prerequisites

Ensure you have the following installed:

- Python 3.x
- Required Python libraries: pandas, numpy, matplotlib, plotly, fredapi
- Access to FRED API with an API key

## Setup and Usage

1. **Installation**: Install the required Python libraries using the following command:

<code>!pip install fredapi pandas numpy matplotlib plotly</code>


2. **API Key**: Replace the `fred_key` variable with your FRED API key.

3. **Running the Notebook**: Execute the code cells sequentially to retrieve economic data, perform analysis, and generate visualizations.

## Contents

### 1. Retrieving and Plotting S&P 500 Data
- Use of FRED API to retrieve and plot S&P 500 data over time.

### 2. Unemployment Rate Analysis
- Retrieval and comparison of monthly unemployment rates across U.S. states.
- Visualization of unemployment rates for specific periods using Plotly.

### 3. April 2020 Unemployment Rate Comparison
- Bar graph representation comparing unemployment rates of different states in April 2020 post-lockdown.

### 4. Labor Force Participation Rate Analysis
- Retrieval and comparison of monthly participation rates across U.S. states.

### 5. Comparing Unemployment and Participation Rates by State
- Comparison between unemployment and participation rates for individual states between 2020 and 2021.
- Visualization of trends using matplotlib for a single state and all states.

## Insights and Interpretations

This notebook provides insights into the economic trends, particularly unemployment and labor force participation rates across different U.S. states during crucial periods, such as the COVID-19 pandemic's onset in April 2020.

## Acknowledgments

The data used in this analysis is sourced from the FRED API by the Federal Reserve Bank of St. Louis.

