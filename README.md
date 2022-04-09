# bikesharing
## Overview of the analysis
This project is to break down, analyze, and visualize the use of citi bikesharing services in New York City in August 2019, so to provide useful information for establishing a similar bike-sharing program in Des Moines. The data is from the Citi bike system data page. I will use Python and Tableau to visualize the data, giving a basic portrait of bike-sharing customers and the possible ideal location to place bikes.

## Results
- From [The checkout times for users](https://public.tableau.com/app/profile/ziwen.lyu/viz/CheckoutTimesforUsers_16494768152590/CheckoutTimesforUsers?publish=yes) we can know that, most of users are using bike-sharing services within 40 minutes, indicating that they travel by bikes for short trips. Given the average speed of riders is 15 mph, most citi bike users travel within 10 miles.

- By breaking down the data by gender, from the chart [The checkout time by gender](https://public.tableau.com/app/profile/ziwen.lyu/viz/CheckoutTimesbyGender_16494768714760/CheckoutTimesbyGender?publish=yes), there's no difference in trip duration among genders. And also, the number of male users are much more than female users.

- If we see the [Trips by Weekday for Each Hour](https://public.tableau.com/app/profile/ziwen.lyu/viz/TripsbyWeekdayforEachHour_16494769207990/TripsbyWeekdayforEachHour?publish=yes), it is noted that many people using sharing bikes from 6am to 9am and from 4pm to 7pm during weekdays, suggesting that the majority of our users using bikes to commute. 

- By adding gender into the graph [Trips by Gender (Weekday per Hour)](https://public.tableau.com/app/profile/ziwen.lyu/viz/TripsbyGenderWeekdayperHour_16494769669400/TripsbyGenderWeekdayperHour?publish=yes) to compare, it shows no difference in using behavior. 

- Also, if we break down the data by user types, from the chart [User Trips by Gender and Weekday](https://public.tableau.com/app/profile/ziwen.lyu/viz/UserTripsbyGenderandWeekday_16494770117450/UserTripsbyGenderbyWeekday?publish=yes), both male and female users are more likely to subscribe the citi bike sharing service as long-term users. We can see that the majority of loyal customers are males and the most often time they will ride a bike is Thursday and Friday.   

For a more concise story version to visualize user portrait and bike using duration access here: [Bike placement and target customers](https://public.tableau.com/app/profile/ziwen.lyu/viz/Bikesharingtargetcustomersandbikeplacementanalysis/Bikeplacementandtargetcustomers?publish=yes)

## Summary
From the analysis, the majority of citi bike sharing customers are: males who commute through bikes on weekdays, usually travel within 40 mins or 10 miles, and prefer to subscribe services. This means that the bike-sharing program should target those kind of customers to market and advertise. Also, the program manager should consider place more bikes near office buildings (within 10 miles) to attract more commuters to ride bikes. 
For better decision-making in targeting customers and identifying bike placement, I suggest:
- visualize the start locations and end locations on maps and show their using frequency by the count of trips.
- visualize the relation of user birthdate and the count of trips. 
