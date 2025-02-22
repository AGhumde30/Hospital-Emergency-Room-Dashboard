# Hospital Emergency Room Dashboard (Interactive dashboard creation using MS Excel)
## Project Objective
Create a Hospital Emergency Room Analysis Dashboard in Power BI to improve efficiency and provide useful insights. This dashboard will help stakeholders monitor, analyze, and make better decisions for managing patients and improving services!
## Dataset used
- <a href="https://github.com/AGhumde30/Hospital-Emergency-Room-Dashboard/blob/main/Dashboard.xlsx">Dataset<a>
# KPI's
## Number of Patients:
Count the total number of patients visiting the ER each day.
Show a daily trend with an area sparkline to spot patterns like busy days or seasonal trends.
## Average Wait Time:
Find the average time patients wait to see a medical professional.
Use an area sparkline to track daily changes and highlight days with longer wait times that might need improvements.
## Patient Satisfaction Score:
Check the average daily satisfaction score of patients to assess service quality.
Use an area sparkline to show trends, spot drops in satisfaction, and link them to busy times or challenges.
# Charts to Create
## Patient Admission Status: 
Show how many patients were admitted vs. not admitted.

## Patient Age Distribution: 
Group patients by age.

## Timeliness: 
Measure the percentage of patients seen within 30 minutes.

## Gender Analysis: 
Display the number of patients by gender. 

Department Referrals: 
Check which departments patients are referred to the most.
# DAX Formulas Used
## DAX Formula for Age Group : 
=IF([Patient Age]>=70,"70-79",IF([Patient Age]>=60,"60-69",IF([Patient Age]>=45,"45-59",IF([Patient Age]>=30,"30-44",IF([Patient Age]>=15,"15-29",IF([Patient Age]>=5,"05-14","0-4"))))))
## DAX Formula For Patient Attend Status :
=IF([Patient Waittime]<30,"Within Time","Delay")
# Dashboard 
![Final Dashboard Of Hospital Emergency Room](https://github.com/user-attachments/assets/c972e561-5cf8-4e86-a98a-9476704ac88d)

