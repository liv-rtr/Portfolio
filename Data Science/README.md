# Data Science

In this folder you will find the following items:
1. Condo_Pricing.Rmd - R Markdown
2. Condo_Pricing.nb.html - Compiled R Notebook
3. ZHVI_Unpivot.csv - Cleaned data
4. ZHVI_raw.csv - Raw data

These are apart of a personal project. This project explores various machine learning techniques to predict the Zillow Home Value Index (ZHVI) for condominiums(condos) and co-operatives(co-ops) across the United States using time-series data. The raw time-series data for this project can be found [here](https://www.zillow.com/research/data/). Specifically, the .csv file can be found under the "HOME VALUE" section, choosing "ZHVI Condo/Co-op Time Series ($)" for "Data Type" and "Metro & U.S." for "Geography". This data was then exported to Excel Power Query where it was unpivoted and merged with the 'United States Cities Database' (which can be found [here](https://simplemaps.com/data/us-cities) to extract latitude and longitudes for each city. The unpivoted and merged data was then was cleaned further in-code, by removing missing ZHVI values, and manually inputting missing latitude and longitude information from Google.
   
