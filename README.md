# Student Academic Pipeline
This database stores information of students for application untill graduation. A typical pipeline is students starts with application, get admission, get enrolled and ends with graduation.

## Data Source
The primary data source are the .csv file. 

## Tools
Postgresql, R, Excel

## Data Base Structure
This database has three layers,

### i. Bronze Layer
All the raw data from the souce, basically .csv files, are stored in this layer as is.
### ii. Silver Layer
All the cleaning of the data is performed in this layer. For instance, checking data quality, missing values, imputation, data enrichment, standardization, integration, etc.
### iii. Gold Layer
