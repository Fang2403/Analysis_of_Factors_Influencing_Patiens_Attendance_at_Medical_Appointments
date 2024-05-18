<a id='intro'></a>
## Introduction

Why do 30% of patients miss their scheduled appointments?

This project is aim to analyze what factors are important for us to know in order to predict if a patient will show up for their scheduled appointment?.

### Dataset Description 

This dataset(original source on [Kaggle](https://www.kaggle.com/datasets/joniarroba/noshowappointments)) collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. The dataset contains several variables that could potentially impact patient attendance at appointments.

**Data Dictionary**

* PatientId: Unique identifier for each patient.
  
* AppointmentID: Unique identifier for each appointment.
  
* Gender: Gender of the patient (M for male, F for female).
  
* ScheduledDay: The date and time when the appointment was scheduled.
  
* AppointmentDay: The date of the actual appointment.
  
* Age: Age of the patient.
  
* Neighbourhood: The neighborhood where the appointment is scheduled.
  
* Scholarship: Indicates whether the patient is enrolled in the Bolsa Família welfare program (0 for not enrolled, 1 for enrolled).
  
* Hipertension: Indicates whether the patient has hypertension (0 for no, 1 for yes).
  
* Diabetes: Indicates whether the patient has diabetes (0 for no, 1 for yes).
  
* Alcoholism: Indicates whether the patient has alcoholism (0 for no, 1 for yes).
  
* Handicap: Indicates the level of handicap of the patient (0 for no handicap, 1-4 for varying degrees of handicap).
  
* SMS_received: Indicates whether the patient received an SMS reminder for the appointment (0 for no, 1 for yes).
  
*  No-show: Tells us if the patient did not show up to their appointment; "No" if they did show up, and "Yes" if they did not.
  
### Question for Analysis

* Is there any factor that would impact patients apperance? 

* If yes, what are the main three factors?

* If sending SMS reminder to patient boost the showing rate?
