## Introduction 

Introduction: An anaylsis will be conducted for the company Zuber. Zuber is a new ride sharing company in Chicago. The aim is to support Zuber in having a successful launch in Chicago. Data is provided from competitors. An examination of passenger preferences and how external factors impact rides will be conducted.

Purpose: The project will aim to answer the following questons:

What patterns emerge about passenger preferneces?
How do external factors impact rides?
Hypothesis: The following hypothesis will be examined: a. The average duration of rides from the Loop to O'Hare International Airport changes on rainy Saturdays.

## Data 

neighborhoods table: data on city neighborhoods

name: name of the neighborhood
neighborhood_id: neighborhood code
cabs table: data on taxis

cab_id: vehicle code
vehicle_id: the vehicle's technical ID
company_name: the company that owns the vehicle
trips table: data on rides

trip_id: ride code
cab_id: code of the vehicle operating the ride
start_ts: date and time of the beginning of the ride (time rounded to the hour)
end_ts: date and time of the end of the ride (time rounded to the hour)
duration_seconds: ride duration in seconds
distance_miles: ride distance in miles
pickup_location_id: pickup neighborhood code
dropoff_location_id: dropoff neighborhood code
weather_records table: data on weather

record_id: weather record code
ts: record date and time (time rounded to the hour)
temperature: temperature when the record was taken
description: brief description of weather conditions, e.g. "light rain" or "scattered clouds"

## Libraries Used 
Pandas, Matplotlib, Numpy, Seaborn, Scipy 

## Table of Contents 
1. Introduction
2. Data Exploration
3. Data Preprocessing 
4. EDA (Exploratory Data Analysis)
5. Hypothesis TEsting
6. Conclusion 
