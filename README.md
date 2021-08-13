#### Bluecar Data Analysis

#### Introduction
The objective of this analysis is to identify the most popular hour of the day for picking up a shared electric car (Bluecar) in the city of Paris over the month of April 2018 by processing stations data to understand electric car usage over time.
#### Data Analysis Format
These are the steps taken to perform the analysis:  
1.  Arrange the data in chronological order i.e. Sort the data in ascending order of date and time. 
2.  Filter out the observations in the City of Paris.
3.  Compute Blue car usage by finding the difference between successive observations of the Bluecar counter column.i.e (previous-current)
*   Negative values show that a car was picked
*   Zero shows that there was no change
*   Positive values show that a car was returned
4. To answer the research question we focus on the negative usage values i.e BluecarUsage<0.
5. Then we group the list by time,
6. And count the observations that meet the criteria BluecarUsage<0
7. Then order that in descending order.
#### Technology & Framework Used
Python, Ipynb, Googlecolab

##### By JoyW 
##### 13/08/2021
