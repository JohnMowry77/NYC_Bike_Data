# tableau_challenge

# New York City Bike Data Analysis

## Background

![Citi-Bikes](Images/citi-bike-station-bikes.jpg)

Congratulations on your new job! As the new lead analyst for the [New York Citi Bike](https://en.wikipedia.org/wiki/Citi_Bike) Program, you are now responsible for overseeing the largest bike sharing program in the United States. In your new role, you will be expected to generate regular reports for city officials looking to publicize and improve the city program.

Since 2013, the Citi Bike Program has implemented a robust infrastructure for collecting data on the program's utilization. Through the team's efforts, each month bike data is collected, organized, and made public on the [Citi Bike Data](https://www.citibikenyc.com/system-data) webpage.

However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. City officials have a number of questions on the program, so your first task on the job is to build a set of data reports to provide the answers.

## Task

**Your task in this assignment is to aggregate the data found in the Citi Bike Trip History Logs and find two unexpected phenomena.** 

**Design 2-5 visualizations for each discovered phenomena (4-10 total). You may work with a timespan of your choosing. Optionally, you may merge multiple datasets from different periods.** 

**The following are some questions you may wish to tackle. Do not limit yourself to these questions; they are suggestions for a starting point. Be creative!**

## Hypothesis
 * We can expect 2021 April/May data to have higher bike trips and for locations to be in the middle of the city. 
 * Today, what are the top 10 stations in the city for starting a journey in 2020 vs 2021? (Based on data, why do you hypothesize these are the top locations?)
 	* Results show densely populated urban areas have seen a comeback as ridership has increased dramatically compared to last April. 

* Today, what are the top 10 stations in the city for ending a journey in 2020 vs 2021? (Based on data, why?)
	* Results show Central Park and other areas sensitive to economic foot traffic have seen a bounce back as several new stations were in the top 10 for April 2021 compared to April 2020. 

* What is the starttime in 2020 compared to 2021?
	* Come back, start time appears to be incorrectly pulled. 

* What is the stoptime in 2020 compared to 2021?
	* Come back, stop time appears to be incorrectly pulled. 

## Method
* Utilize Tableau Desktop to analyze ridership data, specifically the top 10 starting and ending locations for April 2020 compared to April 2021. In addition, compared the start time and end time for the same year over year comparison. Created a series of maps with colored cirlces for top 10 locations, starting and ending locations. Created a series of bar charts comparing the top 10 locations for starting and ending locations. Created a bar chart comparing the top 10 start to end stations for April 2020 compared to April 2021. Created a line chart comparing the starting time and ending time for April 2020 compared to April 2021. 

* Screenshots of each page from Tableau Public, saved as png files. Created a new index.html for each png and utilized bootstrap Navbar to display each png. 


## Data Sources
* 202004-citibike-tripdata.csv
* 202104-citibike-tripdata.csv

