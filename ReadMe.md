### Overview
This repository contains a project focused on predicting traffic congestion levels using machine learning algorithms. The project utilizes two different approaches—Random Forest and Support Vector Regression (SVR)—to forecast traffic conditions based on various factors such as the day of the week, weather conditions, and temperature.

### Dataset
The dataset used for this project includes the following columns:

Date: Date of data collection (DD/MM/YYYY format).
Day: Weekday on which the data was collected.
Coded Day: Numerical encoding of the day of the week for easier processing (1=Monday, 2=Tuesday, ..., 7=Sunday).
Zone: Zone number indicating the area for traffic data collection. Zones are coded to reflect different weather conditions affecting traffic.
Temperature: Temperature recorded for the zone on the given day.
Traffic: Traffic congestion level on a five-level scale, where:
1: Less than 5 cars
2: 5 to 15 cars
3: 15 to 30 cars
4: 30 to 50 cars
5: More than 50 cars

- Machine Learning Models
- Random Forest
- Accuracy: 86.58%
- Error Rate: 13.42%
- Support Vector Regression (SVR)
- Accuracy: 87.84%
- Error Rate: 12.16%