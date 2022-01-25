# covid-data-cleaning
Jupyter notebook used to clean covid data export into csv

This data cleaning proccess was used to facilitate my analysis of COVID-19 data in excel. The code can be found in Cleaning.ipynb. The dataset can be found in 20220123 Global Covid Data.csv.
Cleaning.ipynb takes the dataset and removes irrelevant columns for my analysis, extracts the relevant countries, and filters out dates before 1/5/2021. It then exports the individual country data out as separate csv files. The exported files are titled "[country]_cleaned.csv".
