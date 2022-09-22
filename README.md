# Bikesharing

<b/>

## Project Overview:

<b>

Using `Tableau` to create a presentation and analysis to pitch to investors that a bike-sharing program for Des Moines is a solid business proposal. To solidify the proposal, some of the key stakeholders have requested to see a bike trip analysis of New York City where the same program has been successful. We are going to answer three main questions as well as provide other informative visualizations of the data to answer these questions. The dataset consists of a total of 2,343,246 recorded bike-shares.

<br>

[Link to Deployed Tableau Story](https://public.tableau.com/app/profile/dylan.brothers/viz/CitibikeStory_16635661142550/Zipcode_Top_Stations?publish=yes)

<br>

1. What is the length of time that bikes are checkout out for all riders and genders?
2. How many bike trips are recorded for all riders and genders for each hour of the weekday?
3. How many bike trips are recorded for each type of user and gender for each weekday?

<br>

<p align=center>
<img src=Images/trip_duration.png>

This graph answers the first question our investors have asked. The visualization suggests that `the average time bikes are checked out is between 6-7 minutes with Men as the user majority`.

<br>

<p align=center>
<img src=Images/trips_by_hour.png><img src=Images/trips_by_hour_usertype.png>

Bike Trips vary by the hour of day with the peak hours at `7am in the morning` and `between 5-6pm` in the evening. The above two graphs answer our second question.

<br>

<p align=center>
<img src=Images/trips_by_weekday.png><img src=Images/trips_by_weekday_2.png width=999>

This data provides the information we need to answer our third question. `Thursday` is the most popular day for bike rentals with a total of `353,508 rentals recorded`.

<br>

<p align=center>
<img src=Images/trips_by_usertype_pie.png>

There were `443,822 non-subscribed` and `1,899,424 subscribed` customers recorded. The bulk of customers are subscribed to the service.

<br>

<p align=center>
<img src=Images/top_10_start_stations.png>

This graph shows us the top ten start stations. `Pershing Square North` is the most popular station for bike rentals followed by `E 17th St & Broadway`.

<br>

<p align=center>
<img src=Images/trips_by_weekday_by_hour.png>

This visualization also shows that the peak hours are at 7am and between 5-6pm with the most rentals on Thursday.

<br>

# Final Result:

<p align=center>
<img src=Images/Final.png>

<br>

[Link to Deployed Tableau Story](https://public.tableau.com/app/profile/dylan.brothers/viz/CitibikeStory_16635661142550/Zipcode_Top_Stations?publish=yes)

`Please visit the Tableau Public link to interact with any graphs you've seen and more.`

<br>

## Summary:

Bike rentals vary by the hour of the day and are most popular at 7am and in the evening between 5-6pm. Rentals times vary between age, sex, weekday, and time of day with an average of only 5-6 minutes. The number of bike trips varies dramatically by the type of user (subscribed or unsubscribed) and whether the renter is male or female among other variables. There were 443,822 non-subscribed and 1,899,424 subscribed customers recorded. The bulk of customers are subscribed to the service. For further analysis, I have also included a graph showing the location of start stations by zip-code and a graph visualizing Trip Duration by age.

## Resources:

- Software:
    - `Tableau Desktop`
    - `Tableau Public`
    - `VS Code`
    - `Pandas`
    - `Anaconda`
    - `Jupyter Lab`

<br>

- Resources:
    - `citibike_AUG_2019.csv` (Generated with pandas from the `201908-citibike-tripdata.csv.zip` file found with the link below)
    - https://s3.amazonaws.com/tripdata/index.html
  
<br>

<b/>