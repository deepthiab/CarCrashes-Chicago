# Project5: Chicago Car Accidents Data 2019


### Overview
- Discussion of how to structure the data and use of like term assignments
- Consider types of classifiers relevant and applicable
- Clean data / perform EDA + Data Visualization / Heat-map for feature selection /  Revisions
- Export CSV for group work sync
- Divide classifier modeling load / test models / handle class imbalances when necessary
- Test different classifiers and measure performance based on agreed upon metrics
- Discuss results and plan out next steps / Make recommendations

### Problem Statement
Analyzing data from car crashes in Chicago in 2019 to determine what are the highest contributing factors to a severe injury in result of a car crash. 
Using these contributing factors to make recommendations for local drivers and local government to make the roads safer, as well as to make recommendations 
for self-driving car companies.

### Data Dictionary
|Feature|Description|
|---|---|
|SEVERE_INJURY|Whether there was a severe injury sustained by any person involved in the crash or not|
|RD_NO|Chicago Police Department report number|
|POSTED_SPEED_LIMIT|Posted speed limit, as determined by reporting officer|
|NUM_UNITS|Number of units involved in the crash. A unit can be a motor vehicle, a pedestrian, a bicyclist, or another non-passenger roadway user|
|CRASH_HOUR|The hour of the day component of CRASH_DATE|
|CRASH_DAY_OF_WEEK|The day of the week component of CRASH_DATE (Sun=1, Mon=2, Tue=3, Wed=4, Thu=5, Fri=6, Sat=7)|
|CRASH_MONTH|The month component of CRASH_DATE|
|DEVICE_CONDITION|Condition of traffic control device, as determined by reporting officer|
|LIGHTING_CONDITION|Light condition at time of crash, as determined by reporting officer|
|FIRST_CRASH_TYPE|Type of first collision in crash|
|TRAFFICWAY_TYPE|Trafficway type, as determined by reporting officer|
|ALIGNMENT|Street alignment at crash location, as determined by reporting officer|
|ROADWAY_SURFACE_COND|Road surface condition, as determined by reporting officer|
|ROAD_DEFECT|Road defects, as determined by reporting officer|
|CRASH_TYPE|A general severity classification for the crash. Can be either Injury and/or Tow Due to Crash or No Injury / Drive Away|
|PRIM_CONTRIBUTORY_CAUSE|The factor which was most significant in causing the crash, as determined by officer judgment|


### Brief Summary of Analysis
We as a team had a goal of discovering relevant and applicable insights into the world of vehicular accidents. 
With these insights, we hope to inform local governments with information that could lead to better commuting recommendations, 
preventative laws, and data driven policies. We also see a great deal of potential application of our classifiers with private enterprise 
in the driverless vehicle industry, regarding how to build better predictive driving models. The machine learning classifiers that we have 
developed could contribute to faster reaction times, or when accidents are inevitable, to intentionally make decisions that would reduce the 
accidents fatality or injury rate based on the accident data the classifier was taught on. The ability for self driving vehicles to make decisions 
that reduce lethality is invaluable, and we see this work potentially contributing to this growing industry.

### Recommendations
We found that the most crashes take place at 3pm, 4pm, and 5pm, presumably related to rush hour traffic. A strong recommendation would be to try to 
avoid being on the road at these times, or to carpool so minimize the amount of cars on the road. The most fatalities were attributed to weather. 
When the weather is severe, it would be wise to stay off the road or to wait for conditions to improve to increase commuter safety and chances of survival.
Local governments and agencies could enforce stricter policies regarding Equipment - Vehicle Condition, the second leading cause of fatalities.
Third most fatalities were attributed to failure to reduce speed to avoid crashing. This is likely related to texting and driving, or driving while distracted. 
Local communities could host informational seminars on phone features like Do Not Disturb While Driving, in order to reduce fatal accidents caused by texting 
and driving. While outside features are absolutely a contributor,  a significant amount of the crashes are essentially caused by operator error. 
The focus should be on creating software, features, and policies that encourage more responsible driving behaviors.
We plan to implement neural nets and other SVM variants to test other model performance. 
We would also like to compare year 2019 to year 2020 to evaluate how covid has affected accident rates

### Data Sources
Data Source: https://data.cityofchicago.org/Transportation/Traffic-Crashes-Crashes/85ca-t3if
