# (Investigation of fordgobike-tripdata dataset)
## by (Hany Aly Elmogey)


# This is a Udacity Advanced Data Analysis Nanodegree project

## Dataset

This data set includes information about individual rides made in a bike-sharing system. I downloaded datasets for two consecutive years 2014 and 2015. Variables:

trip_id: ID attached to each trip taken
starttime: day and time trip started, in CST
stoptime: day and time trip ended, in CST
bikeid: ID attached to each bike
tripduration: time of trip in seconds
from_station_name: name of station where trip originated
to_station_name: name of station where trip terminated
from_station_id: ID of station where trip originated
to_station_id: ID of station where trip terminated
usertype: "Customer" is a rider who purchased a 24-Hour Pass; "Subscriber" is a rider who purchased an Annual Membership
gender: gender of rider
birthyear: birth year of rider

link to the datasets files " https://divvy-tripdata.s3.amazonaws.com/index.html" For more information, visit http://DivvyBikes.com/data or email questions to data@DivvyBikes.com.

To Download the datasets and merge them together uncomment the following lines
"download_files()"
"merge_csv_file(files_path,save_path)"

## Summary of Findings

> After investigation i found:
1- Some null values which i had to remove.
2- From the starttime features i created S_Day ( Start day ), S_Year, S_Month and also for the stoptime.
3- Most of the trips are between few seconds and 1000 seconds.
4- Males uses this service more than Females in this dataset.
5- Almost all the users are subscriber.



## Key Insights for Presentation

> After investigation i found:
1- Most of the users are in the Age group of 2 to 40 but age group 70 to 80 has the higest trip duration average.
2- The winter is the least season in the demand on bikes.
3- Although males used the bikes more than females but the average trip duration for females is higher than males.


