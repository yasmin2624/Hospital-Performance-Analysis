📊 Hospital Performance Analysis – Power BI Dashboard
📌 Overview

This project presents a comprehensive Hospital Performance Analysis built using Power BI.
The dashboard evaluates key aspects of hospital operations, including:

Appointments performance

Admissions trends

Department utilization & revenue

Patient demographics & diagnoses

Staff distribution & workload

The goal is to uncover operational issues, identify improvement opportunities, and support data-driven decision making.

🗂️ Project Contents

The repository includes:

📁 Hospital-Performance-Analysis
│
├── 📄 Hospital_Dashboard.pbix        (Power BI file)
├── 📄 Report.pdf                     (Full detailed analysis report)
└──  📁 Dataset/                       (Raw data used in the project)
      ├── Appointments.csv
      ├── Admissions.csv
      ├── Patients.csv
      ├── Staff.csv
      ├── Rooms.csv
      └── ... etc


🎯 Objectives

The project aims to:

Measure hospital operational efficiency.

Analyze appointment completion, cancellation, and no-show behavior.

Evaluate inpatient admissions, room occupancy, and bed utilization.

Understand patient demographics and top diagnoses.

Assess staff workload distribution to detect imbalances.

Provide insights and recommendations for performance improvement.

📌 Dashboards Included
1️⃣ Appointments Dashboard

Covers key appointment KPIs:

Total Appointments

Completion, Cancellation, and Missed Rates

Appointment Revenue

Appointment trends over time

Distribution of booking modes (Online, Call, In-Person)

Payment mode revenue comparison

Highlights:

14.5% of appointments are lost due to cancellations/no-shows.

Online, Call, and In-Person booking methods are nearly equally used.

Digital Wallets generate the highest appointment revenue.

2️⃣ Admissions & Departments Dashboard

Focuses on inpatient insights:

Total admissions

Total rooms, total beds, and occupancy indicators

Room type distribution

Revenue from rooms, beds, and appointments

Top 5 departments by revenue and utilization

Length-of-stay analysis

Highlights:

Rooms and beds generate over 98% of total revenue.

Critical Care and Surgery are the highest-performing departments.

Large number of same-day admissions indicates possible data quality issues.

3️⃣ Patients Analysis Dashboard

Analyzes the hospital’s patient base:

Total patients & total visits

Average age and stay duration

Visit trends across time

Gender distribution

Age group segmentation

Top diagnoses and common medical conditions

Highlights:

Majority of patients are 45+ years old.

“General Checkup” is the most frequent diagnosis.

Visit volume peaks early in the year.

4️⃣ Staff & Workload Dashboard

Evaluates hospital workforce:

Total doctors, nurses, and support staff

Staff distribution by department

Doctor workload comparisons

Detection of workload imbalance

Highlights:

Strong imbalance in doctor workload (e.g., one doctor handling 500+ appointments).

The hospital has a healthy staff-to-patient ratio overall.

🛠️ Tools & Technologies

Power BI Desktop

Power Query for data cleaning

DAX for measures and KPIs

Data Modeling (Star Schema)

CSV/Excel datasets

📈 Key Insights Summary

Appointment loss rate is high and negatively affects revenue.

Revenue is heavily concentrated in a small number of departments.

Elderly population represents the largest age group.

Digital payments are widely adopted.

Staff workload distribution needs optimization.

💡 Recommendations

Implement appointment reminders to reduce no-shows.

Redistribute workload among doctors more evenly.

Improve data entry to fix same-day admission anomalies.

Optimize room pricing and occupancy strategies.

Enhance online booking and digital payment experiences.
