# HEALTHCARE INSURANCE DASHBOARD
## Project Overview
This Project is based on the healthcare domain.An Insurance company is having the data of the Patients who had insured.The data consists of the charges of the each patients insured based on their data like their gender,age,smoking habit,family size,bmi and region.

## Problem Statement 
The Insurance company of the healthcare domain need to know the estimated expenditure need to be spent on the Patients who had insured but they have only the data of the patients and their charges.The Objective of this project is to predict the estimated expenditure based on the factors and charges of the patients insured.

## Steps followed 
### Data Structuring/Formatting
- Replaced the values in the smoking column with smoker and non-smoker.
- Created a new column named health which gives the details that the patient is healthy or unhealthy based on the BMI using the below formula.
  
  ![Screenshot 2024-02-18 092636](https://github.com/Sudarson-analyst/Excel-Project/assets/159156381/d3b81011-c186-4704-b436-4bbbd27a8240)
  
- Here the BMI ranging between 18.5 to 24.9 are consider as healthy as per the scientific data.The IF statement will check for the data based on the two conditions
    - 1.is equal to or above the value 18.5
    - 2.is equal to or below the value 24.9
  if both condition is satisfied it returns healthy else unhealthy.
- Changed the format of the charges column with currency of the United States.

### Creating Charts and Visualisation
Created different charts like donut,pie,bar and funnel chart.The Donut charts was created for the no of patients based on the gender,smoking and health.The Pie chart was created for Total Children based on their health.The Bar chart was created for Total Children for the number of children and their parents health,number of patients based on their age.Also created KPI's like Numbers of Patients,Average Age and Average Expenditure.The Funnel Chart was created for the distribution of number of patients based on their region.

### Conclusion
#### Prediction

- No of Patients who has the possibility to visit the hospital for a check up or any kind of treatment comes under the category of unhealthy and smoking.
- No of Patients who are unhealthy and either smoker nor non-smoker are 1116 and the average charges for each Patients are $13845.49.So the expenditure to be spent is $15.45 Millions
- No of Patients who are healthy and a smoker are 50 and the average charges for each Patients are $19942.22.So the expenditure to be spent is $0.99 Millions

Therefore the Total Expenditure to be spent by the HealthCare Insurance Company is estimated as $16.5 Millions(approximately).

#### Limitations
The Predicted value is approximation of the data and the accuracy is negligible.
