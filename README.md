# tableau-challenge
Analysis of COVID-19 effects on NYC Citi Bikes

 [Tableau Public Workbook](https://public.tableau.com/profile/hchuhtala#!/vizhome/FinalCitiBikeMarch2019vs2020Analysis1/Story?publish=yes). <br>

New York City imposed a strict lockdown in March 2020 in response to the COVID-19 outbreak there. People were asked to stay in their home unless they were an essential worker or had an essential trip. Another piece of it, released March 8th, included guidelines to commuters to bike or walk when possible and avoid packed subway cars possibly by taking the bus instead. The publicly available data from CitiBike NYC and Metro Transit Authority from March 2019 and March 2020 were compared, and any resulting differences were attributed to COVID-19. Analysis was done to determine if Citi Bike usage and trip locations were affected and if Citi Bike acted as a substitute for subway and bus rides. <br>
•	Hypothesis: Citi Bike usage in March 2020 would be less than March 2019.<br>
o	Number of rides spiked between March 8th and 10th, then dipped below 2019 levels. <br>
o	Day of the week could confound the year to year comparison <br>
	Would expect 27% of trips on weekends, if evenly distributed <br>
	Looking week by week controls for this better than a month-long summary <br>
o	There is a peak at 8 am and again 5-6 pm for rush hour with 2020 numbers being on average lower than 2019 <br>
	Looking at each week, the morning rush hour peak disappears as 2020 progresses<br>
•	Hypothesis: COVID-19 changed the location of the most used bike stations throughout the day. <br>
o	There are many housing units in all areas with Citi bike stations. <br>
o	There are more stations with 200 or more rides/ hour during rush hours <br>
o	There are more high use stations in 2019 than 2020<br>
o	The general trend of high use stations being in Manhattan is consistent over the years<br>
•	Hypothesis: To avoid enclosed public transportation, people chose to Citi bike instead. <br>
o	Subway has the most riders followed by buses. Citi bikes are at very most 6% of the total rides<br>
o	Subway and buses only saw decreased ridership, while Citi bikes saw an increase from March 8th to 12th and again the 13th to 15th.<br>
o	During this period Citi bike could have been used as a substitute for subway or bus but during other periods there is no evidence of this.<br>
Data Sources: https://new.mta.info/coronavirus/ridership  https://www.citibikenyc.com/system-data <br>
https://www.nbcnewyork.com/news/local/nyc-issues-new-commuter-guidelines-to-combat-coronavirus-spread/2317584/

# Background
<p>New York City imposed a strict lockdown in March 2020 in response to the COVID-19 outbreak there. People were asked to stay in their home unless they were an essential worker or had an essential trip. Another piece of it, released March 8th, included guidelines to commuters to bike or walk when possible and avoid packed subway cars possibly by taking the bus instead. The publicly available data from CitiBike NYC and Metro Transit Authority from March 2019 and March 2020 were compared, and any resulting differences were attributed to COVID-19. Analysis was done to determine if Citi Bike usage and trip locations were affected and if Citi Bike acted as a substitute for subway and bus rides.</p>
 
# Data Sources
* [**MTA Ridership Data**](https://new.mta.info/coronavirus/ridership )
* [**Citi Bike Data**](https://www.citibikenyc.com/system-data)
* [**NBC NY News Article**](https://www.nbcnewyork.com/news/local/nyc-issues-new-commuter-guidelines-to-combat-coronavirus-spread/2317584/)

# Analysis
* Hypothesis: Citi Bike usage in March 2020 would be less than March 2019.
 * Number of rides spiked between March 8th and 10th, then dipped below 2019 levels.
 * Day of the week could confound the year to year comparison 
* Hypothesis: COVID-19 changed the location of the most used bike stations throughout the day.
 * There are many housing units in all areas with Citi bike stations.
 * There are more stations with 200 or more rides/ hour during rush hours
 * There are more high use stations in 2019 than 2020<br>
 * The general trend of high use stations being in Manhattan is consistent over the yearsFit ML models from scikit-learn 
* Hypothesis: To avoid enclosed public transportation, people chose to Citi bike instead.
 * Subway and buses only saw decreased ridership, while Citi bikes saw an increase from March 8th to 12th and again the 13th to 15th.
 * During this period Citi bike could have been used as a substitute for subway or bus but during other periods there is no evidence of this.

