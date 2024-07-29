# COVID-19 Data Analysis Using Python

This project compares the COVID-19 dataset with the World Happiness Report to explore correlations between COVID-19 impacts and happiness metrics across different countries. The analysis involves data cleaning, aggregation, and visualization to uncover insights.

## Datasets
1. `covid19_Confirmed_dataset.csv`: Contains confirmed COVID-19 cases for various countries.
2. `worldwide_happiness_report.csv`: Contains happiness metrics for various countries.

## Steps
1. **Loading and Cleaning Data:**
   - Load the COVID-19 dataset.
   - Drop unnecessary columns (latitude and longitude).
   - Aggregate data by country.

2. **Data Visualization:**
   - Plot COVID-19 cases for specific countries (China, Italy, Spain).
   - Analyze and plot China's daily new cases.

3. **Calculate Maximum Infection Rates:**
   - Compute the maximum daily new infection rates for each country.
   - Create a DataFrame with the maximum infection rates.

4. **Loading and Cleaning Happiness Data:**
   - Load the World Happiness Report.
   - Drop unnecessary columns.
   - Set country names as the index.

5. **Merge Datasets and Analyze Correlations:**
   - Merge the COVID-19 data with the happiness data.
   - Compute and plot correlations between maximum infection rates and happiness metrics (GDP per capita, social support, healthy life expectancy, freedom to make life choices).

## Libraries Used
- Pandas
- Matplotlib
- Seaborn
- Numpy

## Usage
Run the provided code to load, clean, and analyze the datasets. The code will produce various plots illustrating the relationships between COVID-19 impacts and happiness metrics.

## Summary
This analysis provides insights into how the pandemic's impact correlates with happiness metrics across different countries. The visualizations help in understanding these relationships better.
