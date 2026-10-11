# Spatial Regression Analysis of Poverty in North Sumatra

## About
This project analyzes the percentage of the poor population across regencies and cities in North Sumatra in 2023. Ordinary Least Squares (OLS) and spatial regression models are compared to examine spatial dependence and identify a suitable model for the data.

## Project Analysis
- [**View Full Analysis on RPubs**](https://rpubs.com/sandraberlianaputri/spatial-regression-north-sumatra-poverty)

## Dataset
- **Region:** North Sumatra, Indonesia
- **Period:** 2023
- **Observations:** 33 regencies and cities
- **Data source:** `Sumut.xlsx` and regional boundary data
- **Response variable:**
  - `PPM`: Percentage of the poor population
- **Explanatory variables:**
  - `RLS`: Mean years of schooling
  - `PPK`: Expenditure per capita
  - `UHH`: Life expectancy
  - `HLS`: Expected years of schooling
- **Data quality:** No missing values were reported in the dataset.

## Methods
- **Exploratory Data Analysis:** Descriptive statistics, boxplots, correlation analysis, and thematic maps.
- **Spatial Weights:** Queen and rook contiguity, k-nearest neighbors, radial distance, inverse distance, and exponential distance.
- **Spatial Autocorrelation:** Moran's I and Lagrange Multiplier tests.
- **Modeling:** OLS, Spatial Autoregressive (SAR), Spatial Error (SEM), and SARMA models.
- **Model Selection:** Comparing AIC values and residual diagnostic tests.
- **Spatial Interpretation:** Examining direct, indirect, and total effects.

## Author
**Sandra Berliana Putri** - Statistics and Data Science graduate from IPB University.
