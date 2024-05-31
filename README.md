# Indian-Airlines-Analysis
## Overview 
This analysis focuses on a dataset comprising various flight details including airline information, flight numbers, departure and arrival cities and times, stops, travel class, flight duration, days left until departure, and ticket prices. The analysis was conducted using Power BI to derive insights and trends from the data.

## Objectives of Analysis
- **Price Pattern Identification:** To identify and analyze the distribution and patterns of flight ticket prices across different airlines, travel classes, and routes.
* **Duration Efficiency:** To examine the relationship between flight duration and the number of stops, aiming to identify the most time-efficient flight options.
+ **Airline Performance Comparison:** To compare the performance of various airlines in terms of average ticket prices and flight durations, providing insights into cost-effectiveness and time efficiency.
- **Booking Strategy Insights:** To analyze how ticket prices fluctuate as the departure date approaches, offering valuable insights for travelers to optimize their booking strategies for cost savings.
* **Route Popularity Analysis:** To map and analyze the most frequently traveled flight routes, understanding demand trends and the competitive landscape of the airline industry

## Dataset Used
The data used was gotten from a survey that was conducted amidst airport customers, which was later collated into excel as a csv file. The data set includes all the following features which are necessary for analysis.
- **Airline:** The name of the airline company is stored in the airline column. It is a categorical feature having 6 different airlines.
* **Flight:** Flight stores information regarding the plane's flight code. It is a categorical feature.
+ **Source City:** City from which the flight takes off. It is a categorical feature having 6 unique cities.
- **Departure Time:** This is a derived categorical feature obtained created by grouping time periods into bins. It stores information about the departure time and have 6 unique time labels.
* **Stops:** A categorical feature with 3 distinct values that stores the number of stops between the source and destination cities.
+ **Arrival Time:** This is a derived categorical feature created by grouping time intervals into bins. It has six distinct time labels and keeps information about the arrival time.
- **Destination City:** City where the flight will land. It is a categorical feature having 6 unique cities.
* **Class:** A categorical feature that contains information on seat class; it has two distinct values: Business and Economy.
+ **Duration:** A continuous feature that displays the overall amount of time it takes to travel between cities in hours.
- **Days Left:** This is a derived characteristic that is calculated by subtracting the trip date by the booking date.
* **Price:** Target variable stores information of the ticket price.

## Methodology
The dataset was relatively clean, making the preparation for visualization straightforward. Initially, it was uploaded into Excel to remove any extra characters like "-" using the Find and Replace feature. Mixed-case text entries were then standardized to a proper format. Once cleaned, the data was loaded into Power BI, where new measures were created to facilitate easier and more effective visualization.
