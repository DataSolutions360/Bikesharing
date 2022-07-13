# Bikesharing

## Purpose

The purpose of this activity is to provide investors with data that shows that a bike-sharing program in Des Moined IA is a solid business proposal. In order to solidify this proposal, one of the stakeholders would like to see a complete bike trip analysis. For this chalenge, I used Pandas to change the "tripduration" colum from an integer to a datetime datatype. Then, with the new DataFrame I:

- Showed the length of time that bikes are checked out for all riders and genders.

- Showed the number of bike trips for all riders and genders for each hour of each day of the week.

- Showed the number of bike trips for each type of user and gender for each day of the week.

This was done via visualizations with Tableau in order for others to better understand the data I present to them.

## Trip Duration becomes a DataFrame for further analysis

![Citibike_df](https://user-images.githubusercontent.com/8845050/178769097-814e0029-b1df-46fd-89a5-a3f2816f4ff1.PNG)

## Create Visualizations for Trip Analysis

![Peak_Hours](https://user-images.githubusercontent.com/8845050/178778093-9e509fa5-90ce-4115-b31e-628c143a030a.PNG)

## Checkout Times for Users

![Checkout_Times_for_Users](https://user-images.githubusercontent.com/8845050/178778914-fae8b1e0-be6d-48f2-a3b5-d67708bbf6fe.PNG)

## Checkout Times by Gender

![Checkout_Times_by_Gender](https://user-images.githubusercontent.com/8845050/178779073-523c3975-d0f3-4dec-b689-6f83b2e22a7a.PNG)

## Trips by Weekday

![Trips_by_Weekday_for_each_hour](https://user-images.githubusercontent.com/8845050/178780319-059e0ec3-55f8-4eff-bbf2-08a931d36800.PNG)

## Trips by Gender (Weekday Per Hour)

![Trips_by_Gender_weekday_per_hr](https://user-images.githubusercontent.com/8845050/178780369-21db150d-5e4a-4cbb-a7cc-2408b739c3b1.PNG)

## User Trips by Gender by Weekday

![User_Trips_By_Gender_by_Weekday](https://user-images.githubusercontent.com/8845050/178780533-c6351dee-692e-48f5-b1cc-9b41f3635431.PNG)

## Starting Locations

![TOP_STARTING_LOCATIONS](https://user-images.githubusercontent.com/8845050/178792285-9ddcde83-3cd2-44dd-b38f-396b4c71af2f.PNG)

## Create a Story

For Deliverable 3, we created a story in Tableau which displayed insights and interpretations to the data/visualization that you have seen above, and supplements the baseline data to "bring it all together".

## Story

![story](https://user-images.githubusercontent.com/8845050/178803453-0464ebd5-8897-4b53-b3b6-ee7380953869.PNG)

Based on the resulted gathered during the analysis, the data presents peak hours and some very correlated aspects, such as gender, commuter hours to/from work, and the day of the week.  This may be helpfuil when deciding what bike frame to offer, what PSI for tires to maintain, given the assumption that males weigh more than females, or even which gender prefers the current model of bike being offered now.

### Peak Hours

As expected, from 7am to 9am, commute TO work is probably the peak, as well as commuting FROM work(4pm to 6pm).  In addition, the majority of the bikes are not used for a very long time. Mainly just under 10 minutes which means that the users of the bikes most liekly live close to where they work but not too close where they can just walk (or they just choose to se the bikes regardless). During the week, the bikes are heavily used from Monday-Friday which also implies that the bikes are mainly used to help individuals get to and from work.

### Other Aspects to Analyze

In addition to having the data presented now. I beleive the information can be respresented in other ways as well. One visualization that comes to mind if a simple pie chart showing the percentages of the genders. Even though we already know that men are the majority of users in this dataset, it would be insightful to see how much (percetnage wise) they cover. Going off this first suggestion, another good visualization that can be used is another pie chart but instead of showing the gender, it can show the percentage of subscribers compared to customers. I made a graph showing the User Trips by Gender by Weekday which showes the subscriber in color shading form. having another pie chart showing the actual percentages of subscribers and customers can highlight the amount of subscribers across all genders and can help in showing the majority of the kinds of users.


