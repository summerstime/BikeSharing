# Bike Sharing in Des Moines, IA

## Objective
* This project is to analyze New York City's Citibank bike share database to help determine the viability of having a similar bike sharing business in Des Moines, IA.

### Analysis
* The data was contained in a csv file with the trip duration column in a format that needed to be changed to datetime. This was done with Python and Jupyter Notebook.
* After the correction the data was exported to a new file and then loaded into Tableau.
* The following worksheets have been created to review different aspects of the data:
- Checkout Times for Users
	- Most active time for checkout out a bike is within the first hour. 
- Checkout Times by Gender
	- The distinction of gender shows that males are the majority of users and tend to have longer trip durations.
	- ![Checkout Gender](https://github.com/summerstime/BikeSharing/blob/main/Images/CheckoutGender.png)
- Trips by Weekday per Hour
	- The heatmap shows the majority of activity is during the week at about 8am and 5 to 7pm. Saturday from 11am to 6pm is also very popular.
	- ![Trips Weekday by Hour](https://github.com/summerstime/BikeSharing/blob/main/Images/TripsWeekdayHr.png)
- Trips by Gender (Weekday per Hour)
	- This heatmap shows a similar result as the prior except it breaks it down by gender.
	- ![Trips Weekday by Gender](https://github.com/summerstime/BikeSharing/blob/main/Images/WeekdayGender.png)
- User Trips by Gender by Weekday
	- This heatmap shows that most users are male subscribers.
	- ![Trips Weekday by User](https://github.com/summerstime/BikeSharing/blob/main/Images/UserWeekday.png)
- Starting and Stopping Stations
	- The combined worksheets show the different stations around the city. There are color and size distinctions for the more active sites.
	- ![Starting and Stopping Stations](https://github.com/summerstime/BikeSharing/blob/main/Images/StartStopStations.png)
- Birth Year
	- This bar graph shows the birth year of users based on gender. The highest point shows that a majority of users are older than 30. The results display as a skewed bell curve.
	- ![Des Moines Birth Year](https://github.com/summerstime/BikeSharing/blob/main/Images/BirthYear.png)
- Popular Stations
	- This is a comparison of the Top 10 Starting Stations and their Top 5 Ending Stations. It shows the most active stations and also provides User Type.
	- In the dashboard, it shows the top 10 starting stations and the top 5 ending stations.
	- This helps determine where the surplus and shortage of bikes could be throughout the city.
	-![Popular Stations](https://github.com/summerstime/BikeSharing/blob/main/Images/PopularStations.png)

* From some of those worksheets, a dashboard was created. This dashboard focusses on the activity of the system, users (age, gender, subscriber), station popularity, time (weekday, hour, duration).
![NYC Bike Share Dashboard](https://github.com/summerstime/BikeSharing/blob/main/Images/Dashboard.PNG)


#### Des Moines Data
* Data about Des Moines was also gathered to compare and contrast the population in the city.
	- This website shows the age group in the city is within a similar range as the users in NYC.
[Des Moines Stats](https://censusreporter.org/profiles/16000US1921000-des-moines-ia/)

* The number of bikeable trails in the city must also be considered.
	- This website shows many available trails to sustain a bike sharing option for users.
[Des Moines Trails](https://dmampo.maps.arcgis.com/apps/webappviewer/index.html?id=c48776f60395490eb3029f5b29fc7b88)

## Summary
* In summary, the data from NYC provides some guidelines as to the popularity of bikesharing and who is most likely to utilize the system. For NYC, male subscribers over the age of 30, getting to and from work during the week and most hours on Saturday appear to be the most active.  [Bike Share Dashboard on Tableau Public](https://public.tableau.com/views/Mod14Challenge-BikeShareNYC/AllDash?:language=en-US&:display_count=n&:origin=viz_share_link)
* Suggestions for more analysis will be to focus on Des Moines. The age profile appears to be similar and the city has many trails. The next question is, how are the trails being utilized, who utilizes them, when are they utilized, and can the bike system be used as a transporation method to and from work?
* Combining the results from those questions with the results from NYC, will provide a more rounded look at the viability. Just because something works in NYC doesn't mean it will work in other locations. That needs to be the next focus of the investigation.





