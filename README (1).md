# No-show appointments analysis

## Overview

The project focused on analyzing **medical appointments in Brazil** and focused on the question of whether or not patients show up for their appointment as scheduled.

The dataset for the analysis "No-show appointment's" was gotten from [Kaggle](https://www.kaggle.com/joniarroba/noshowappointments)

## Question(s) for Analysis

- what is the effect of **elapsed time**(day interval between Scheduled day and Appointment day) to not show up for scheduled appointment?
- What factors are important for us to know in order to predict if a patient will show up for their scheduled appointment?


## Findings

In the exploration, elapsed time have high impact on patients not showing for their appointment. The lower the elapsed time given the high chances of not showing up for their appointment. Exploring the effect of age, gender, scholarship and SMS received against No_show revealed that gender and scholarship have little or no effect on showing up for the appointment. The analysis has also revealed that appointment reminder-messages and age of the patient have effect on patient not showing up. The lower the reminder message the higher the rate of No-show and the young patients have high rate of no show, the lower the age the higher the chances of no show.

## Limitation

- No use of machine learning and infrential statistics is a big limitation in this project.
- Having some value in the dataset which are very difficult to drop because the row have some useful value needed for the project.