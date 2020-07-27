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
The [Withings API developer documentation (v1.0)](https://developer.withings.com/oauth2/) page has further documentation on the sensors and measures.

## Measures and units

activities.csv: Activities history

aggregates_calories_earned.csv: Active calories burned regrouped by days

aggregates_calories_passive.csv: Passive calories burned regrouped by days

aggregates_distance.csv: Travelled distance regrouped by days

aggregates_steps.csv: Steps datas regrouped by days
· Value : (steps number)

bp.csv: Blood Pressure Data
· Heart Rate : (bpm)
· Systolic : (mmHg)
· Diastolic : (mmHg)

height.csv: Height Measurements
· Height : (meters)

raw_sleep-monitor_hr.csv: Sleep monitor heart rate datas
· Duration : (seconds)
· Value : (bpm)

raw_sleep-monitor_respiratory-rate.csv: Sleep monitor respiratory rates
· Duration : (seconds)

raw_sleep-monitor_sleep-state.csv: Sleep monitor sleep datas
· Duration : (seconds)
· Value : ( 0 -> awake; 1 -> sleeping)

raw_sleep-monitor_snoring.csv: Sleep monitor snoring datas
· Duration : (seconds)
· Value : (0 -> not snoring; 1 -> snoring)

raw_tracker_elevation.csv: To complete

raw_tracker_hr.csv: Heart rate datas
· Heart Rate : (bpm)

raw_tracker_sleep-state.csv: Sleep trackers datas
· Duration: (seconds)

raw_tracker_steps.csv: Steps datas

weight.csv: Weights Measurements
· Weight : Weight (kg)

Further information available at the [Withings API developer documentation (v1.0)](https://developer.withings.com/oauth2/)
