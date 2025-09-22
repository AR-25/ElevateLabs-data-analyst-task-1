# Elevate Labs-data-analyst-task-1

# Task 1: Data Cleaning and Preprocessing for Customer Personality Analysis

This project involves cleaning and preparing the "Customer Personality Analysis" dataset from Kaggle as part of the Elevate Data Analyst Internship. The goal was to address common data quality issues to make the dataset ready for analysis.

### Summary of Changes Made:

1.  **Loaded Data**: The dataset `marketing_campaign.csv` was successfully loaded into a Pandas DataFrame.

2.  **Renamed Columns**: All column headers were converted to lowercase for consistency (e.g., `Year_Birth` became `year_birth`). Product columns were also shortened (e.g., `MntWines` to `mnt_wines`).

3.  **Handled Missing Values**: Missing values in the `income` column were identified. To preserve data, these were imputed using the **median** income, which is more robust to outliers than the mean.

4.  **Removed Duplicates**: The dataset was checked for duplicate rows, and all identified duplicates were removed to ensure the integrity of the analysis.

5.  **Corrected Data Types**: The `dt_customer` column, which was initially stored as text, was converted to a proper `datetime` format. This is crucial for any time-based analysis.

The final, clean dataset is saved as `cleaned_customer_data.csv` and is ready for the next steps of analysis or visualization.
