 **Uber project**
   Uber needs to identify the reasons for driver churn.
   I want to analyze driver churn and examine the differences between drivers who leave the service and those who stay. I aim to formulate and test hypotheses and identify groups of drivers most susceptible to churn. Based on the results, I will draw conclusions on how to improve the service.


**Data Description:**

 - city – city
 - phone – the primary device used by the driver
 - signup_date – account registration date (YYYYMMDD)
 - last_trip_date – date of the last trip (YYYYMMDD)
 - avg_dist – average distance (in miles) per trip in the first 30 days after registration
 - avg_rating_by_driver – average rating given by the driver for trips
 - avg_rating_of_driver – average rating received by the driver for trips
 - surge_pct – percentage of trips taken with a surge multiplier >1 (likely during peak hours)
 - avg_surge – average surge multiplier for all trips taken by the driver
 - trips_in_first_30_days – number of trips completed by the driver in the first 30 days after registration
 - luxury_car_user – TRUE if the driver used a premium car in the first 30 days
 - weekday_pct – percentage of the user's trips taken on weekdays


**In this project:**
 - I examined whether there are differences in churn rates across different cities.
 - I identified differences in activity levels during the first 30 days after registration among drivers from different cities.
 - I analyzed whether churn could be related to activity levels during the first 30 days after registration.
 
**Findings:**
 - We found statistically significant differences between platforms. More drivers leave the service on Android than those who stay. It is essential to determine the reason for this and address the issue.
 - We also identified statistically significant differences in churn rates between cities. In Astapor and Winterfell, more drivers leave than stay. It is necessary to delve deeper into the reasons behind this behavior.
 - Additionally, I discovered that drivers who churned were less active during their first 30 days after registration. Implementing initiatives to increase user activity during this period could help reduce churn, and this should be tested.
