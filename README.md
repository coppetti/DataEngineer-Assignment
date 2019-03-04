# Yacht Data Engineer Assignment

## The Challenge
The city of Seattle has an open data program where we can find different datasets.
For this challenge we will be analysing their data for Crimes and Use of Force.

Your task here is to ETL these data into you preferred DB and programming language, and:

* Provide a report with crimes by date and time;
* Provide a report with crimes by date,time and precinct-sector;
* Provide a report with crimes by time and precinct;
* Analyse the Use of Force dataset and give your insights regarding the use of force in each precinct-sector and the
incidents in same area (date, time, datetime).

The outputs must be in a well documented CSV format.

## The Data

+ Crime data

```
Report Number,Occurred Date,Occurred Time,Reported Date,Reported Time,Crime Subcategory,Primary Offense Description,Precinct,Sector,Beat,Neighborhood
1975000079415,12/16/1975,900,12/16/1975,1500,BURGLARY-RESIDENTIAL,BURGLARY-FORCE-RES,SOUTH,R,R3,LAKEWOOD/SEWARD PARK
1976000069169,01/01/1976,1,01/31/1976,2359,SEX OFFENSE-OTHER,SEXOFF-INDECENT LIBERTIES,UNKNOWN,,,UNKNOWN
1979000049118,01/28/1979,1600,02/09/1979,1430,CAR PROWL,THEFT-CARPROWL,EAST,G,G2,CENTRAL AREA/SQUIRE PARK
```

+ Use of Force

```
ID,Incident_Num,Incident_Type,Occured_date_time,Precinct,Sector,Beat,Officer_ID,Subject_ID,Subject_Race,Subject_Gender
11865-1741-4871,11865,Level 1 - Use of Force,07/19/2016 06:40:00 AM,E,E,E1,1741,4871,Black or African American,Male
11898-1840-9082,11898,Level 1 - Use of Force,07/21/2016 04:12:00 PM,E,C,C2,1840,9082,White,Female
10924-907-8357,10924,Level 2 - Use of Force,05/01/2016 06:00:00 PM,W,K,K1,907,8357,Not Specified,Not Specified
10710-1065-2989,10710,Level 2 - Use of Force,05/01/2016 07:30:00 PM,W,K,K1,1065,2989,White,Male
```

## Acceptance Criteria
In order to have a full solution we ask you to:

* Write a README.m file with your documentation and usage instructions;
* Write unit tests;
* Deploy your solution in a Docker image;
* Your solutiuon must run in a UNIX environment with `./run.sh`;
* Your solution must be hosted on a public github and contains all your git history.
