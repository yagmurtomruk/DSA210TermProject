# DSA210 Term Project

## Contents
- [Motivation](#motivation)
- [Dataset](#dataset)
- [Data Collection](#data-collection)
- [Data Analysis](#data-analysis)

---

## Motivation

As someone who enjoys running outdoors, I’ve always wondered whether air quality directly impacts my performance. There are days when my runs feel effortless, and other days when I struggle to maintain my usual pace—sometimes without any obvious reason. I started questioning whether pollution levels, specifically AQI (Air Quality Index), could be affecting my breathing, endurance, and overall running efficiency. Especially for someone living on the Sabancı University campus, the air quality certainly feels like an obstacle at certain times.

This project is a personal experiment to see whether poor air quality impacts my running performance by affecting factors like pace, heart rate, and perceived effort. I want to turn this into a real experiment and collect data from my own running sessions to determine:

- Whether I run slower on days with poor air quality compared to clean-air days.
- If my heart rate increases when I run in polluted conditions, even if my effort remains the same.
- Whether I feel more fatigued or short of breath when running in moderate or unhealthy AQI conditions.
  
By tracking my running performance in different air conditions, I hope to uncover data-driven insights about how air pollution affects endurance sports. This study will help me, and potentially other outdoor sports enthusiasts, to understand when it’s best to train outdoors and whether avoiding high-pollution days can lead to better running performance.

🔹 Null Hypothesis (H₀):
Air quality has no significant effect on running performance.

🔹 Alternative Hypothesis (H₁):
Poor air quality negatively impacts running performance.

## Dataset

The dataset for this project consists of running performance data collected over multiple outdoor running sessions, combined with real-time air quality measurements from publicly available sources.

The datasets used for analysis will be:

Date – The date of the running session.
Air Quality Index (AQI) – A numerical value representing pollution levels at the time of the run.
PM2.5 & NO₂ Concentrations – Specific pollutants known to affect lung function.
Temperature & Humidity – To control for weather-related effects on performance.
Running Distance (km/miles) – Ensuring consistency across sessions.
Pace (min/km or min/mile) – I want to measure my pace as a direct measure of my running efficiency.
Heart Rate (BPM) – Will be monitored as an indicator of cardiovascular strain.
Perceived Effort (Scale 1-10) – Self-reported difficulty level.

All runs will be recorded under similar conditions (same route, time of day, and hydration levels) to minimize confounding variables and ensure meaningful comparisons.

## Data Collection

I will personally collect all running performance data using the Samsung Health app.
Manual Logging – For perceived effort ratings and any additional observations (e.g., fatigue, shortness of breath).

For air quality data, I will use the data from www.weather.com since it provides real-time AQI, PM2.5, NO₂, temperature, and humidity data.
Local Government Air Quality Data – If available, for additional verification.
Each run’s air quality metrics will be logged within 30 minutes before or after the session to capture the most relevant environmental conditions.

Control Measures to Ensure Data Consistency:
- Same running route – Avoiding terrain-related performance differences.-
- Same time of day – Minimizing temperature and humidity fluctuations.
- Similar rest, hydration, and nutrition levels before each run.
- Only outdoor runs will be recorded (No treadmill runs).

## Data Analysis

1) Categorization of Data
Categorize AQI into:
- Good (0-50 AQI)
- Moderate (51-100 AQI)
- Unhealthy for Sensitive Groups (101-150 AQI)
- Unhealthy (151-200 AQI)
2) Correlation Analysis
3) Regression Modeling
4) Experimental Data Analysis (EDA)

---
