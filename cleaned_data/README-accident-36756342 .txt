DATE OF RELEASE
Date of release: June 2026

GENERAL INFORMATION
Title of Dataset: Victoria Road Accident Data
Author: Victoria’s Department of Transport and Planning (DTP)
Date of data collection: 1 January 2012 - 30 September 2025
Geographic location of data collection: Victoria, Australia

SHARING/ACCESS INFORMATION
Data is consolidated from Victoria Police reports and Hospital injury information to provide users with better understanding of the information about Victorian road crash.
It can be freely used for research and analysis.
Users are free to reuse and distribute the data and even make a commercial use of the materials with the condition that the attribution of the original author is included.

HOW TO USE THE DATA
The dataset can be loaded in R using the following code:
data <- read_csv("road_accident_data_tidy.csv")
A data dictionary is provided in data-dictionary-accident-36756342.csv, which describes all variables, 
their types, units, and categories. Refer to the data dictionary for variable descriptions 
before conducting any analysis.

DATA & FILE OVERVIEW
- road_accident_data_tidy.csv: Contains the cleaned dataset.
- data-dictionary-accident-36756342.csv: Provides details of all variables included in the dataset, covering variable types, units, and categories.
- README-accident-36756342.txt: Provides details about data origin, author, files, and how to use the data.

METHODOLOGICAL INFORMATION
- Description of methods used for data collection: This data has been consolidated from Victoria Police reports and Hospital injury information, then validated and enriched to provide a comprehensive and detailed view of road crashes and injuries across Victoria.
- Methods for processing the data: The data consists of multiple tables which have been joined together using ACCIDENT_NO as a primary key. The AGE_GROUP variable has been recoded into broader bands to reflect a better grouping for further analysis. Observations with missing values or unidentified values are removed from the dataset.

ASSUMPTIONS
- Data is assumed to reflect the accidents that occurred in Victoria during 1 January 2012 - 30 September 2025.
- The dataset is a sample and may not be fully representative of all accident events.





