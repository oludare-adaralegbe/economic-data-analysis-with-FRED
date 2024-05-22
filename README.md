# Economic Data Analysis with FRED and pandas

This project analyzes and explores the relationship between economic indicators using data from the Federal Reserve Economic Data (FRED) and performs the analysis with pandas and the FRED API in Python. The codebase is built upon the foundations provided by a tutorial by Rob Mulla ([YouTube Link](https://www.youtube.com/watch?v=R67XuYc9NQ4)). I extended the initial exploration by analyzing the relationship between the Unemployment Rate and Consumer Confidence, as well as the relationship between the Unemployment Rate and Job Openings, providing my own analysis.

## Getting Started

### 1. Prerequisites

- Python 3.11
- pandas library: `pip install pandas`
- fredapi library: `pip install fredapi`
- matplotlib library: `pip install matplotlib`
- plotly express library: `pip install plotly_express`
- SciPy: `pip install scipy`
- Statsmodels: `pip install statsmodels`

### 2. Obtain a FRED API Key

- Create a free account at [FRED](https://fred.stlouisfed.org/docs/api/fred/)
- Generate an API key under "My Account" -> "API Keys"

## Project Highlights

- **Data Gathering**: Successfully retrieved economic indicator data from FRED using the fredapi library.
- **Data Cleaning and Exploration**: Analyzed the data for missing values and overall characteristics using pandas functionalities.
- **Correlation Analysis**: Calculated correlation coefficients between chosen economic indicators to understand potential relationships (e.g., Unemployment Rate vs. Participation Rate, Consumer Confidence, Job Openings).
- **Statistical Significance Testing**: Performed tests like Granger causality (using statsmodels) to assess if changes in one variable might influence another.
- **Data Visualization**: Created informative visualizations (e.g., line plots) using libraries like matplotlib and Plotly Express to visually explore the data and relationships.
