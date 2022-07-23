# Western US Climbing Routes Analysis

This repository contains python scripts, data sets, and a report on findings and analysis of rock climbing routes within the western United States. This is a project for Career Foundry Data Immersion Course. 

For the final report, click here (insert link when done). 

## **Objective**
There are two overall objectives for this analysis. The first is to develop a tool to better help rock climbers decide where to climb in the west based on a variety of factors related to climbing routes. Examples include route difficulty, length, and type of climbing. 

The second objective is to provide an analysis of variables affecting any given routes quality (or average stars it receives from other climbers).  In this analysis, we look at two specific variables- route difficulty (rating) and route length. 

**Key questions to answer:**
- Based on a desired difficulty, where are the best climbing areas to visit? 
- What areas have the highest number of routes based on type of climbing (traditional or sport)? 
- Where are the majority of long routes located in the western US? 
- What factors/variables help determine a routes quality? 

## **Data**
The data contains information on the following parameters:
- Route Name
- Location (State, Region, Area)
- Avg Stars a route receives 
- Route Type
- Number of Pitches
- Route Length
- Rating
- Latitude
- Longitude
- URL to route page on mountainproject

The data was sourced from https://www.mountainproject.com/, an online climbing route database. Most data on mountain project is submitted and compiled by its users. The site allows for up to 1000 records to be exported and downloaded at a time. Therefore, 79 separate data sets were exported and then combined in order to capture the vast majority of routes in the western US. 

## **Tools**
For this project, the following python libraries were used: 
- pandas
- numpy 
- seaborn
- matplotlib
- scipy
- sklearn
- pylab
- folium
- json

The final report was created in Tableau.  

