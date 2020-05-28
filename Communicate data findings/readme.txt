Ford Go Bikes Exploration 

#What is this dataset

Ford Go Bikes is a public bike sharing system in the San Francisco Bay Area in California.
The dataset used for this exploratory analysis consists of files containing monthly individual trip data
from January 2018 to December 2018 in CSV format.
These files were downloaded from 'https://s3.amazonaws.com/baywheels-data/index.html' 
and they were gathered together to form one big dataset containing some information like type of users , 
start and end time , start and end points and duration of the trips.
The Files gathered for year 2018 have about 1.8 million records with initially 14 columns .

#Main findings from the exploratory data analysis 

After assessing the data to define its issues , we had to clean the data a little bit and add some new columns 
Columns added are :
1-start month 
2-start week day
3-start hour 
4-distance 
We used the Exploration methods to find interesting trends and relations inside the dataset .
Main findings are :
1-Subscriber users are much more than Customer users .
2-Bikes shared for trips represent 91.3% in the total trips of the year 2018.
3-Subscribers use bikes in weekdays more while customers use bikes in weekends more.
4-The average trip duration all over the year is 500 seconds ( around 8.5 minutes ).
5-The highest count of trips occur in October month , and the lowest in January (may be due to heavy ice falling) 