# Medical Appointment No-Show Analysis
Project Overview
This project aims to analyze over 110,000 medical appointments to identify key patterns and trends in patient attendance. The insights gathered from this analysis can help healthcare providers develop targeted strategies to enhance patient engagement and ensure better resource utilization.

##Problem Statement
In an effort to improve patient attendance and reduce no-show rates, this project investigates the factors influencing appointment attendance. By understanding these patterns, healthcare providers can tailor their strategies to improve patient attendance, from targeted reminders to special assistance for older adults.

##Key Findings
Female Dominance: Female patients are booking more appointments than their male counterparts.
Age Matters: Show rates are generally balanced across age groups, except for older adults (61-81), who show higher no-show rates.
Neighborhood Trends: Each neighborhood exhibits an average 80% show rate, highlighting consistent patient behavior across locations.
Scholarship Influence: Patients without scholarships show up more (80%) compared to those with scholarships (75%).
Health Conditions: Patients with hypertension (85%) and diabetes (83%) have higher show rates than those without these conditions.
SMS Reminders: Receiving an SMS reminder correlates with a lower show rate (72%), suggesting a need for improved reminder strategies.
Weekly Patterns: Appointments are rarely scheduled on Saturdays and never on Sundays, reflecting typical medical office hours.
Data Description


##The dataset contains the following columns:

PatientId: Identification of a patient.

AppointmentID: Identification of each appointment.

Gender: Gender of the patient ('F' for female, 'M' for male).

ScheduledDay: The day someone called or registered the appointment.

AppointmentDay: The day of the actual appointment.

Age: Age of the patient.

Neighbourhood: The location of the hospital.

Scholarship: Whether or not the patient is enrolled in the Brazilian welfare program Bolsa Família.

Hypertension: Whether or not the patient has hypertension.

Diabetes: Whether or not the patient has diabetes.

Alcoholism: Whether or not the patient is an alcoholic.

Handicap: Whether or not the patient is handicapped.

SMS_received: Whether or not the patient received an SMS reminder.

No-show: Whether or not the patient showed up to their appointment ('Yes' for no-show, 'No' for show).

