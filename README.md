# BikeShare
Using Python's Pandas and Numpy libraries, made an interactive guide exploring bike share data from 3 major cities.
The data is requests information about the first 6 months of 2017.

## The Data
This data pulls from three csv files saved in the zip files of this repository. 
Based on the first question of the program, it will read in the city csv file into a data frame.

## The program
1st Question: request city to view data

2nd Question: request day filters
	If input is day, request what day of the week you would like to view.
	If input is month, it will request if you would like to see January through June

### Output
The output will show several demographics:
- Frequency of time 
- Popular stations
- Trip duration
- User stats

After this, the program will request if you like to see the first five results
	If respond is yes, will show 5 result and will continue to ask if you would like to see more.
  
Afterward, will ask if you would like to do another analysis
