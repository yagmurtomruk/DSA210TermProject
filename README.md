# DSA210 Term Project: How Air Quality Affects Running Performance

## Project Overview
This project explores the impact of air quality on running performance by analyzing data from personal running sessions alongside publicly available pollution metrics. By applying data science techniques, the study aims to determine whether factors like AQI levels, and particle concentrations influence pace, heart rate, and perceived effort. The goal is to use data-driven insights to better understand the relationship between environmental conditions and endurance exercise, contributing to both my personal training awareness and broader discussions on air quality and physical activity.

The following hypotheses will be tested throughout the project:
### Null Hypothesis (H₀): 
- Air quality has no significant effect on my running performance.
### Alternative Hypothesis (H₁): 
- Poor air quality negatively impacts my running performance.

---

## Contents
- [Motivation](#motivation)
- [Dataset](#dataset)
- [Data Collection](#data-collection)
- [Current Data Analysis Plan](#current-data-analysis-plan)

---

## Motivation

As someone who enjoys running, I tend to struggle with unexpected fluctuations in my running performance when I am training outdoors. I’ve always wondered if this is because of the changes in air quality that directly impact my performance.  There are days when my runs feel effortless, and other days when I struggle to maintain my usual pace—sometimes without any obvious reason. I started questioning whether pollution levels, specifically AQI (Air Quality Index), could be affecting my breathing, endurance, and overall running efficiency. Especially for someone living on the Sabancı University campus, the air quality certainly feels like an obstacle at certain times.
Therefore, I decided to take this project as a personal experiment to see whether poor air quality impacts my running performance by affecting factors like pace, heart rate, and perceived effort. I want to turn this into a real experiment and collect data from my own running sessions to determine:

- Whether I run slower on days with poor air quality compared to clean-air days.
- If my heart rate increases when I run in polluted conditions, even if my effort remains the same.
- Whether I feel more fatigued or short of breath when running in moderate or unhealthy AQI conditions.
  
By tracking my running performance in different air conditions, I hope to uncover data-driven insights about how air pollution affects endurance sports. This study will help me, and potentially other outdoor sports enthusiasts, to understand when it’s best to train outdoors and whether avoiding high-pollution days can lead to better running performance.

## Dataset

The dataset for this project consists of running performance data collected over multiple outdoor running sessions, combined with real-time air quality measurements from publicly available sources.
The datasets used for analysis will be:

- **Date:** The date of the running session.
- **Air Quality Index (AQI):** A numerical value representing pollution levels at the time of the run.
- **PM2.5 & NO₂ Concentrations:** Specific pollutants known to affect lung function.
- **Temperature & Humidity:** The specific temperature & humidity levels on the day and time of the run.
- **Running Distance (km):** Ensuring consistency across sessions.
- **Pace (min/km)** I want to measure my pace as a direct measure of my running efficiency.
- **Heart Rate (BPM):** Will be monitored as an indicator of cardiovascular strain.

#### Control Measures to Ensure Data Consistency:

All runs will be recorded under similar conditions (same route, time of day, and hydration levels) to ensure meaningful comparisons. The control measures will be as follows:

- Same running route to avoiding terrain-related performance differences. The sessions will be held on the university campus.
- Same time of day to minimize fluctuations in temperature and humidity levels.
- Similar rest, hydration, and nutrition levels before each run. The sessions will be held daily before breakfast, at around 7 AM, which is my usual running time. 
- Only outdoor runs will be recorded (No treadmill runs).

## Data Collection

I will personally collect all running performance data.
The heart rate and pace data will be monitored during the running session using a Samsung Galaxy Watch.

For air quality data, I will use the data from www.weather.com since it provides real-time AQI, PM2.5, NO₂, temperature, and humidity data. 

Each run’s air quality metrics will be logged in an Excel file within 30 minutes before or after the session to capture the most relevant environmental conditions.

## Current Data Analysis Plan

Here are the current plans for the analysis steps:

**1) Categorization of Data & Preprocessing**

- Categorizing AQI data based on the numerical value:
  - Good (0-50 AQI)
  - Moderate (51-100 AQI)
  - Unhealthy for Sensitive Groups (101-150 AQI)
  - Unhealthy (151-200 AQI)
- Cleaning and structuring the data logged in the Excel document.
- Reorganizing the dataset by handling missing values, ensuring consistency in time, and removing outliers.
- Standardizing numerical variables if necessary for comparison.

**2) Correlation Analysis**

Investigating the relationship between air quality and running performance based on collected data, to see if they are correlated.

**3) Exploratory Data Analysis (EDA)**

- Identifying trends and patterns in air quality levels and running performance across different sessions.
- Detecting outliers and unusual variations if present.

**4) Regression Modeling**

For understanding how air quality impacts running performance, and quantifying the relationship between AQI and key performance indicators such as pace and heart rate.

**5) Data Visualization**

Generating appropriate plots to illustrate the relationship.


---
