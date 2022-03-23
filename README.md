# No-Show Appointments Data Analisis
## by (Mohamed Mounir Awadallah)


## Dataset

This dataset collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. A number of characteristics about the patient are included in each row.

>- `ScheduledDay` tells us on what day the patient set up their appointment.
>- `Neighborhood` indicates the location of the hospital.
>- `Scholarship` indicates whether or not the patient is enrolled in Brasilian welfare program Bolsa Família.


## Summary of Findings

### General statistics

- The average **age** of the patients is **37 years**.
- The percentage of patients who have a **scholarship** is **10%**.
- The percentage of patients suffering from **diabetes** is **20%**.
- The percentage of patients suffering from **hypertension** is **7%**.
- The percentage of patients suffering from **alcoholism** is **3%**.
- The percentage of patients suffering from **handicap** is **2%**.
- The Percentage of patients who **received SMS** is **32%**.
- The percentage of patients who **did not attend** is **20%**.
- The average number of **days to wait for appointment** is **10 days**.


### Factors affecting no-show 

- **The rate of no-show increases for patients who have scholarship.** 
- **The rate of no-show in patients with Hypertension is lower than in patients without.**
- **The rate of no-show in patients with Diabetes is lower than in patients without.**
- **The no-show rate for patients with handicap increases with the increase in handicap.**
- **The no-show rate for patients who received SMS is higher than for patients who did not receive.**
- **The no-show rate increases with the increase in waiting days for daysless than 40 days.**
- **The ratio of no-show for more than 40 days is very low.**



## Conclusions

Two kinds of factors affected the rate of a no-show.

- **factors dependent on patients,** such as if the patients have a scholarship and whether they suffer from chronic diseases or disabilities.

- **factors dependent on systems,** such as if the patients received SMS and the waiting days.