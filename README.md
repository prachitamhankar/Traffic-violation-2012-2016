# Traffic-violation-2012-2016
Thorough analysis of Traffic violation caused between years 2012-2016

## Motivation

Traffic Violations in the USA have increased in the past few years. A thorough study of these traffic violations is essential for traffic accident prevention and traffic offense management. In this project, I have studied the relationship between driver sex, age, ethnicity, type of vehicle, state in which driver license was issued, time of the accidents and type of violation. The aim is to predict the Traffic Violations for the year 2017 based on the dataset available from the years 2012- 2016. This can be used to increase cautions and help reduce the chance of occurrence. 

### Steps in the execution of this project

1) Data Extraction: The data is obtained from the following data source: [Kaggle - Traffic violations](https://www.kaggle.com/felix4guti/traffic-violations-in-usa)
2) Data Munging: The data was cleaned using python 
3) Data blending in Tableau 
4) Performing descriptive and predictive analysis on the data
5) Finding interesting insights by thorough analysis

## Goals of the Project

### Descriptive Analysis:

a) Visualization of State Wise analysis of data to represent number of traffic violation records based on specific time of the day in a particular year 

b) State Wise Analysis depicting the number of violations based on gender and ethnicity.

![image_descript](/images/1.png)

#### Tableau Skills:
1) Select a state on the map. The given state showcases the violations based on the gender and race. 

2) **Created Filters:** When a state is selected, the Year and the respective number of records are displayed on the dashboard. 

3) **Created Actions:** When we hover over a particular year we see the line graph changing as per the time of the day. 

4) We get the information when we select a state, which year was the one where the number of violations occurred were the maximum and what was the time of the day when the violations were at the peak. 

### Predictive Analytics:

Predicting the number of occurrences for each type of Violations in the year 2017 per quarter based on the data from 2012- 2016 in any selected state. 

![image_descript](/images/2.png)

#### Tableau Skills:

Here Animation is displayed on the dashboard. Once we play it changes the results of the number of charges every quarter over the years from 2012 to 2016 and at the end predicts the number of changes in the year 2017 quarter wise. 

Based on the year the most popular violation is also seen on the dashboard.

**Anomalous Behavior Insight:**

Maximum number of violations reported in a state is not same in the state in which the driver license was issued. For example when a state of OR (Oregon) is selected where the driver license was issued, rather than the number of records being maximum in OR(63), they were found to be maximum in the state of MD (127)

![image_descript](/images/3.png)


## Acknowledgments

* [US Bureau of Transportation](https://www.bts.gov/topics/airlines-and-airports/origin-and-destination-survey-data)
* [Kaggle - Traffic violations](https://www.kaggle.com/felix4guti/traffic-violations-in-usa)
