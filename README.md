## Linear Regression and Model Comparison on Buenos Aires Land Prices

This project analyzes land prices in Buenos Aires through linear regression and model comparison, using Bayesian inference to explore the socio-economic drivers affecting land affordability. The analysis leverages recent housing and inflationary trends, using historical data to understand price dynamics and disparities in different neighborhoods and districts across Buenos Aires.

### Project Overview

Buenos Aires faces escalating socio-economic challenges, with severe inflation, currency devaluation, and a housing market strain that has intensified homelessness and economic disparity. This project seeks to analyze land price data to gain insights into these issues. Using a dataset from the Buenos Aires Data program, we perform regression analysis and Bayesian model comparisons to explore land price determinants across different regions in the city.

#### Objectives

1. **Data Exploration and Model Fitting**: Perform linear regression on the "Lands of Buenos Aires: Prices" dataset to model and understand variations in land prices.
2. **Bayesian Model Comparison**: Compare models with Bayesian inference to evaluate the best model for predicting land prices based on location, size, and neighborhood characteristics.

### Data Summary

The dataset provides a comprehensive view of land property data in Buenos Aires from 2014 to 2018, covering 15 districts and 48 neighborhoods, with over 7,000 observations. Key attributes include:

- **LAT**: Latitude
- **LON**: Longitude
- **M2**: Land area in square meters
- **USD**: Price in USD
- **NEIGHBORHOOD**: Specific neighborhood
- **COMMUNE**: District/community identifier

This dataset allows a focused analysis of property trends and land price variations, enabling us to evaluate housing affordability and accessibility issues.

### Repository Structure

- **`data/`**: Contains the cleaned dataset and any pre-processed files.
- **`analysis/`**: Jupyter Notebooks detailing:
  - `linear_regression.ipynb`: Initial linear regression and exploratory data analysis.
  - `model_comparison.ipynb`: Bayesian model comparison to identify the best model.
- **`results/`**: Visualizations, tables, and summary statistics from the analysis.

### How to Run

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/buenos-aires-land-prices.git
   cd buenos-aires-land-prices
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

### Results and Findings

Our analysis uncovers significant disparities in land prices across neighborhoods, with a notable impact of location (latitude and longitude), land size, and socio-economic factors. The model comparison section shows that Bayesian methods can robustly highlight underlying patterns and validate model performance, aiding in reliable predictions for land price determinants.

### References

- Buenos Aires Data Program: Original source of the "Lands of Buenos Aires: Prices" dataset.
- Background information and supporting data derived from recent news on Buenos Aires' socio-economic conditions.
