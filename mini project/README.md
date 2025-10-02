BDA-Big-Data-Analytics-4-1

COVID-19 Testing Data Analysis

Overview:

This project analyzes COVID-19 testing data across different states using a dataset of testing records. It focuses on testing trends, state-wise distribution, positivity rates, and temporal analysis.

The goal is to understand testing patterns, identify hotspots, and provide actionable recommendations for public health interventions.

Dataset:

File: covid_testing.csv

Records: [Provide total records, e.g., 15,000]

Columns include:

Date – Date of testing

State – Name of the state

TotalSamples – Total number of tests conducted

Negative – Number of negative results

Positive – Number of positive results

Analysis Performed:

Data Cleaning: Handling missing values, duplicates, and outliers

Descriptive Statistics: Mean, median, distributions of numeric columns

Visualizations: Histograms, line charts, bar charts, pie charts, scatter plots

Relationship Analysis:

TotalSamples vs Positive cases

State-wise Positive/Negative distribution

Temporal trends of Positive/Negative cases

Positivity rate analysis (Positive / TotalSamples)

Key Findings:

Daily testing volumes fluctuate, with peaks on certain dates.

Certain states consistently report higher testing numbers.

Positive cases are concentrated in a few states, indicating regional hotspots.

Positivity rates vary over time and across states.

Outliers exist in TotalSamples and Positive counts, likely due to reporting anomalies or mass testing events.

Recommendations:

Focus testing resources on states with higher positivity rates.

Allocate additional testing kits during peak testing periods.

Standardize data entry and reporting procedures to reduce errors and duplicates.

Monitor positivity rates in real-time to guide public health interventions.

Expand testing in underrepresented states to ensure comprehensive coverage.

Tools Used:

Python (Pandas, NumPy)

Matplotlib, Seaborn

Jupyter Notebook