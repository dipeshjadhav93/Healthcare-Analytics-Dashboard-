f5# Hospital Analytics & Performance Dashboard

A 4-page Power BI dashboard built on 10,000 synthetic patient records across 5 hospitals and 8 departments. It covers hospital overview KPIs, patient demographics and admissions, and clinical metrics.

## Project purpose
To demonstrate dashboard design, DAX, and data storytelling in Power BI, combined with my 14+ years of clinical and laboratory experience. The dataset is synthetic, so this project shows skills, not real-world clinical findings.

## Dataset
- 10,000 synthetic patient records
- 5 hospitals, 8 departments
- Fields include age, gender, blood group, department, hospital, revenue, BMI, glucose, cholesterol, heart rate, and outcome
- No real patient data is used

## Dashboard pages

### 1. Summary Report
Overview of the pages, data, and a note on the synthetic dataset.

![Summary Report](Screenshot%202026-11-25%20004434.png)

### 2. Executive Overview
KPI cards for total patients, total revenue, average age, and number of hospitals, plus daily revenue trend and gender distribution.

![Executive Overview](Screenshot%202026-11-25%20004453.png)


### 3. Patient Analytics
Patient profile by age group, gender, and blood group, plus admissions by department and hospital.

![Patient Analytics](Screenshot%202026-11-25%20004518.png)

### 4. Clinical Performance
Average BMI, glucose, cholesterol, and heart rate across gender, department, age group, and patient outcome.

![Clinical Performance](Screenshot%202026-11-25%20004537.png)

## Key insights
1. **Scale:** 10,000 patients generated 26.18M in total revenue (about 2,618 per patient) across 5 hospitals. Daily revenue stayed around 0.85M with no clear trend.
2. **Age profile:** The 65+ group is the largest (about 3.4K patients), and the average patient age is 53.5. The 0-18 group is the smallest.
3. **Blood groups:** O+ (about 3.9K) and A+ (about 3.4K) together make up roughly 73% of patients.
4. **Admissions:** Emergency has the most admissions (about 1,300), and Neurology the fewest (about 1,190). Patients are evenly split across hospitals (1,957 to 2,037 each).
5. **Clinical metrics:** Average BMI (26.3), glucose (about 100), cholesterol (about 199), and heart rate (about 74) are almost identical across gender, department, age group, and outcome. This is expected in synthetic data, and I noted it on the dashboard rather than inventing a trend.

## Tools
Power BI, DAX

## Files
- Power BI dashboard file (`.pbix`)
- Screenshots of all 4 dashboard pages (`.png`)

## About me
Healthcare professional (BSc MLT) with 14+ years of clinical and laboratory data experience, moving into data analytics. I use my healthcare domain knowledge to build analytics that make sense to clinicians and managers.
