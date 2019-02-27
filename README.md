Tableau :https://public.tableau.com/profile/akshata1035#!/vizhome/ChicagoCrimeAnalysis_15/Story1


I created some visualizations in tableau and created a story. I have published the workbook on Tableau public forum.(https://public.tableau.com/profile/akshata1035#!/vizhome/ChicagoCrimeAnalysis_15/Story1 ). The first in performing data analysis on any dataset is to look at the data and understand the data fields.
After understanding the dataset and fields, next step is to remove unnecessary data fields and null values. I have used Pandas and Numpy to perform these operations. 
After cleaning, the data set has 12 columns:
 1)	Date: Which has date and time when incident happened.
 2)	Block: Address where the incident happened.
 3)	Primary Type: Type of crime
 4)	Description: Brief description about crime
 5)	Location Description: Description of location where crime happened.
 6)	Arrest: Indicates whether an arrest was made.
 7)	Community Area
 8)	Year: This is derived column from date.
 9)	Day: This is also a derived column to get day of week from date.
 10)	Latitude: The latitude of the location where the incident occurred. 
 11)	Longitude: The longitude of the location where the incident occurred.
 12)	Location - The location where the incident occurred in a format that allows for creation of maps.
The next step is to research more about crime analysis and why it is important. It helps police officers have to search for ways to discover patterns and similarities between incidents for years.
Insights:
 1)	Crime over the years:
 ![Alt text](C:\Users\AKSHATA\Desktop\years.png?raw=true "Title")
 
    •	I overserved that crime rate has decreased over the years and for 2017 there is significate drop in crime count. As Chicago crime       department has adopted Data-driven policing which uses information from multiple sources to help police learn where crimes are     happening and where they are likely to happen. Also, in 2017 homicide rate has dropped by 10 %.

 2)	Crime over the months:
 
    •	Most of the crimes in Chicago has happened during July and August.
    •	Also, according to the annual National Crime Victimization Survey, crime increases in summer time. As temperature increases,    people drive out of door more and during day hours people spend most of the time outside which increases the crime. This rises the amount of people in public and the amount of time that homes are left empty. 

 3)	Day wise Crime count:
 
    •	After plotting graph using Matplotlib, I observed that most of the crimes in Chicago happened on Friday.
    •	As Friday is last working day, most people tend to go home late. Spend more times in outside. 

 4)	Top 5 crime location:
    •	In order to understand locations where most of the crimes happened I used value_counts() function to get top crime location in  Chicago 
 
    •	After plotting bar graph in tableau, I observed that most of the crimes happens on street, residence, apartments and sidewalk.
    •	This postulate my findings in point number 2.

 5)	Crimes per block
 
    •	After searching this location on internet, I found out that North state st and West terminal street are very close to downtown.  Chicago downtown has lots of attractive activities  so it gives opportunities to criminals to rob.
