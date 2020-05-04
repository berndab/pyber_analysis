# PyBer Analysis Report

|      Type         |             Name                |             Description            |
--------------------|---------------------------------|------------------------------------|
| Program Language  | Python 3.7.7                    |                                    |
| APIs and Modules  | Anaconda 4.8.3                  |                                    |
|                   | Pandas 1.0.3                    |                                    |
|                   | Matplotlib 3.1.3                |                                    |
| Data Sources      | resources/scity_data.csv        |                                    |
|                   | resources/ride_data.csv         |                                    |
| Programming Tools | Jupyter Notebook                |                                    |
| Application Files | PyBer_Analysis.ipynb            | PyBer ride share data analysis     |

## Background and Results

### Purpose

The purpose of this project is to analyze ride data from the cities that PyBer has, so far, provided it's ride-sharing services in and to generate market analysis data aggregated by the type of city where each ride took place in. Each city where a PyBer ride took place is assigned one of the following city types:

* Urban
* Suburban
* Rural

PyBer management will use this market analysis data to improve access to ride sharing services and to determine affordability for underserved neighborhoods.

### Technical Analysis

This analysis utilized Pyber ride-sharing data for the months of January to April of 2019. The ride sharing data for this period consisted of two data sets

Ride Data
* Date of the ride
* City where the ride occured
* Total fare
* Ride Id - unique ride identifier

City Data
* City name
* City type
* Number of PyBer drivers

The application to generate this analysis data was created using Jupyter Notebook, Python, Python Pandas API, and Matplotlib API

The Jupyter Notebook application geerated the following analysis data:

Ride Summary Data
* Total Rides
* Total Drivers
* Total Fares
* Average Fare 
* Average Fare per Driver

Total Weekly Fares By City Type

### Results

<img src="https://github.com/berndab/pyber_analysis/blob/master/analysis/Table.Summary.png" width="760" height="225" />

<img src="https://github.com/berndab/pyber_analysis/blob/master/analysis/Chart.Weekly_Total_Fares.png" width="800" height="250" />

### Summary

The goal of this market analysis is to provide information to PyBer management so they can implement policies to improve access to ride sharing services and to determine affordability for underserved neighborhoods per the goal of this project.

The data clearly shows that urban rides make up most of the ride provided by the PyBer. In addition, the data shows that the number of rides decreases and the average ride costs increase significantly as the ride location goes from an urban to a suburban setting and from a suburban to a rural setting. The total number of rides decrease by 80% going from an urban to a suburban setting and by 97% when going from an urban to a rural setting.  Furthermore, the average cost of a suburban ride is 25% higher and the average cost of a rural ride is 58% higher than an urban ride. Clearly, the analysis data shows that the suburban and rural cities are PyBer's most underserved and least affordable regions.
It should be expected that the number of rides decreases the farther out the rides occur from major city centers. This decrease can be attributed to the smaller population density of suburban and rural cities and more conducive these cities are to the use of personal automobiles for transportation. However, a 80% plus difference in total rides is too large a magnitude to be solely attributed to these two factors. The higher average cost of PyBer rides in suburban and rural setting must also strongly contribute to PyBer’s low ridership in suburban and rural cities. 

Transportation and parking cost should also be considered when explaining the ridership difference between urban and suburban and rural cities. The scarcity and cost of parking at urban destinations as opposed to the availability of free parking at the typical suburban and rural destination significantly contributes this ridership difference. In urban settings, free parking is much less available, and the cost of paid parking is usually based on time. Depending on the urban destination and the time that a PyBer customer spends there, the parking costs in a significant number of instances would exceed the average cost of a urban PyBer ride. That means that using PyBer is attractive to urban customers because in many instances it offers a cost saving over driving.  
If we assume that the average distance to an urban destination is much shorter than the average distance to a suburban or rural destination, fuel cost of driving to an urban destination is negligible compared to the parking cost. Due to these shorter distances keep the cost of using PyBer low. Thus the parking cost saving is the cost advantage of using PyBer in urban cities. However for suburban and rural trips with the longer distances to destinations and the availability of ample free parking, there is a cost disadvantage to using PyBer. Since the ride data provided does not include trip length, there was no data available to test these assumptions. 
The goal of this market analysis is to provide information to PyBer management so they can implement policies to improve access to ride sharing services and to determine affordability for underserved neighborhoods per the goal of this project.

The data clearly shows that urban rides make up most of the ride provided by the PyBer. In addition, the data shows that the number of rides decreases and the average ride costs increase significantly as the ride location goes from an urban to a suburban setting and from a suburban to a rural setting. The total number of rides decrease by 80% going from an urban to a suburban setting and by 97% when going from an urban to a rural setting.  Furthermore, the average cost of a suburban ride is 25% higher and the average cost of a rural ride is 58% higher than an urban ride. Clearly, the analysis data shows that the suburban and rural cities are PyBer's most underserved and least affordable regions.
It should be expected that the number of rides decreases the farther out the rides occur from major city centers. This decrease can be attributed to the smaller population density of suburban and rural cities and more conducive these cities are to the use of personal automobiles for transportation. However, a 80% plus difference in total rides is too large a magnitude to be solely attributed to these two factors. The higher average cost of PyBer rides in suburban and rural setting must also strongly contribute to PyBer’s low ridership in suburban and rural cities. 

Transportation and parking cost should also be considered when explaining the ridership difference between urban and suburban and rural cities. The scarcity and cost of parking at urban destinations as opposed to the availability of free parking at the typical suburban and rural destination significantly contributes this ridership difference. In urban settings, free parking is much less available, and the cost of paid parking is usually based on time. Depending on the urban destination and the time that a PyBer customer spends there, the parking costs in a significant number of instances would exceed the average cost of a urban PyBer ride. That means that using PyBer is attractive to urban customers because in many instances it offers a cost saving over driving.  

If we assume that the average distance to an urban destination is much shorter than the average distance to a suburban or rural destination, fuel cost of driving to an urban destination is negligible compared to the parking cost. Due to these shorter distances keep the cost of using PyBer low. Thus the parking cost saving is the cost advantage of using PyBer in urban cities. However for suburban and rural trips with the longer distances to destinations and the availability of ample free parking, there is a cost disadvantage to using PyBer. Since the ride data provided does not include trip length, there was no data available to test these assumptions. 

 In order to attract more riders in the underserved and more costly suburban and rural markets PyBer must explore using a different cost model in these regions.  Given that the most like contributor to low ridership in suburban and rural cities if the fact that longer rides cost more and more expensive to driving yourself given that the destination usually has free parking, PyBer must look at having a graduated cost model where the longer the distance there is a reduce cost per mile about a give trip length threshold. For instance, trip miles over 15 have a reduced rate per mile.  This would attract more riders in suburban and rural areas due to marginally lower costs. 

## Challenges Encountered and Overcome

### Challenges and Difficulties Encountered

### Technical Analyses Used

## Recommendations and Next Steps

### Recommendations for Future Analysis

### Additional Analysis 1

All future individual ride data provided for analysis should contain ride distances. This is needed to accuratly determine the factors the lead having higher avarage trip costs in the underserved and less affordable suburban and rural city types

### Additional Analysis 2

* Description of Approach

* Technical Steps
