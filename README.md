# bikesharing
Work with Tableau to present a business proposal for a bike-sharing company.
## Overview 

The purpose of this project is to present an analysis of the impacts and success of bikesharing in New York City.

The following questions were elaborated on to guide the project's analysis:
- What are the top bike stations in the city for starting a journey?
- What are the top bike stations in the city for ending a journey?
- How long are bikes checked out for all riders and genders?
- How many trips are taken by the hour for each day of the week for all riders and genders?
- A breakdown of what days of the week a user might be more likely to check out a bike by type of user and gender. 

[link to dashboard](https://public.tableau.com/views/NYCCitiBikeAnalysis_16699374940950/NYCCitiBikeAnalysis?:language=pt-BR&publish=yes&:display_count=n&:origin=viz_share_link)

## Resources 
- data: https://ride.citibikenyc.com/system-data (201908-citibike-tripdata.csv.zip)
- source: Pandas, Jupyter Notebook, Tableau.

## Results 
1. Top Starting Stations Locations

- There is a concentration of trips starting in the south of Manhattan, 
where there are many tourist places and big companies.


![NYC_Citi_Bike_Analysis](NYC_Citi_Bike_Analysis.png).



2. Top Ending Stations Locations

- There is the same concentration at the end of trips. 
Another reason for this concentration is this region's variety of bike lanes.


![NYC_Citi_Bike_Analysis1](NYC_Citi_Bike_Analysis1.png).


3. Checkout Time for Users

- Looking at how long the bikes checkout, based on the data, 
the maximum peak is for a period of fewer than 40 minutes.

![NYC_Citi_Bike_Analysis2](NYC_Citi_Bike_Analysis2.png).


4. Checkout Time by Gender

- Comparing the checkout of bikes by gender, it is still possible to observe a 
shorter period of 40 minutes. But there are fewer females and unknown riders.


![NYC_Citi_Bike_Analysis3](NYC_Citi_Bike_Analysis3.png).


5. Trips by Weekday per Hour

- There are two peak periods during weekdays. The first is in the morning, 
around 8 am, and the second peak is from 6 pm to 7 pm.


![NYC_Citi_Bike_Analysis4](NYC_Citi_Bike_Analysis4.png).


6. Trips by Gender (Weekday per Hour)

- As seen in graph 4, there are fewer women and unknown riders; this is clearer in 
this graph as there are no extreme peak times in these categories. As for Male riders, 
the peaks are still at 8 am and night from 6 pm to 7 pm.


![NYC_Citi_Bike_Analysis5](NYC_Citi_Bike_Analysis5.png).


7.User Trips by Gender by Weekdays

- And finally, in the last graph, it is possible to observe that subscribers have 
a significantly greater tendency to use bikesharing than customers.


![NYC_Citi_Bike_Analysis6](NYC_Citi_Bike_Analysis6.png).

## Summary 

After the analysis, it is possible to understand that bikesharing is a business opportunity, 
obviously, for the research to be more accurate, it is also necessary to analyze the city 
where the bikesharing will be applied.

Here are two suggested metrics for further analysis:

- Better understand the period of use of the bicycle until it needs maintenance, directly 
affecting the cost of the business and also the availability of bikes for customers.


- Another metric would be the city's geography, as this can change which bicycles can be available 
to the public. For example, conventional bicycles work in a flat town, while electric bikes are needed 
in a city with hills to improve the customer experience.


