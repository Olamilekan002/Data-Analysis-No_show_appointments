# Data-Analysis-No_show_appointments
# Project: No-show appointments

## Table of Contents
* Introduction
* Data Wrangling
* Exploratory Data Analysis
* Conclusions

### Introduction

#### Dataset Description
This dataset collects information from 110,527 medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. The dataset has 14 columns of characteristics about the patient. The columns are

● PatientId - a unique identification for each patient

● AppointmentID - a unique identification for each set appointment

● Gender - patient's gender

● ScheduledDay - the day the patient set up their appointment

● AppointmentDay - day Date of appointment

● Age - Age of the patient

● Neighbourhood - indicates the location of the hospital

● Scholarship - indicates whether or not the patient is enrolled in Brasilian welfare program Bolsa Família

● Hipertension - indicates if patient is hypertensive

● Diabetes - indicates if patient has diabetes

● Alcoholism - indicates if patient consumes alcohol

● Handcap- indicates if patient is handicap

● SMS_received - indicates if patient recieves any sms

● No-show - the target, indicates is patient shows up. (‘No’ if the patient showed up to their appointment, and ‘Yes’ if they did not show up.)

# Question(s) for Analysis
- What factors are important for us to know in order to predict if a patient will show up for their scheduled appointment?
- Which Top 5 neighbourhoods as highest No-show?
- What is the likelihood of young patients Not Show-Up?
- Is there any relationship between age; hipertension, diabetes, and handicap?

## Conclusions
From the analysis, it was discovered that gender, age, neighborhood, and Day of appointment are important to predict if a patient will show up. It was discovered that more Females are likely to Show-Up than Male, although the data is imbalanced towards gender having more Females than Male.

The Age group of Infant and Old Age also Shows-Up more for Appointment compared to other groups. The young patients comprising the Infant and Youth Age group have a 54% likelihood of not Showing Up.

Some Neighborhoods show a record of regular Showing Up while some Neighborhood like SANTOS DUMONT has low patients Showing Up. This can be to so many reasons that can be further researched like closeness and accessibility to the hospital.

It was also seen that patients show up more if the Appointment Day is within the first 10 days of the month compared to the middle of the Month. Also, SMS Received by patients has little or no effect on Showing Up, this conclusion is limited because the majority of patients did not receive SMS.

Further analysis shows that cases of Hypertension and Diabetes increase from Youth to Old Age while Handicap is common to all but more for the Old Age.

## LIMITATIONS:
* During the analysis a negative value of age was identified as an outlier which was dropped. Having domain knowledge about the data might have helped to understand why this was so or if it was a mistake.

* The SMS_received was highly imbalanced and the relationship with Showing up may not be considered.

* Data about the population or closeness of a Neighboorhood to the hospital would help to further analyse the cause.

* Having data about the reason for the appointment might help to know why some eventually not show up.
