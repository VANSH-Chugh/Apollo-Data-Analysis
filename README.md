# 🏥 Apollo Hospitals: Data Analysis & Dashboard Project

A healthcare data analysis project focusing on hospital workflow, patient diagnosis, and billing patterns using Power BI. This dashboard enables stakeholders to monitor performance metrics, identify high-cost diagnosis trends, and optimize patient care operations.

---

## 🎯 Objectives

- Understand diagnosis trends and their financial impact.
- Compare billed vs. insured amounts across diseases.
- Analyze bed occupancy by category (ICU, General, Private).
- Track patient flow across admit, discharge, and follow-up timelines.
- Enable quick feedback tracking by doctor for service quality.

---

## 📂 Dataset Overview

- **Source**: Internal project dataset from Apollo Hospitals (anonymized).
- **Sheet Used**: `Sheet1` only.
- **Data Fields**:
  - `Patient_ID`, `Admit Date`, `Discharge Date`, `Follow Up Date`
  - `Diagnosis Type`, `Bed_Occupancy`
  - `Billing Amount`, `Health Insurance Amount`
  - `Feedback Volume`, `Doctor Name`

---

## 🔍 Key Insights

- **High Volume Diagnoses**: Viral Infection (2K+), Flu (1.7K+), Malaria (1.4K+) were the top occurring conditions.
- **Revenue Trends**: Viral infections generate the highest billing and insurance claims, followed by Flu and Malaria.
- **Insurance Gap**: Insurance coverage tends to fall short of billed amounts across nearly all diagnosis types.
- **Bed Demand**: Private beds were most in demand, with ICU showing least occupancy, suggesting scope for resource reallocation.
- **Doctor Feedback**: Every listed doctor had a uniform feedback volume, hinting at either data input constraints or uniform patient allocation.
- **Low-Cost Cases**: Fractures and Pneumonia had relatively lower billing amounts and fewer patient counts.

---

## 💡 Recommendations

- **Resource Planning**: Increase private/general bed capacity based on usage trends.
- **Insurance Optimization**: Reassess pricing models or negotiate better insurance rates for high-burden diagnoses.
- **Diagnosis Forecasting**: Use top diagnosis trends for seasonal inventory and staff planning.
- **Data Cleaning**: Doctor feedback volume appears fixed—may require validation or richer input design.

---

## 📊 Dashboard Preview

### 🌐 Global View (All Patients)

Provides a macro-level overview of:

- Bed occupancy distribution  
- Top diagnosis types  
- Billing vs. insurance comparisons  
- Timeline for patient journey  
- Feedback distribution by doctors

![Global Dashboard](Images/Dashboard%20-%20Apollo.png)

---

### 👤 Individual Patient View

When a `Patient_ID` is selected, the dashboard shows:

- Personalized admit, discharge & follow-up timeline  
- Diagnosis & bed type used  
- Billing vs. insurance breakdown for the case  
- Feedback linked to assigned doctor

![Individual Patient Dashboard](https://github.com/VANSH-Chugh/Apollo-Data-Analysis/blob/main/Images/Per%20Patient.png)

---

## ✅ Tools Used

- **Power BI**: For all dashboard creation, data transformation, and insight visualization.
- **Excel**: As the source of raw data.
- **DAX**: For custom measures and conditional formatting.
- **Power Query**: For data shaping and cleaning.

---

## 🧾 Conclusion

This project demonstrates how Power BI can turn hospital data into actionable healthcare insights. The interactive dashboard supports both high-level and patient-specific analysis, making it useful for hospital admins, billing teams, and diagnosis planners alike.

---

