# hospital-performance-dashboard-excel-
Excel dashboard report analyzing 1,000 hospital visits ( 2024-2025): admissions, departmental billing, insurance coverage and unpaid bills, with recommendations for management
[README (1).md](https://github.com/user-attachments/files/34517254/README.1.md)
# Secure Life General Hospital Performance Analysis

An Excel dashboard and written report that turn two years of hospital visit records (January 2024 to December 2025) into a clear picture of admissions, billing, insurance coverage and payment status.

![Dashboard](images/dashboard.png)

## Business Problem

Secure Life General Hospital records every patient visit, bill and insurance claim, but management has no consolidated report of its operational and financial performance. Management had noticed changes in admissions, outstanding bills and insurance coverage across departments and wanted answers.

## Questions Answered

1. How many patient visits were recorded?
2. Which departments receive the most patients?
3. Which departments generate the highest total bills?
4. What is the average length of stay by department?
5. What share of bills is Paid, Pending or Partially Paid?
6. How much was billed, and how much remains outstanding?
7. How does insurance coverage vary by department and diagnosis?
8. Which age groups account for the most visits?
9. How do admissions and billing change over time?
10. Which areas need management attention?

## Dataset

- 1,000 patient visits, 15 columns (each row is one visit, not necessarily one unique patient)
- Columns: Patient ID, Patient Name, Age, Gender, Admission Date, Discharge Date, Department, Diagnosis, Total Bill Amount, Insurance Coverage (%), Payment Status
- No missing values, duplicate rows or duplicate IDs

**Columns I added:** Length of Stay, Age Group, Insurance Amount, and Bill patient is paying (patient's share).

## Tools

Microsoft Excel: formulas, PivotTables, PivotCharts, timelines and dashboard design.

## Key Findings

- **Volume:** 1,000 visits (508 in 2024, 492 in 2025). General handles the most patients (25.2%).
- **Billing:** $8,053,143 billed in total. Orthopedics, Cardiology and Neurology generate 72.8% of billing from only 40.5% of visits.
- **Length of stay:** 4.8 days on average, from 2.0 (Emergency) to 8.4 (Orthopedics).
- **Payment status:** 56.4% Paid, 25.7% Pending, 17.9% Partially Paid.
- **Outstanding:** about $580K of patient-owed money on Pending bills, and up to $1.03M including Partially Paid bills.
- **Insurance:** covers about 75% of charges. Asthma (61.5%), Arrhythmia (63.5%) and Epilepsy (67.9%) have the lowest average coverage; 44 visits had no coverage.
- **Trend:** billing fell 5.1% from 2024 to 2025. Q4 is the peak quarter and November the busiest month.

## Recommendations

- Follow up on Pending bills first, starting with Pediatrics (28.8% pending) and General (27.0%), and set up payment reminders.
- Record the balance remaining on Partially Paid bills so the true outstanding amount can be reported.
- Review pricing and length of stay in Orthopedics, Cardiology and Neurology.
- Offer payment plans and insurance guidance for low-coverage diagnoses and uninsured patients.
- Plan staffing and bed capacity for Q4 and November.

## Assumptions and Limitations

- "Outstanding" means the patient's share of Pending bills. The data does not show whether insurers have paid their share.
- The data does not show how much of each Partially Paid bill has been settled.
- Years are assigned by admission date.
- There is no unique patient identifier, so repeat visits cannot be measured reliably.

## Repository Contents

| File | Description |
|---|---|
| `Hospital_Patients_Dashboard.xlsx` | Dataset, PivotTables and interactive dashboard |
| `Secure_Life_General_Hospital_Performance_Report.pdf` | Full written report |
| `Problem_Statement_and_Data_Dictionary.pdf` | Original brief and column definitions |
| `images/` | Dashboard screenshots |

## How to Use the Dashboard

Download the `.xlsx` file and open it in Microsoft Excel (2013 or later). Use the Admission Date timelines to filter the charts by period.

## Author

**Dasho Okikioluwa**: Statistics student, Federal University of Technology Akure
[htttps://www.linkedin.com/in/okikioluwa-dasho-93abba38b](#) | [okikioluwadasho1@gmail.com](#)
