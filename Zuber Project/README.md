This was the second project I completed in the TripleTen Business Intelligence Analytics Program. It was an independent project aimed at demonstrating my SQL skills. The goal was to analyze competitor data to identify trends in passenger preferences and assess how external factors influence ride activity.

*** Description:

This project involved a 6-step SQL query to conduct an exploratory data analysis examining whether ride durations from the Loop to O'Hare International Airport vary on rainy Saturdays.

*** Process:

1.) Trip Analysis: Analyzed taxi rides by company for specific dates, ranking by trip count.
  
2.) Company Filtering: Identified rides for companies with certain keywords, grouping by company name.
  
3.) Location Mapping: Retrieved neighborhood IDs for O'Hare and Loop.
  
4.) Weather Categorization: Classified weather conditions by hour.
  
5.) Data Extraction: Selected Saturday rides from Loop to O'Hare, incorporating weather and ride duration.
  
6.) Result Sorting: Organized the final output.

  
*** Data:

The analysis used a Chicago taxi ride database provided by TripleTen, including:

> 'neighborhoods' table: Neighborhood names and IDs.
> 'cabs' table: Taxi company names, cab IDs, and vehicle IDs.
> 'trips' table: Ride details, including duration, distance, timestamps, and location IDs.
> 'weather_records' table: Weather data, including temperature, descriptions, and timestamps.

*** Assumptions:

- No direct link exists between trips and weather_records tables.
 --- Primary keys:
    - neighborhood_id: for neighborhoods table.
    - cab_id: for cabs table.
    - trip_id: for trips table.
    - record_id: for weather_records table.

*** Findings:

- Top Company: "Flash Cab" completed 19,558 trips between Nov. 15th-16th, 2017.
  
- Keyword Search: "Blue Diamond" led with 6,764 trips for Nov. 1st-7th, 2017 when filtering for "Yellow" or "Blue".
  
- Company Comparison: Combined rides from "Other" companies far exceeded "Flash Cab" and "Taxi Affiliation Services" individually or combined during Nov. 1st-7th, 2017.
  
- Neighborhood IDs: The Loop and O'Hare were identified as ID #50 and ID #63, respectively.
  
- Weather Classification: Each hour received an initial "Good" weather designation.
  
- Result Table: A SQL table displayed Saturday rides from the Loop to O'Hare, showing start times, weather conditions, and ride durations.
