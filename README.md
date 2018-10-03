# Flight-Delay-Warning-System
Exploratory Data Analysis (EDA) performed on the On-Time Performance of Airlines and Predict if a flight arrives late at its destination using Supervised Machine Learning Algorithms.

## Objective:
The task is - given the scheduled/actual departure time and delays, predict whether a flight will get delayed or not. Delay threshold used for this dataset is 0 minutes (That is, if a flight is even 1 minute over its scheduled arrival time it will be classified as delayed).

## Dataset:
- **Procured from:** [Bureau of Transporation Statistics](https://www.bts.gov/explore-topics-and-geography/topics/time-data). It can be obtained as .CSV files from the Bureau of Transportation Statistics Database, and requires you to download the data month by month.
- **Time-range:** January 2015 to December 2015
- **Contains** around 6 Million rows of flight information. 
- **Raw-data information:**
 on-time arrival data for non-stop domestic flights by major air carriers, and provides such additional items as departure and arrival delays, origin and destination airports, flight numbers, scheduled and actual departure and arrival times, cancelled or diverted flights, taxi-out and taxi-in times, air time, and non-stop distance.
 
 ## Summary of Results
 #### Insights from EDA
- Flight Delay Distribution: Not Delayed = 63.48% | Delayed = 36.52%
- Average Arrival Delay is 33 minutes.
- Average Air Time for delayed flights is higher than non-delayed flights. 
- Average Distance traveled by delayed flights is less than non-delayed flights.
- Much of the delay time (~98.5%) is observed within 2 standard deviations (139 minutes).
- WN, DL, AA, OO, EV, UA have the most number of flights during the year.
- March, June and July seem to be the busiest months.
- 9 AM to 9 PM seems to be the busiest time frame in a day.

#### Insight from Machine Learning Models
- **Logistic Regression:** Training Accuracy = 78.742% | Test Accuracy = 80.663%
- **Decision Tree Classifier:** Training Accuracy = 99.981% | Test Accuracy = 99.993%
- **Random Forest Classifier:** Training Accuracy = 98.063% | Test Accuracy = 98.061%
