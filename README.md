# bike-Sharing
# bikesharing

## Project Overview
Analyize the August, 2018 NYC bike-sharing dataset and create set of visualizations for a similar project in Des Moines. The visualizations were then used to create a business proposal in Tableau. 

## Resources
- Data Source: 201908-citibike-tripdata
- Software: Tableau, Jupyter Notebook, Python, Pandas

## Analysis
One of the key stakeholders would like to see a bike trip analysis. <br>

### Deliverable 1:
The dataset needed preparation upfront. Using Pandas, "tripduration" column datatype was changed from an integer to datetime. 
 ![Updated_dataframe](https://github.com/Quinneth/bike-Sharing/blob/main/updated%20data%20frame.png)<br>
 
### Deliverable 2:
Using Tableau, we created visualizations that show:<br>
- Length of time that bikes are checked out for all riders and genders
![All_users](https://github.com/Quinneth/bike-Sharing/blob/main/Checkout%20Times%20for%20Users.png)
![by_gender_users](https://github.com/Quinneth/bike-Sharing/blob/main/Checkoutbygender.png)

- Number of bike trips for all riders and genders for each hour of each day of the week
![Trips_per_day](https://github.com/Quinneth/bike-Sharing/blob/main/Trips%20by%20weekday:hr.png)
![Trips_per_day_gender]( https://github.com/Quinneth/bike-Sharing/blob/main/Trips%20by%20gender.png)

- Number of bike trips for each type of user and gender for each day of the week <br>
![User_Trips_gender](https://github.com/Quinneth/bike-Sharing/blob/main/User%20trips%20by%20gender%20weekday.png)<br>

### Deliverable 3:
Create story for results using 7 visualizations in Tableau Dashboard and report key outcomes. 
Link to dashboard [link to dashboard](https://prod-useast-b.online.tableau.com/#/site/quinnethd/workbooks/76738?:origin=card_share_link)

## Results
- Most riders are subscribers.
- Males are predominant users.
- Subscribers are bike sharing more than customers
- Most users checking out at 15 minutes or less.
- Males checkout duration peaks at 5 minutes; Female's at 7 minutes. This may be due to faster riding by males.
- Thursday sees peak usage. 
- Weekend sees higher trip duration. 
- The volumen of people using the same starting and ending locations indicate there are common destinations.
- The number of weekday rides peak in rush hour times. This could indicate that bike-sharing is a common transit method for commuiting to and from work. 

## Recommendations
The only way to properly evaluate this proposal would be to add additional resources. New York City is very different from Des Moines, Iowa. Analysis would involve determing if the Des Moines popultion lives within biking distance from a concentrated group of employers, bike path safety or availability, and revenue proceeds of custormers versus subscribers. 



