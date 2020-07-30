# About the 'Multivariate Sensor Data' dataset

## Overview

|METADATA||
|:-----|------|
|**topic**|geriatric wearable sensor data|
|**soure**|Charité / Withings|
|**type**|sensor data|
|**format**|csv|
|**licence**|[Open Data Commons Attribution Licence (ODC-By)](https://opendatacommons.org/licenses/by/summary/)|
|**publisher**|Charité|
|**publishing date/period**|14.07.20 - 29.07.20|

## Short description
This data is from an elderly patient of the geriatric departement of the Charité, gathered by multiple wearables of the brand Withings over the course of 16 days.


## Measures and units

**activities.csv:** Activities history
- calories: Active calories burned (in Kcal)
- intensity: Duration of intense activities (in seconds)
- hr_zone_0: Duration in seconds when heart rate was in a light zone
- hr_zone_1: Duration in seconds when heart rate was in a moderate zone
- hr_zone_2: Duration in seconds when heart rate was in an intense zone
- hr_zone_3: Duration in seconds when heart rate was in maximal zone
- distance: Distance in meters
- elevation: Number of floors climbed 

**aggregates_calories_earned.csv:** Active calories (Kcal) burned regrouped by days

**aggregates_calories_passive.csv:** Passive calories (Kcal) burned regrouped by days

**aggregates_distance.csv:** Travelled distance (meters) regrouped by days

**aggregates_steps.csv:** Steps datas regrouped by days
- Value : (steps number)

**bladder_filling.csv:** Bladder data in percent filling

**bp.csv:** Blood Pressure Data
- Heart Rate : (bpm)
- Systolic : (mmHg)
- Diastolic : (mmHg)

**height.csv:** Height Measurements
- Height : (meters)

**raw_sleep-monitor_hr.csv:** Sleep monitor heart rate datas
- Duration : (seconds)
- Value : (bpm)

**raw_sleep-monitor_respiratory-rate.csv:** Sleep monitor respiratory rates
- Duration : (seconds)

**raw_sleep-monitor_sleep-state.csv:** Sleep monitor sleep datas
- Duration : (seconds)
- Value : ( 0 -> awake; 1 -> sleeping)

**raw_sleep-monitor_snoring.csv:** Sleep monitor snoring datas
- Duration : (seconds)
- Value : (0 -> not snoring; 1 -> snoring)

**raw_tracker_calories-earned.csv:** Active calories (Kcal) burned raw data

**raw_tracker_distance.csv:** Travelled distance (meters)

**raw_tracker_hr.csv:** Heart rate datas
- Heart Rate : (bpm)

**raw_tracker_sleep-state.csv:** Sleep trackers datas
- Duration: (seconds)

**raw_tracker_steps.csv:** Steps datas

**sleep.csv:** Sleep state, snoring and heart rate datas

**weight.csv:** Weights Measurements
- Weight : Weight (kg)



Further information available at the [Withings API developer documentation (v1.0)](https://developer.withings.com/oauth2/)
