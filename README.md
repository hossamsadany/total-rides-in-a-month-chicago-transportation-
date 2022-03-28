# total-rides-in-a-month-chicago-transportation-
A python project using pandas to explore chicago puplic transportation system on weekdays of july in wilson station

# project overveiw
This project focuses on pandas library usage and simple statistics methods to perform descriptive analysis on the chicago transportations system data and mergeing methods between 3 tables of data to display information such as the total rides of a month.

# output
my goal is to find the total number of rides provided to passengers passing through the Wilson station when riding Chicago's public transportation system on weekdays in July. Luckily, Chicago provides this detailed data, but it is in three different tables. output works on merging these tables together to answer the question. then I added another criteria to filter any other station , month , day . finally I create a power pi file using the saved csv file to present a map with stations and size of rides filtered by the day type

# Requirements
Language: Python 3.6 or above
Libraries: pandas
# Project Data
- ridership , calender , stations pickle files - Stored in the data folder.
- the ridership file is the dataset containing station_id, year, month, day , rides columns only .
- calender file dataset contatining calender of 2019 contains year , month ,day, day_type columns.
- station file dataset containing station_id , station_name, location.
- files loaded from chicago transportation system
