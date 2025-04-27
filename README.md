# Melbourne Pedestrian Traffic Analysis


**Project Overview**
This project analyzes pedestrian traffic patterns in Melbourne using real-world data collected from city-installed sensors. The goal is to clean the dataset, extract meaningful time-based features, and visualize foot traffic trends to uncover insights such as busiest locations, daily and seasonal patterns, and the influence of weekdays versus weekends on pedestrian flow.

## **Dataset**

**Source:** Melbourne Open Data Platform

**Features:**

Sensor_Name

Sensing_Date

Location_ID

HourDay

Direction_1

Direction_2

Total_of_Directions

Location (Latitude and Longitude coordinates)

## **Technologies Used**

Python

Pandas for data cleaning and feature engineering

Matplotlib, Seaborn for data visualization

Google Colab for running the Jupyter Notebook

## **Data Cleaning**

Renamed columns for readability.

Converted Sensing_Date into a proper datetime format.

Extracted additional time-based features: Month, Day, Weekday.

Checked and handled missing or inconsistent data.

## **Visualizations and Insights**

1. Pedestrian Count by Hour
    Two significant peaks occur at 8 AM and 5 PM, aligning with morning and evening commute periods.
    Pedestrian traffic drops to its lowest between midnight and 5 AM.
    Activity is sustained during standard office hours but falls sharply in the evening, indicating the influence of work schedules.

2. Monthly Pedestrian Counts by Top 5 Sensors
    Certain sensors consistently record the highest foot traffic volumes, especially those located in major city hubs.
    Pedestrian activity peaks during warmer months (October to December), likely influenced by better weather and events.
    A noticeable decline in counts occurs during winter months (June to July), reflecting reduced outdoor activity.

3. Top 5 Locations by Total Volume
    Identified key hotspots with the highest cumulative pedestrian counts across the dataset.
    Locations such as Bourke Street Mall and Southern Cross Station emerged as dominant foot traffic hubs.

## **Key Learnings**
Handling and preprocessing time-series and location-based datasets.

Deriving insights through feature engineering.

Building clear and informative visualizations that highlight trends and patterns.

Understanding how external factors like seasons, work hours, and weekends impact pedestrian activity in urban environments.

## **Future Work**
Build an interactive dashboard using Streamlit.

Incorporate weather or event data to further explain fluctuations.

Apply simple forecasting models to predict future pedestrian counts.

