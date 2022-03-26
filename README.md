# Citi BikeShare Analysis
Using a data visualization software called Tableau to present a business proposal for a bike-sharing company start-up in Des Moines, IA. This is accomplished by importing, styling, and portraying data accurately, and ultimately creating worksheets, dashboards, and a story to visualize key data from a New York Citi Bike dataset to present to a group of investors.


## Overview of the Analysis
![citi_bike](https://user-images.githubusercontent.com/94148420/159907840-fed544f3-706d-4896-bc58-13151541cecf.jpg)

After returning from an amazing trip to New York City, Kate thinks it might be a good idea to explore a bike share project for her home town of Des Moines, IA.  She enjoyed using the Citi BikeShare while on her vacation to explore New York City and thinks there is a potential business case for Des Moines.  She asks for my assistance to prepare a presentation for a potential angel investor for this venture.

Kate suggests that I use publically available Citi Bike data in preparing the presentation.  Tableau Public will be used to create the data visualizations for the business proposal pitch to the investor group.  Caution must be exercised with this project because Des Moines is no New York City!  The data selected for this presentation was from August 2019.  It is believed that Citi Bike traffic and usage would be heaviest during the summer season.

It will take a combination of my data expertise and critical thinking skills and Kate's salesmanship to convince this investor group that this is a viable business proposal.

### Resources
**Code:**
* NYC_CitiBike_Challenge.ipynb

**Data Source**
* Data downloaded from Citi Bike System Data Page:
  
  https://s3.amazonaws.com/tripdata/201908-citibike-tripdata.csv.zip
  

**Software/Data Tools:**
* Tableau Public 2021.4.4
* Jupyter Notebook
* Pandas 1.3.5
* GitHub


## Results
### Citi BikeShare Analysis Tableau Public Link

Link:  https://public.tableau.com/app/profile/john.beauchamp/viz/CitiBikeShareAnalysis/Story1#2

### Dashboard for Key Metrics

![citi_bike_dashboard](https://user-images.githubusercontent.com/94148420/160211462-dd8a7224-ae95-46ae-b583-11d725325b04.PNG)

A **dashboard** was created to display key metrics including:
* Number of Trips = 2.3 million trips in August
* Customer Type
    * Customer = 19%
    * Subcriber = 81%
* Gender Breakdown
    * Female = 25.1%
    * Male = 65.3%
    * Unknown = 9.6%

### Check Out Times for Users
![check_out_times_for_users](https://user-images.githubusercontent.com/94148420/160246367-68a9a80e-32a6-42ce-b27d-7d4e0bb77fcc.PNG)

Bike trips are of relatively short duration.  99% of the trips taken are below 60 minutes, where as 77% of the trips are under 20 minutes.  This would speak to bikes being readily available and/or short wait times, thus enhancing the customer experience.

### Check Out Times by Gender
![check_out_times_by_gender](https://user-images.githubusercontent.com/94148420/160246572-c9200ca7-5fc1-4603-b7e1-0399a0f70e2b.PNG)

Gender breakdown:  65.3% are male, 25.1% are female, and 9.6% are unknown.

### Trips by Weekday for Each Hour
![trips_by_weekday_for_each_hour](https://user-images.githubusercontent.com/94148420/160246680-2328f25c-c4d6-4fc5-a7f5-d7f0d7521f64.PNG)

This heatmap really lights up during the weekday in the morning from 7AM - 9AM and in the evening from 5PM - 7PM indicating riders are commuting to and from work.  Weekend ridership is fairly steady from 10AM - 5PM.

### Trips by Gender (Weekday per Hour)
![image](https://user-images.githubusercontent.com/94148420/160246757-b68a6bd8-de17-47a4-a301-9609e2c9d274.png)

Males make up the vast majority of the ridership, including the commute to and from work and riding on the weekends.

### User Trips by Gender by Weekday
![user_trips_by_gender_by_weekday](https://user-images.githubusercontent.com/94148420/160246818-b3fe9755-9d2d-4e4f-a6a4-3b4ca070de29.PNG)

Male subcribers are the prominent user type for Citi Bike Share.

### Top Starting Location
![top_starting_location](https://user-images.githubusercontent.com/94148420/160246885-f30cfdc6-51ef-4279-bd64-91cc70b1cbac.PNG)

Business locations provide top areas to set up bike stations.

### August Peak Hours
![august_peak_hours](https://user-images.githubusercontent.com/94148420/160247086-6f954493-af9c-4904-a151-570e557de52c.PNG)

Ridership is greatest during the morning and evening commute times.  Best to perform bike maintenance between 2AM - 4AM.

## Summary
The following is a summary of the August 2019 Citi BikeShare data analysis using Tableau Public:
* In August alone, 2.3 million trips were taken.
* 81% of users are **SUBSCRIBERS**, whereas 19% are **CUSTOMERS**
* Ridership is predominantly male at 65.3%, followed by females at 25.1%, and 9.6% are unknown.
* Trip duration is relatively short with 99% under 60 minutes and 77% less than 20 minutes.
* Data indicate that the bikes are primarily used for commuting to and from work.  The busiest riding times are during the work week in the morning from 7AM to 9AM and in the evening from 5PM to 7PM.
* Bike traffic is heaviest in the business district.

There is a good business case that the DM BikeShare business proposal would be a successful business venture based on the NYC Citi BikeShare Analysis.  Lessons learned from the Citi BikeShare analysis to be applied and scaled to DM BikeShare would include:
* Locate bike stations in and in proximity to the business district.
* Market the program to potential **SUBSCRIBERS**.
* Target the program to **COMMUTERS** traveling to and from work.

### Additional Considerations for DM BikeShare
* Assess the marked *Bike Routes* in and around Des Moines for additional bike stations.
* Perform and analysis with spring and fall data, the ridership will be theoretically less.
* Conduct a complete weather analysis for the entire year.
* Conduct an analysis on potential tourism bikeshare users.
* Consult with the Des Moines Chamber of Commerce on the business proposal.


