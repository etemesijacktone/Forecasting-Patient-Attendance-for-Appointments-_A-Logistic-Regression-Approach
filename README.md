# Forecasting Patient Attendance for Appointments: A Logistic Regression Approach

## Introduction

This project involves an analysis of patient records in Brazil to determine the attendance rates of scheduled medical appointments. The aim of the project is to address the following research questions:

Q1. In general, what sex is associated with the highest no-show rate?

Q2. What age bracket is associated with the highest number of missed appointments?

Q3. What day of the week registered the highest number of missed appointments?

Q4. What are the five leading hospital neighbourhoods in terms of alcoholism cases? How do these neighbourhoods compare in terms of missed patient appointments?

Q5. Is there a correlation between the number of days a patient in a given region has to wait for an appointment and the number of missed appointments in that particular region?

Q6. Can a model be built to predict if a patient will show up for an appointment?

The dataset used for this analysis consists of information from 110,527 medical appointments in Brazil. Each row contains various characteristics of the patient.

The dataset comprises 14 columns, which are described as follows:

1. PatientId: The unique ID assigned to each patient.
2. AppointmentID: The unique ID assigned to each appointment.
3. Gender: The gender of the patient.
4. ScheduledDay: The date when the patient scheduled the appointment.
5. AppointmentDay: The date when the patient is expected to attend the appointment.
6. Age: The age of the patient.
7. Neighbourhood: The location where the appointment takes place.
8. Scholarship: Indicates whether the patient is enrolled in the Brazilian welfare program.
9. Hypertension: Indicates whether the patient has hypertension.
10. Diabetes: Indicates whether the patient has diabetes.
11. Alcoholism: Indicates whether the patient has alcoholism.
12. Handicap: The number of handicaps the patient has.
13. SMS_received: Indicates whether the patient received an SMS reminder for the appointment.
14. No-show: Indicates whether the patient showed up for the appointment or not.

By analyzing these variables, we can gain insights into the factors that contribute to missed patient appointments in Brazil and potentially develop predictive models to enhance appointment attendance rates.

### Business Applications

These applications demonstrate how the machine learning model predicting patient attendance can be applied in various industries beyond healthcare, enabling businesses to optimize their operations and enhance customer experience.

1. Healthcare Service Providers: Healthcare facilities can utilize the insights from the analysis to develop targeted strategies and interventions to reduce missed appointments. They can implement reminder systems, tailored communication, or appointment rescheduling options to improve patient attendance.

2. Hospitality Industry: Hotels, restaurants, and other service-based industries that rely on customer reservations can benefit from the analysis. By implementing a similar prediction model, they can anticipate the likelihood of no-shows for reservations and optimize resource allocation accordingly, minimizing operational disruptions.

3. Insurance Providers: Insurance companies can leverage the predictive model to assess the risk of missed appointments for policyholders. This information can help insurance providers tailor their coverage plans, premiums, and policy terms based on the likelihood of missed appointments, ultimately improving the overall efficiency of healthcare insurance.

4. Appointment Scheduling Platforms: Companies offering appointment scheduling platforms can integrate a prediction model based on the analysis. This would help clients optimize their schedules by identifying high-risk appointments and allocating resources accordingly.

5. Transportation Services: Businesses providing transportation services to clients for appointments, such as medical transportation companies, can use the prediction model to optimize their resources. By identifying appointments with a high probability of being missed, they can prioritize and allocate transportation services more efficiently.


