# Bike Sharing in Des Moines, IA

## Objective
* This project is to utilize the Citibank Bike data to help determine the viability of having a similar bike sharing business in Des Moines, IA.
* The data analyzed is from New York City's Citibank bike share database. The analysis of this data is to help determine if starting a similar bike share in Des Moines, IA is a viable business plan.

### Analysis
* The data was contained in a csv file with the trip duraition column in a format that needed to be changed to datetime. This was done with Python and Jupyter Notebook.
* After the correction the data was exported to a new file and then loaded into Tableau.
* The following worksheets have been created to review different aspects of the data:
** Checkout Times for Users
	- Most active time for checkout out a bike is within the first hour. 
** Checkout Times by Gender
	- The distinction of gender shows that males are the majority of users and tend to have longer trip durations.
** Trips by Weekday per Hour
	- The heatmap shows the majority of activity is during the week at about 8am and 5 to 7pm. Saturday from 11am to 6pm is also very popular.
** Trips by Gender (Weekday per Hour)
	- This heatmap shows a similar result as the prior except it breaks it down by gender.
** User Trips by Gender by Weekday
	- This heatmap shows that most users are male subscribers.
** Starting stations
	- This shows different starting points around the city.
** Stopping stations
	- This shows different ending/drop-off points around the city.
** Birth Year
	- This bar graph shows the birth year of users based on gender. The highest point shows that a majority of users are older than 30. 
** Popular Stations
	- This is a comparison of the Top 10 Starting Stations and their Top 5 Ending Stations. It shows the most active stations and also provide User Type.
* From some of those worksheets, a dashboard was created. This dashboard focusses on the activity of system as whole, users (age, gender, subscriber), station popularity, time (weekday, hour, duration).
[Des Moines Dashboard](https://github/images.....)

####Des Moines Data
* Data about Des Moines was also gathered to compare and contrast the population in the city.
* This website shows the age group in the city is within a similar range as the user in NYC.
[Des Moines Stats](https://censusreporter.org/profiles/16000US1921000-des-moines-ia/)

* The number of bikeable trails in the city must also be considered.
[Des Moines Trails](https://dmampo.maps.arcgis.com/apps/webappviewer/index.html?id=c48776f60395490eb3029f5b29fc7b88)

* In the dashboard, it shows the top 10 starting stations and the top 5 ending stations.
* This helps determine where the surplus and shortage of bikes could be through the city.

[Bike Share Dashboard](https://public.tableau.com/views/Mod14Challenge-BikeShareNYC/AllDash?:language=en-US&:display_count=n&:origin=viz_share_link)

