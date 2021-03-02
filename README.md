# DataPython

Ficheros de datos para análisis (extraidos de kaggle).

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

## Diabetes

This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage.

The datasets consists of several medical predictor variables and one target variable, Outcome. Predictor variables includes the number of pregnancies the patient has had, their BMI, insulin level, age, and so on.

Attribute Information

1) Pregnancies: Number of times pregnant
2) Glucose: Plasma glucose concentration a 2 hours in an oral glucose tolerance test
3) BloodPressure: Diastolic blood pressure (mm Hg)
4) SkinThickness: Triceps skin fold thickness (mm)
5) Insulin: 2-Hour serum insulin (mu U/ml)
6) BMI: Body mass index (weight in kg/(height in m)^2)
7) DiabetesPedigreeF..: Diabetes pedigree function
8) Age: Age (years)
9) Outcome: Class variable (0 or 1) 268 of 768 are 1, the others are 0

## Cancer

Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the image.
n the 3-dimensional space is that described in: [K. P. Bennett and O. L. Mangasarian: "Robust Linear Programming Discrimination of Two Linearly Inseparable Sets", Optimization Methods and Software 1, 1992, 23-34].

This database is also available through the UW CS ftp server:
ftp ftp.cs.wisc.edu
cd math-prog/cpo-dataset/machine-learn/WDBC/

Also can be found on UCI Machine Learning Repository: https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29

Attribute Information:

1) ID number
2) Diagnosis (M = malignant, B = benign)
3-32)

Ten real-valued features are computed for each cell nucleus:

a) radius (mean of distances from center to points on the perimeter)
b) texture (standard deviation of gray-scale values)
c) perimeter
d) area
e) smoothness (local variation in radius lengths)
f) compactness (perimeter^2 / area - 1.0)
g) concavity (severity of concave portions of the contour)
h) concave points (number of concave portions of the contour)
i) symmetry
j) fractal dimension ("coastline approximation" - 1)

The mean, standard error and "worst" or largest (mean of the three
largest values) of these features were computed for each image,
resulting in 30 features. For instance, field 3 is Mean Radius, field
13 is Radius SE, field 23 is Worst Radius.

All feature values are recoded with four significant digits.

## Avocado prices

It is a well known fact that Millenials LOVE Avocado Toast. It's also a well known fact that all Millenials live in their parents basements. Clearly, they aren't buying home because they are buying too much Avocado Toast! But maybe there's hope… if a Millenial could find a city with cheap avocados, they could live out the Millenial American Dream.

This data was downloaded from the Hass Avocado Board website in May of 2018 & compiled into a single CSV. Here's how the Hass Avocado Board describes the data on their website:

The table below represents weekly 2018 retail scan data for National retail volume (units) and price. Retail scan data comes directly from retailers’ cash registers based on actual retail sales of Hass avocados. Starting in 2013, the table below reflects an expanded, multi-outlet retail data set. Multi-outlet reporting includes an aggregation of the following channels: grocery, mass, club, drug, dollar and military. The Average Price (of avocados) in the table reflects a per unit (per avocado) cost, even when multiple units (avocados) are sold in bags. The Product Lookup codes (PLU’s) in the table are only for Hass avocados. Other varieties of avocados (e.g. greenskins) are not included in this table.

Some relevant columns in the dataset:

Date - The date of the observation
AveragePrice - the average price of a single avocado
type - conventional or organic
year - the year
Region - the city or region of the observation
Total Volume - Total number of avocados sold
4046 - Total number of avocados with PLU 4046 sold
4225 - Total number of avocados with PLU 4225 sold
4770 - Total number of avocados with PLU 4770 sold

## Mushrooms

Although this dataset was originally contributed to the UCI Machine Learning repository nearly 30 years ago, mushroom hunting (otherwise known as "shrooming") is enjoying new peaks in popularity. Learn which features spell certain death and which are most palatable in this dataset of mushroom characteristics. And how certain can your model be?

This dataset includes descriptions of hypothetical samples corresponding to 23 species of gilled mushrooms in the Agaricus and Lepiota Family Mushroom drawn from The Audubon Society Field Guide to North American Mushrooms (1981). Each species is identified as definitely edible, definitely poisonous, or of unknown edibility and not recommended. This latter class was combined with the poisonous one. The Guide clearly states that there is no simple rule for determining the edibility of a mushroom; no rule like "leaflets three, let it be'' for Poisonous Oak and Ivy.

Attribute Information: (classes: edible=e, poisonous=p)

1) cap-shape: bell=b,conical=c,convex=x,flat=f, knobbed=k,sunken=s
2) cap-surface: fibrous=f,grooves=g,scaly=y,smooth=s
3) cap-color: brown=n,buff=b,cinnamon=c,gray=g,green=r,pink=p,purple=u,red=e,white=w,yellow=y
4) bruises: bruises=t,no=f
5) odor: almond=a,anise=l,creosote=c,fishy=y,foul=f,musty=m,none=n,pungent=p,spicy=s
6) gill-attachment: attached=a,descending=d,free=f,notched=n
7) gill-spacing: close=c,crowded=w,distant=d
8) gill-size: broad=b,narrow=n
9) gill-color: black=k,brown=n,buff=b,chocolate=h,gray=g, green=r,orange=o,pink=p,purple=u,red=e,white=w,yellow=y
10) stalk-shape: enlarging=e,tapering=t
11) stalk-root: bulbous=b,club=c,cup=u,equal=e,rhizomorphs=z,rooted=r,missing=?
12) stalk-surface-above-ring: fibrous=f,scaly=y,silky=k,smooth=s
13) stalk-surface-below-ring: fibrous=f,scaly=y,silky=k,smooth=s
14) stalk-color-above-ring: brown=n,buff=b,cinnamon=c,gray=g,orange=o,pink=p,red=e,white=w,yellow=y
15) stalk-color-below-ring: brown=n,buff=b,cinnamon=c,gray=g,orange=o,pink=p,red=e,white=w,yellow=y
16) veil-type: partial=p,universal=u
17) veil-color: brown=n,orange=o,white=w,yellow=y
18) ring-number: none=n,one=o,two=t
19) ring-type: cobwebby=c,evanescent=e,flaring=f,large=l,none=n,pendant=p,sheathing=s,zone=z
20) spore-print-color: black=k,brown=n,buff=b,chocolate=h,green=r,orange=o,purple=u,white=w,yellow=y
21) population: abundant=a,clustered=c,numerous=n,scattered=s,several=v,solitary=y
22) habitat: grasses=g,leaves=l,meadows=m,paths=p,urban=u,waste=w,woods=d

## hotel_bookings

This data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things.

All personally identifying information has been removed from the data.

Attribute Information:

1) hotel: (H1 = Resort Hotel or H2 = City Hotel)
2) is_canceled: Value indicating if the booking was canceled (1) or not (0)
3) lead_time: Number of days that elapsed between the entering date of the booking into the PMS and the arrival date
4) arrival_date_year: Year of arrival date
5) arrival_date_month: Month of arrival date
6) arrival_date_week_number: Week number of year for arrival date
7) arrival_date_day_of: Day of arrival date
8) stays_in_weekend_: Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay at the hotel
9) stays_in_week_nigh: Number of week nights (Monday to Friday) the guest stayed or booked to stay at the hotel
10) adults: Number of adults
11) children: Number of children
12) babies: Number of babies
13) meal: Type of meal booked. Categories are presented in standard hospitality meal packages: Undefined/SC – no meal
14) country: Country of origin. Categories are represented in the ISO 3155–3:2013 format
15) market_segment: Market segment designation. In categories, the term “TA” means “Travel Agents” and “TO” means “Tour Operators”
16) distribution_channel: Booking distribution channel. The term “TA” means “Travel Agents” and “TO” means “Tour Operators”
17) is_repeated_guest: Number of previous bookings that were cancelled by the customer prior to the current booking
18) previous_bookings: Number of previous bookings not cancelled by the customer prior to the current booking
19) reserved_room_type: Code of room type reserved. Code is presented instead of designation for anonymity reasons.
20) assigned_room_type: Code for the type of room assigned to the booking. Sometimes the assigned room type differs from the reserved room type due
21) booking_changes: Number of changes/amendments made to the booking from the moment the booking was entered on the PMS
22) deposit_type: Indication on if the customer made a deposit to guarantee the booking. This variable can assume three categories: No
23) agent: ID of the travel agency that made the booking
24) company: ID of the company/entity that made the booking or responsible for paying the booking. ID is presented instead of designation for
25) days_in_waiting_list: Number of days the booking was in the waiting list before it was confirmed to the customer
26) customer_type: Type of booking, assuming one of four categories: Contract - when the booking has an allotment or other type of contract associated to
27) adr: Average Daily Rate as defined by dividing the sum of all lodging transactions by the total number of staying nights
28) required_car_parking_spaces: Number of car parking spaces required by the customer
29) total_of_special_requests: Number of special requests made by the customer (e.g. twin bed or high floor)
30) reservation_status: Reservation last status, assuming one of three categories: Canceled – booking was canceled by the customer; Check-Out
31) reservation_status_date: Date at which the last status was set. This variable can be used in conjunction with the ReservationStatus to


## Student Alcohol Consumption


The data were obtained in a survey of students math and portuguese language courses in secondary school. It contains a lot of interesting social, gender and study information about students. You can use it for some EDA or try to predict students final grade.

Attributes for student-mat.csv:

1) school - student's school (binary: 'GP' - Gabriel Pereira or 'MS' - Mousinho da Silveira)
2) sex - student's sex (binary: 'F' - female or 'M' - male)
3) age - student's age (numeric: from 15 to 22)
4) address - student's home address type (binary: 'U' - urban or 'R' - rural)
5) famsize - family size (binary: 'LE3' - less or equal to 3 or 'GT3' - greater than 3)
6) Pstatus - parent's cohabitation status (binary: 'T' - living together or 'A' - apart)
7) Medu - mother's education (numeric: 0 - none, 1 - primary education (4th grade), 2 – 5th to 9th grade, 3 – secondary education or 4 – higher education)
8) Fedu - father's education (numeric: 0 - none, 1 - primary education (4th grade), 2 – 5th to 9th grade, 3 – secondary education or 4 – higher education)
9) Mjob - mother's job (nominal: 'teacher', 'health' care related, civil 'services' (e.g. administrative or police), 'at_home' or 'other')
10) Fjob - father's job (nominal: 'teacher', 'health' care related, civil 'services' (e.g. administrative or police), 'at_home' or 'other')
11) reason - reason to choose this school (nominal: close to 'home', school 'reputation', 'course' preference or 'other')
12) guardian - student's guardian (nominal: 'mother', 'father' or 'other')
13) traveltime - home to school travel time (numeric: 1 - 1 hour)
14) studytime - weekly study time (numeric: 1 - 10 hours)
15) failures - number of past class failures (numeric: n if 1<=n<3, else 4)
16) schoolsup - extra educational support (binary: yes or no)
17) famsup - family educational support (binary: yes or no)
18) paid - extra paid classes within the course subject (Math or Portuguese) (binary: yes or no)
19) activities - extra-curricular activities (binary: yes or no)
20) nursery - attended nursery school (binary: yes or no)
21) higher - wants to take higher education (binary: yes or no)
22) internet - Internet access at home (binary: yes or no)
23) romantic - with a romantic relationship (binary: yes or no)
24) famrel - quality of family relationships (numeric: from 1 - very bad to 5 - excellent)
25) freetime - free time after school (numeric: from 1 - very low to 5 - very high)
26) goout - going out with friends (numeric: from 1 - very low to 5 - very high)
27) Dalc - workday alcohol consumption (numeric: from 1 - very low to 5 - very high)
28) Walc - weekend alcohol consumption (numeric: from 1 - very low to 5 - very high)
29) health - current health status (numeric: from 1 - very bad to 5 - very good)
30) absences - number of school absences (numeric: from 0 to 93)

These grades are related with the course subject, Math or Portuguese:

G1 - first period grade (numeric: from 0 to 20)
G2 - second period grade (numeric: from 0 to 20)
G3 - final grade (numeric: from 0 to 20, output target)






















