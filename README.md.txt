# US Electric Charging Stations - Data Analysis with Python

## Project Overview

This project explores alternative-fuel station data across the United States, with a particular focus on publicly accessible electric vehicle charging stations.

Using Python and pandas, I analyzed station counts, fuel types, ownership categories, public access and geographical differences to identify patterns in charging infrastructure.

## Dataset

The dataset contains 819 records and five columns:

- `fuel` - Type of alternative fuel
- `state` - US state or district
- `owner` - Station ownership category
- `access` - Public or private accessibility
- `number_of_stations` - Number of stations represented by each record

**Note:** Each row represents a group of stations rather than an individual station. Therefore, the number of records is different from the total number of stations.

## Tools and Technologies

- Python
- pandas
- Jupyter Notebook

## Skills Demonstrated

- Importing CSV datasets using pandas
- Exploring data using head(), value_counts() and describe()
- Sorting DataFrames using sort_values()
- Creating Boolean masks
- Filtering data using multiple conditions
- Comparing station counts across ownership categories and states
- Interpreting and communicating analytical findings

## Key Findings

- Electric charging stations represent 260 of the dataset's 819 records, making electric the most frequently represented fuel category.
- Station counts vary substantially, with a mean of approximately 34.74 and a median of 5 stations per record.
- The dataset contains 134 publicly accessible electric charging station records, of which 51 are privately owned.
- Among non-privately owned public electric charging records, 21 contain more than 17 stations.
- Washington has 425 publicly accessible electric charging stations in the dataset, compared with 299 in Oregon.
- Private ownership accounts for the largest publicly accessible electric charging station counts in both Washington and Oregon.

## Project Files

- `ev_charging_stations_analysis.ipynb` — Jupyter Notebook containing the Python analysis, results and interpretations
- `stations.csv` — Dataset used in the analysis

## How to Run the Project

1. Download the notebook and CSV file into the same folder.
2. Open `ev_charging_stations_analysis.ipynb` in Jupyter Notebook.
3. Ensure Python and pandas are installed.
4. Run all notebook cells from top to bottom.

## Conclusion

This project demonstrates how Python and pandas can be used to explore alternative-fuel station data and investigate differences in electric charging infrastructure.

The analysis highlights variations in station counts, ownership categories and geographical distribution, while demonstrating fundamental data exploration, filtering and sorting techniques.