# Hospital Emergency Room – Patient Analytics

### Patient Volume | Admissions | Demographics | Waiting Time | Patient Satisfaction

[![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow?style=for-the-badge&logo=powerbi)](https://powerbi.microsoft.com/)
[![Excel](https://img.shields.io/badge/Microsoft%20Excel-Data%20Preparation-green?style=for-the-badge&logo=microsoftexcel)](https://www.microsoft.com/microsoft-365/excel)
![Data Analytics](https://img.shields.io/badge/Data-Analytics-blue?style=for-the-badge)
![Healthcare Analytics](https://img.shields.io/badge/Healthcare-Analytics-red?style=for-the-badge)

---

## 📌 Project Overview

The **Hospital Emergency Room – Patient Analytics** project analyses emergency room patient data to understand patient volume, admissions, demographics, referral patterns, waiting time and patient satisfaction.

The project converts raw patient-level data into an **interactive Power BI dashboard** designed to provide a simple and business-friendly view of important Emergency Room operational indicators.

The analysis covers patient records from:

> **April 2023 – October 2024**

The dashboard allows users to interactively analyse the data using filters such as **Gender, Age Group, Admission Date and Admission Status**.

---

## 🎯 Business Objective

The primary objective of this project is to demonstrate how raw healthcare operational data can be transformed into meaningful business insights.

### Key Objectives

- 👥 Understand overall Emergency Room patient volume.
- 🏥 Monitor admitted and non-admitted patients.
- 📊 Calculate and analyse admission rate.
- 👨‍👩‍👧 Analyse patient demographics.
- 🏥 Understand referral department distribution.
- ⏱️ Monitor average patient waiting time.
- 😊 Analyse available patient satisfaction information.
- 📈 Identify important operational patterns.
- 🎛️ Build an interactive Power BI dashboard for decision support.

---

# 📊 Key Performance Indicators

| KPI | Value |
|---|---:|
| 👥 **Total Patients** | **9,216** |
| 🏥 **Total Admissions** | **4,612** |
| 📊 **Admission Rate** | **50.04%** |
| ⏱️ **Average Wait Time** | **35.26 minutes** |
| 😊 **Average Satisfaction** | **4.998 / 10** |

---

# 🗂️ Dataset Description

The source dataset contains:

- **9,216 patient records**
- **12 fields**
- Admission information
- Patient demographics
- Referral department information
- Waiting time
- Patient satisfaction
- Additional patient-related information

### Dataset Coverage

**April 2023 – October 2024**

### Major Dataset Fields

| Category | Information |
|---|---|
| 👤 Patient Information | Patient ID, First Initial, Last Name |
| 📅 Admission Details | Admission Date, Admission Flag |
| 👨‍👩‍👧 Demographics | Gender, Age, Race |
| 🏥 Referral | Department Referral |
| 😊 Patient Experience | Satisfaction Score, Waiting Time |
| 📌 Additional Field | Patients CM |

> **Note:** The source dataset does not provide a business definition for the `Patients CM` field. Therefore, it has not been interpreted as a specific clinical or operational measure in this project.

---

# 🧹 Data Preparation

The source data was reviewed and prepared before developing the Power BI dashboard.

### Data Preparation Activities

- Reviewed patient-level records.
- Handled admission dates for time-based analysis.
- Created age-group categories.
- Categorised records without a department referral as **No Referral**.
- Reviewed admission status.
- Created KPI calculations.
- Analysed waiting time.
- Analysed available satisfaction responses.
- Prepared fields for interactive Power BI filtering.
- Reviewed data-quality limitations.

### Age Groups

The following age groups were created:

| Age Group |
|---|
| 0–17 |
| 18–29 |
| 30–44 |
| 45–59 |
| 60+ |

---

# 📈 Power BI Dashboard

The project was developed as a **single-page interactive management dashboard**.

### Dashboard Components

- 📌 KPI Cards
- 📈 Monthly Patient Volume
- 👴 Patients by Age Group
- 🏥 Admissions by Referral Department
- ⚥ Patient Distribution by Gender
- ⏱️ Average Wait Time by Admission Status
- 🌍 Patients by Race
- 🎛️ Interactive Slicers

### Dashboard Filters

Users can interactively filter the dashboard using:

- Gender
- Age Group
- Admission Date
- Admission Status

---

# 🖼️ Dashboard Preview

<p align="center">
  <img width="1082" height="602" alt="Screenshot 2026-10-06 235853" src="https://github.com/user-attachments/assets/90fa1479-211c-4914-ad94-f562a85b394f" />

---

# 🔍 Analysis & Key Findings

## 👥 1. Patient Volume

The dataset contains **9,216 Emergency Room patient records** covering the period from **April 2023 to October 2024**.

The monthly patient volume analysis helps identify changes in Emergency Room activity over the reporting period.

The dashboard provides a visual trend of patient activity, allowing users to identify periods with relatively higher or lower patient volumes.

---

# 🏥 2. Admission Analysis

The dataset contains:

- **4,612 admitted patients**
- **4,604 non-admitted patients**

### Admission Rate

**50.04%**

The admission outcome is almost evenly distributed between admitted and non-admitted patients.

This provides a useful basis for comparing operational measures such as waiting time across admission status.

---

# 👴 3. Age Group Analysis

| Age Group | Patients | Share of Patients |
|---|---:|---:|
| **0–17** | 1,971 | 21.4% |
| **18–29** | 1,452 | 15.8% |
| **30–44** | 1,755 | 19.0% |
| **45–59** | 1,731 | 18.8% |
| **60+** | 2,307 | 25.0% |

### Key Finding

The **60+ age group** is the largest patient category with **2,307 patients**, representing approximately **25%** of the total patient population.

The **18–29 age group** is the smallest category with **1,452 patients**.

---

# ⚥ 4. Gender Analysis

| Gender | Patients |
|---|---:|
| **Male** | 4,705 |
| **Female** | 4,487 |
| **NC** | 24 |

The gender distribution is relatively balanced, with a slightly higher number of male patients.

---

# 🌍 5. Race Distribution

The dataset includes multiple race categories.

### Major Categories

| Race | Patients |
|---|---:|
| **White** | 2,571 |
| **African American** | 1,951 |
| **Two or More Races** | 1,557 |

Other categories include:

- Asian
- Declined to Identify
- Pacific Islander
- Native American / Alaska Native

### Key Finding

**White patients** represent the largest race category in the dataset, followed by **African American** and **Two or More Races**.

---

# 🏥 6. Referral Department Analysis

| Referral Category | Patients |
|---|---:|
| **No Referral** | 5,400 |
| **General Practice** | 1,840 |
| **Orthopedics** | 995 |
| **Physiotherapy** | 276 |
| **Cardiology** | 248 |
| **Neurology** | 193 |
| **Gastroenterology** | 178 |
| **Renal** | 86 |

### Key Finding

**No Referral** is the largest category with **5,400 records**.

Among the named referral departments, **General Practice** has the highest patient volume, followed by **Orthopedics**.

---

# ⏱️ 7. Waiting Time Analysis

The overall average patient waiting time is:

## **35.26 minutes**

### Waiting Time by Admission Status

| Admission Status | Average Wait Time |
|---|---:|
| **Not Admitted** | 35.55 minutes |
| **Admitted** | 34.97 minutes |
| **Overall** | **35.26 minutes** |

### Key Finding

The average waiting time for admitted and non-admitted patients is very similar.

This suggests that admission status alone does not show a major difference in average waiting time within this dataset.

---

# 😊 8. Patient Satisfaction Analysis

The overall average recorded satisfaction score is:

## **4.998 / 10**

However, satisfaction data is available for only:

**2,517 out of 9,216 patient records**

### Satisfaction Response Coverage

**Approximately 27.3%**

Therefore, the average satisfaction score should be interpreted as the average of **recorded responses**, rather than as a score representing the complete patient population.

### Satisfaction by Admission Status

| Admission Status | Average Satisfaction |
|---|---:|
| **Not Admitted** | 4.91 / 10 |
| **Admitted** | 5.08 / 10 |

Admitted patients have a slightly higher average recorded satisfaction score than non-admitted patients.

However, the difference is relatively small and should be interpreted carefully because satisfaction responses are available for only a portion of the total patient population.

---

# 💡 Key Business Insights

### 👥 High Overall Patient Volume

The dataset contains **9,216 Emergency Room patient records**, providing a strong base for operational analysis.

### 🏥 Balanced Admission Outcome

The admission rate is **50.04%**, with almost equal numbers of admitted and non-admitted patients.

### 👴 Older Patients Form the Largest Age Group

Patients aged **60+** represent the largest age category with **2,307 records**.

### ⚥ Balanced Gender Distribution

Male and female patient counts are relatively close, with only a small difference between the two groups.

### 🏥 High Number of No-Referral Cases

**5,400 records** are categorised as **No Referral**, making this an important area for operational and data-quality review.

### ⏱️ Average Waiting Time Around 35 Minutes

The overall average waiting time is **35.26 minutes**, with admitted and non-admitted patients showing similar averages.

### 😊 Satisfaction Data Has Limited Coverage

Only approximately **27.3%** of patient records contain satisfaction scores.

Therefore, satisfaction findings should be treated as **response-based insights**.

---

# 🎯 Recommendations

Based on the analysis, the following areas could be considered for further operational review:

### 1. Monitor Waiting Time

Regularly monitor waiting time by:

- Admission status
- Age group
- Referral category
- Date/month

This can help identify areas where operational improvements may be required.

### 2. Review No-Referral Records

The high number of **No Referral** records should be reviewed to determine whether they represent genuine non-referral cases or missing referral information.

### 3. Improve Satisfaction Response Collection

Increasing satisfaction response coverage would provide a broader understanding of patient experience.

### 4. Monitor Patient Volume

Track patient volume periodically to identify changes in Emergency Room demand.

### 5. Monitor Admission Rate

Regular monitoring of admission rate can help identify changes in patient admission patterns.

### 6. Use Demographic Analysis Carefully

Demographic information should be used as a supporting operational indicator and should not be used to make assumptions about patient needs that are not directly supported by the data.

---

# 📊 Dashboard Design

The Power BI dashboard was designed as a **single-page management view**.

### Visuals Used

| Visual | Purpose |
|---|---|
| **KPI Cards** | Monitor key performance indicators |
| **Line Chart** | Analyse monthly patient volume |
| **Column Chart** | Analyse patients by age group |
| **Bar Chart** | Analyse referral department |
| **Donut Chart** | Analyse gender distribution |
| **Column Chart** | Compare waiting time by admission status |
| **Bar Chart** | Analyse race distribution |
| **Slicers** | Enable interactive filtering |

---

# 🛠️ Tools & Technologies

### Data Preparation

- Microsoft Excel
- CSV

### Data Visualisation

- Microsoft Power BI

### Power BI Skills

- Data preparation
- Data modelling
- DAX measures
- KPI creation
- Data categorisation
- Slicers
- Interactive visualisations
- Dashboard design
- Business reporting

### Data Analytics Skills

- KPI analysis
- Demographic analysis
- Admission analysis
- Operational analysis
- Trend analysis
- Data quality review
- Business insight generation

---

# 🧠 Skills Demonstrated

| Area | Skills Demonstrated |
|---|---|
| **Data Preparation** | Data review, cleaning, categorisation and validation |
| **Data Analysis** | KPI, demographic, admission and operational analysis |
| **Power BI** | Data modelling, DAX, slicers, KPI cards and interactive visuals |
| **Business Intelligence** | Dashboard development and management reporting |
| **Data Quality** | Missing-value awareness, response coverage and limitations |
| **Business Reporting** | Insight generation and recommendation development |

---

# ⚠️ Data Quality & Limitations

## Patient Satisfaction

Satisfaction scores are available for only a portion of the total patient population.

Therefore, the average satisfaction score represents **recorded responses only**.

---

## Referral Information

A significant number of records are categorised as **No Referral**.

The source dataset does not clarify whether these records represent genuine non-referrals or unavailable referral information.

---

## Patients CM

The `Patients CM` field is binary, but the source dataset does not provide a business definition.

Therefore, this field has not been used for clinical or operational interpretation.

---

## Analytical Limitation

This project identifies patterns and relationships in the available data.

It does **not** establish:

- Medical causes
- Clinical outcomes
- Treatment effectiveness
- Patient-level medical conclusions

---

## Patient Privacy

The source dataset contains patient-level identifiers.

This project focuses on **aggregated analytical information** rather than individual patient-level analysis.

If publishing the dataset publicly, identifiable or sensitive patient information should be removed or anonymised.

---


### 👨‍💻 Project Author

### Anurag Kumar Poddar

**Data Analyst | Business Analyst | Power BI | SQL | Excel | Python**

This project was developed as part of my **Data Analytics Portfolio** to demonstrate practical skills in healthcare data analysis, Power BI dashboard development, KPI reporting, and business insight generation.

---

## 💡 Project Takeaway

> **Behind every number, there is a story.  
> Behind every dashboard, there should be a decision.**

This project demonstrates how raw Emergency Room data can be transformed into **clear insights, meaningful KPIs, and an interactive dashboard** that supports better operational understanding.

### 📊 Analyse. Visualise. Understand. Improve.

**Thank you for exploring this project!**

⭐ If you found this project useful, consider giving the repository a star.

**— Anurag Kumar Poddar**
