# Project Group 45 Section 001: NYC Data

## Data Description
There are many open data sets for public consumption or use published by New York City. This consists of a data set that includes 311 phone numbers for the non-emergency services call.

Many data points are tracked and summarized every time the 311 phone number is called.

It's a CVS file [containing a year of data from this dataset](https://drive.google.com/drive/folders/1BRd8_RSST69UaZRBeD_dtXGw9fuKoBZE?usp=sharing). 

Each date contains information about Created Date, Closed Date, Agency Name, Complaint Type, Descriptor, Location Type, Incident Zip, Incident Address, Street Name, Cross Street 1, Cross Street 2, Intersection Street 1, Intersection Street 2, Address Type, City, Landmark, Facility Type, Status, Due Date, Resolution Description , Resolution Action, Updated Date, Community Board, BBL, Borough, X Coordinate (State Plane), Y Coordinate (State Plane), Open Data Channel Type, Park Facility Name, Park BoroughBridge, Latitude, Longitude and Location.  

For the project, we focus on features like Incident Zip and Complaint Type to get analysis of the complaints in the New York City.



## Project Work
For the the project, we want to explore the details of service request made by people from area(Zip Code:10025). 

In order to figure out the top 10 incident types in the area, we use value_counts and display the incident types and count values in descending order. The top 10 incident types analysis is stored in Top10.ipynb. 

The illegal parking incidents area major problems in New York area. We analyze the illegal parking incidents fraction(parking incidents/ total incidents) in our area(Zip Code:10025) compared to the whole city. The analysis of the illegal parking is stored in Parking.ipynb.




## Name: 
Xinhang Li, Ashely Luo

## UIN: 
xl3035, hl3536

