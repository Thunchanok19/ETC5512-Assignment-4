DATE OF RELEASE
Date of release: June 2026

GENERAL INFORMATION
Title of Dataset: Victoria 2021 Census Data
Author: Australian Bureau of Statistics
Date of data collection: 2021
Geographic location of data collection: Victoria, Australia

SHARING/ACCESS INFORMATION
Data is provided to use as a snapshot of information about Australians that reflects the community at the time the Census was undertaken.
It can be freely used for research and analysis.
Users are free to reuse and distribute the data and even make a commercial use of the materials with the condition that the attribution of the original author is included.

HOW TO USE THE DATA
The dataset can be loaded in R using the following code:
data <- read_csv("census_data_vic_tidy.csv")
A data dictionary is provided in data-dictionary-census-36756342.csv, which describes all variables, 
their types, units, and categories. Refer to the data dictionary for variable descriptions 
before conducting any analysis.

DATA & FILE OVERVIEW
- census_data_vic_tidy.csv: Contains the cleaned dataset.
- data-dictionary-census-36756342.csv: Provides details of all variables included in the dataset, covering variable types, units, and categories.
- README-census-36756342.txt: Provides details about data origin, author, files, and how to use the data.

METHODOLOGICAL INFORMATION
- Description of methods used for data collection: Data was collected by the Australian Bureau of Statistics as part of the 2021 Australian Census.
- Methods for processing the data: The data has been separated into multiple columns for easier analysis. The columns represent the minimum age, maximum age, sex, and population count within each census age group.

ASSUMPTIONS
- Population is assumed to be uniformly distributed within each census age band when applying proportional allocation to align with the road accident dataset age bands.
- The 2021 Census data is assumed to be a reasonable approximation of Victoria's population composition for the years covered by the road accident dataset, despite the time difference between the two datasets.





