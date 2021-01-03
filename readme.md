# (Investigation of fordgobike-tripdata dataset)
## by (Hany Aly Elmogey)


# This is a Udacity Advanced Data Analysis Nanodegree project

## Dataset

This data set includes information about individual rides made in a bike-sharing system. I downloaded datasets for two consecutive years 2014 and 2015. Variables:

trip_id: ID attached to each trip taken<br />
starttime: day and time trip started, in CST<br />
stoptime: day and time trip ended, in CST<br />
bikeid: ID attached to each bike<br />
tripduration: time of trip in seconds<br />
from_station_name: name of station where trip originated<br />
to_station_name: name of station where trip terminated<br />
from_station_id: ID of station where trip originated<br />
to_station_id: ID of station where trip terminated<br />
usertype: "Customer" is a rider who purchased a 24-Hour Pass; "Subscriber" is a rider who purchased an Annual Membership<br />
gender: gender of rider<br />
birthyear: birth year of rider<br />

link to the datasets files " https://divvy-tripdata.s3.amazonaws.com/index.html" For more information, visit http://DivvyBikes.com/data or email questions to data@DivvyBikes.com.

To Download the datasets and merge them together uncomment the following lines<br />
"download_files()"<br />
"merge_csv_file(files_path,save_path)"<br />

## Summary of Findings

> After investigation i found:<br />
1- Some null values which i had to remove.<br />
2- From the starttime features i created S_Day ( Start day ), S_Year, S_Month and also for the stoptime.<br />
3- Most of the trips are between few seconds and 1000 seconds.<br />
4- Males uses this service more than Females in this dataset.<br />
5- Almost all the users are subscriber.<br />



## Key Insights for Presentation

> After investigation i found:<br />
1- Most of the users are in the Age group of 2 to 40 but age group 70 to 80 has the higest trip duration average.<br />
2- The winter is the least season in the demand on bikes.<br />
3- Although males used the bikes more than females but the average trip duration for females is higher than males.<br />


