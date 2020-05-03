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

The goal of this market analysis is to provide information to PyBer management so they can implement policies to to improve access to ride sharing services and to determine affordability for underserved neighborhoods per the goal of this project.

The data clearly shows that urban rides make up the vast majority of the ride-shares provided by the PyBer. In addition, the data shows that the number of ride decreases significantly and the average ride costs increase significantly as the ride location goes from urban an suburban and from suburban to rural. The total munber of ride provided to suburban cities is 80% less than the rides provided to urban customers while the number of rides provided to rural cities is 97% than the rides provided to urban cities. Forthermore, the average cost of a suburban ride is 25% higher than an urban ride and the average cost of a rural ride is 58% higher than an urban ride.
Clealy, the analysis data shows that the suburban and rural markets are PyBer's most underserved regions and least affordable.




## Challenges Encountered and Overcome

### Challenges and Difficulties Encountered

* Programming

* Data analysis

* Graphing, etc

### Technical Analyses Used

## Recommendations and Next Steps

### Recommendations for Future Analysis

### Additional Analysis 1

* Description of Approach

* Technical Steps

### Additional Analysis 2

* Description of Approach

* Technical Steps
