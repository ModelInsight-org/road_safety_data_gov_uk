
# Ideas to try

* Look at
 * Casualties
 * Vehicles by Make and Model
 * Blood Alcohol (note no locations, simplified dates)
* Merge the accident id (see Accidents and Vehicles) to merge more data sources together
* Can we draw a linear trend out of something?

# Data sources

* Page of data: https://data.gov.uk/dataset/road-accidents-safety-data and put the following into "./data/"
* "DfTRoadSafety_Accidents_2014.csv" <- http://data.dft.gov.uk/road-accidents-safety-data/DfTRoadSafety_Accidents_2014.zip
* "DfTRoadSafety_Vehicles_2014.csv" <- http://data.dft.gov.uk/road-accidents-safety-data/DfTRoadSafety_Vehicles_2014.zip
* "DfTRoadSafety_Casualties_2014.csv" <- http://data.dft.gov.uk/road-accidents-safety-data/DfTRoadSafety_Casualties_2014.zip
* "Road Safety - Vehicles by Make and Model 2014.csv" <- http://data.dft.gov.uk.s3.amazonaws.com/road-accidents-safety-data/Road%20Safety%20-%20Vehicles%20by%20Make%20and%20Model%202014.zip
* "DigitalBreathTestData2014.txt" <- http://data.dft.gov.uk/road-accidents-safety-data/DigitalBreathTestData2014.zip
* "Stats19_Data_2005-2014/(3 files)" <- http://data.dft.gov.uk.s3.amazonaws.com/road-accidents-safety-data/Stats19_Data_2005-2014.zip

My working directory looks like:

```
.../road_safety_data_gov_uk/data $ ls -lt
total 36084
-rw-r--r-- 1 ian ian 16833469 Jul 21  2015 DfTRoadSafety_Vehicles_2014.csv
-rw-r--r-- 1 ian ian 20099000 Jun 19  2015 DfTRoadSafety_Accidents_2014.csv
```
