# Seattle or New York City, Which Rains More?

The purpose of this project is to determine whether it rains more in Seattle, WA or New York City, NY. 


# Data

Weather data will be acquired from the National Centers for Environmental Information NOAA Climate Date from Jan. 1, 2020 to Jan. 1, 2024. Their website can be found here:

https://www.ncei.noaa.gov/cdo-web/search?datasetid=GHCND

The files containing the data used for this project can be found here:

https://github.com/galenegan/DATA-3320/tree/main/weather

# Requirements
All Data Analysis was performed using Python. All imports used are publicly available. All code was written using Google Colab. 



# Data Preparation

To prepare the data, all columns besides city, date and precipitation were removed. Null valued were interpolated. Due to mismatched station data, the averages for each day for Seattle and New York was taken to ensure that each day of each city had one precipitation data point. The Date column was converted to DateTime. After joining the two data frames, the merged data frame was converted into a tidy format. 


# Data Analysis

To analyze the data, visualizations were created to compare New York City and Seattle precipitation cumulatively, yearly, and monthly. The results were summarized and communicated in a report linked below. 

# Author(s)
This project was created by Eli Gunderman as part of his Methodology of Data Science course. 
LinkedIn profile can be found here: https://www.linkedin.com/in/eli-gunderman/

# License
No license is required to use any materials included in this project.


## File Locations: 

### File which performed data preparation named "data_preparation.ipynb"

### File which contains exported, clean data file is called "merged_weather_data.csv"

### File which contains Data Analysis is called "data_analysis.ipynb
