# Analysis of Economic Data using FRED API and Python

## Overview

This Jupyter Notebook involves data scraping, data cleaning, retrieval, manipulation, and visualization to analyze various economic indicators using the Federal Reserve Economic Data (FRED) API in Python. The project focuses on exploring and comparing unemployment rates, labor force participation rates, and other economic metrics across different U.S. states.


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
  ![image](https://github.com/ParmeetChanne/Analysing-Economic-Factors-Python/assets/67189839/64915e74-a366-4a2c-b817-aee9dcb57016)


### 2. Unemployment Rate Analysis
- Retrieval and comparison of monthly unemployment rates across U.S. states.
- Visualization of unemployment rates for specific periods using Plotly.

### 3. April 2020 Unemployment Rate Comparison
- Bar graph representation comparing unemployment rates of different states in April 2020 post-lockdown.
  ![image](https://github.com/ParmeetChanne/Analysing-Economic-Factors-Python/assets/67189839/9309ccb2-b5ef-4994-beb8-b9643de6b345)


### 4. Labor Force Participation Rate Analysis
- Retrieval and comparison of monthly participation rates across U.S. states.

### 5. Comparing Unemployment and Participation Rates by State
- Comparison between unemployment and participation rates for individual states between 2020 and 2021.
- Visualization of trends using matplotlib for a single state and all states.
  ![image](https://github.com/ParmeetChanne/Analysing-Economic-Factors-Python/assets/67189839/84f49a1a-ff5d-474d-839c-d33a20fd0ea2)
  ![image](https://github.com/ParmeetChanne/Analysing-Economic-Factors-Python/assets/67189839/5c43ad6d-90ab-4be7-b7ae-97f6a23bdf48)


## Insights and Interpretations

This notebook provides insights into the economic trends, particularly unemployment and labor force participation rates across different U.S. states during crucial periods, such as the COVID-19 pandemic's onset in April 2020.

## Acknowledgments

The data used in this analysis is sourced from the FRED API by the Federal Reserve Bank of St. Louis.

