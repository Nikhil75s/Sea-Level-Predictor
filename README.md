# Sea Level Predictor

This project analyzes historical global average sea level data and predicts future sea level changes through the year 2050. Using Python and libraries such as Pandas, Matplotlib, and SciPy, the project creates visualizations and calculates trends to understand the rate of sea level rise over time. 

## Features

1. **Data Analysis:**
   - Import and process historical sea level data from `epa-sea-level.csv`.
   - Visualize the relationship between time (Year) and sea level (CSIRO Adjusted Sea Level) using scatter plots.

2. **Trend Prediction:**
   - Calculate the line of best fit for the entire dataset using `linregress` from SciPy.
   - Extend the trend line to the year 2050 to predict future sea levels.
   - Compute a separate trend line for data from 2000 onward to assess recent changes in the rate of sea level rise.

3. **Data Visualization:**
   - Generate clear and labeled plots with:
     - **X-axis:** Year
     - **Y-axis:** Sea Level (inches)
     - **Title:** Rise in Sea Level

4. **Image Export:**
   - Save generated visualizations as images for further analysis and reporting.

## Development

- Write and implement functionality in `sea_level_predictor.py`.
- Use `main.py` for testing and visualization during development.

## Testing

- Run unit tests located in `test_module.py` to ensure code correctness.
- Tests are integrated with `main.py` for convenience during development.

## Data Source

The dataset is sourced from the **US Environmental Protection Agency**:
- **Global Average Absolute Sea Level Change (1880–2014)**
  - Compiled using data from:
    - CSIRO, 2015
    - NOAA, 2015

## Objectives

This project aims to:
- Enhance understanding of historical sea level trends.
- Provide visual tools for analyzing the impact of recent changes.
- Predict future sea level rise to aid in environmental planning and awareness.

---