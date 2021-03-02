# DataPython

Ficheros de datos para análisis

## Stroke Prediction Dataset

According to the World Health Organization (WHO) stroke is the 2nd leading cause of death globally, responsible for approximately 11% of total deaths.
This dataset is used to predict whether a patient is likely to get stroke based on the input parameters like gender, age, various diseases, and smoking status. Each row in the data provides relavant information about the patient.

Attribute Information

1) id: unique identifier
2) gender: "Male", "Female" or "Other"
3) age: age of the patient
4) hypertension: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension
5) heart_disease: 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease
6) ever_married: "No" or "Yes"
7) work_type: "children", "Govt_jov", "Never_worked", "Private" or "Self-employed"
8) Residence_type: "Rural" or "Urban"
9) avg_glucose_level: average glucose level in blood
10) bmi: body mass index
11) smoking_status: "formerly smoked", "never smoked", "smokes" or "Unknown"*
12) stroke: 1 if the patient had a stroke or 0 if not
*Note: "Unknown" in smoking_status means that the information is unavailable for this patient

## Rain in Australia

Predict next-day rain by training classification models on the target variable RainTomorrow.

Content
This dataset contains about 10 years of daily weather observations from many locations across Australia.

RainTomorrow is the target variable to predict. It means -- did it rain the next day, Yes or No? This column is Yes if the rain for that day was 1mm or more.

Attribute Information

1) Date: The date of observation
2) Location: The common name of the location of the weather station
3) MinTemp: The minimum temperature in degrees celsius
4) MaxTemp: The maximum temperature in degrees celsius
5) Rainfall: The amount of rainfall recorded for the day in mm
6) Evaporation: The so-called Class A pan evaporation (mm) in the 24 hours to 9am
7) Sunshine: The number of hours of bright sunshine in the day.
8) WindGustDir: The direction of the strongest wind gust in the 24 hours to midnight
9) WindGustSpeed: The speed (km/h) of the strongest wind gust in the 24 hours to midnight
10) WindDir9am: Direction of the wind at 3pm
11) WindSpeed9am: Wind speed (km/hr) averaged over 10 minutes prior to 9am
12) WindSpeed3pm: Wind speed (km/hr) averaged over 10 minutes prior to 3pm
13) Humidity9am: Humidity (percent) at 9am
14) Humidity3pm: Humidity (percent) at 3pm
15) Pressure9am: Atmospheric pressure (hpa) reduced to mean sea level at 9am
16) Pressure3pm: Atmospheric pressure (hpa) reduced to mean sea level at 3pm
17) Cloud9am: Fraction of sky obscured by cloud at 9am. This is measured in "oktas", which are a unit of eigths. It records how many
18) Cloud3pm: Fraction of sky obscured by cloud (in "oktas": eighths) at 3pm. See Cload9am for a description of the values
19) Temp9am: Temperature (degrees C) at 9am
20) Temp3pm: Temperature (degrees C) at 3pm
21) RainToday: Boolean: 1 if precipitation (mm) in the 24 hours to 9am exceeds 1mm, otherwise 0
22) RainTomorrow: The amount of next day rain in mm. Used to create response variable RainTomorrow. A kind of measure of the "risk".






















