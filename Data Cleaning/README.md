# Data Cleaning
In this folder you will find the following three items:
### 1. Cleaned Data - Folder
  Contains 5 .csv files of the cleaned versions of each dataset (see README inside for more details)
### 2. Raw Data - Folder
  Contains 5 .txt files of the raw versions of each dataset (see README inside for more details)
### 3. clean_data_queries - Excel File
  Contains 1 .xls file used to query the data from each text file and to clean each dataset
#
These three items are a part of a personal project used to practice cleaning data in Excel Power Query. The data used in this project was collected from [The American Community Survey 5-Year Data 2022](https://www.census.gov/data/developers/data-sets/acs-5year/2022.html) which is a part of the United States Census Bureau. Specifically, the data was collected from the "Data Profiles" section of this website using API calls. This section contains the "2022 ACS Data Profiles Variables", ACS Technical Documentation, a table of examples for each geography level, and the supported geography for this section. The API calls for this project were done at the Region, Division, State, County, and Place levels and each contained the variables DP02_0154E and DP02_0154PE. These variables represent an estimate and a percentage, respectively, of total households with a broadband internet subscription at each geography level. For the County and Place levels, the state of South Carolina was chosen, which is indentified by the FIPS code of 45. 

The API calls for this project are given below:
- Region: [https://api.census.gov/data/2022/acs/acs5/profile?get=NAME,DP02_0154E,DP02_0154PE&for=region:*](https://api.census.gov/data/2022/acs/acs5/profile?get=NAME,DP02_0154E,DP02_0154PE&for=region:*)
- Division: [https://api.census.gov/data/2022/acs/acs5/profile?get=NAME,DP02_0154E,DP02_0154PE&for=division:*](https://api.census.gov/data/2022/acs/acs5/profile?get=NAME,DP02_0154E,DP02_0154PE&for=division:*)
- State: [https://api.census.gov/data/2022/acs/acs5/profile?get=NAME,DP02_0154E,DP02_0154PE&for=state:*](https://api.census.gov/data/2022/acs/acs5/profile?get=NAME,DP02_0154E,DP02_0154PE&for=state:*)
- County: [https://api.census.gov/data/2022/acs/acs5/profile?get=NAME,DP02_0154E,DP02_0154PE&for=county:*&in=state:45](https://api.census.gov/data/2022/acs/acs5/profile?get=NAME,DP02_0154E,DP02_0154PE&for=county:*&in=state:45)
- Place: [https://api.census.gov/data/2022/acs/acs5/profile?get=NAME,DP02_0154E,DP02_0154PE&for=place:*&in=state:45](https://api.census.gov/data/2022/acs/acs5/profile?get=NAME,DP02_0154E,DP02_0154PE&for=place:*&in=state:45)
