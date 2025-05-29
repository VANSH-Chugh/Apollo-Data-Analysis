# 🏥 Apollo Hospitals Data Analysis – Patient Workflow & Revenue Insights

## 📌 Project Description

This project explores operational efficiency, diagnosis trends, and revenue patterns at Apollo Hospitals using real-world simulated data. Built with **Power BI** and **Excel**, it identifies bottlenecks in hospital workflows, reveals treatment-wise billing gaps, and aids in optimizing bed occupancy and insurance planning. The dashboard equips stakeholders with actionable insights to make informed strategic decisions.

---

## 🎯 Objectives

- Understand the **distribution of diagnoses** to identify most common health concerns  
- Analyze **bed occupancy trends** across Private, General, and ICU wards  
- Visualize the **feedback volume per doctor** to assess doctor-patient engagement  
- Compare **billing vs insurance amounts** by diagnosis for financial planning  
- Evaluate the **workflow timeline**: Admit → Discharge → Follow-up  

---

## 📁 Dataset Overview

- **Source:** Simulated dataset for Apollo Hospital's patient records  
- **File Name:** `Apollo Hospitals Data Analysis Dataset.xlsx`  
- **Sheet Used:** Sheet1 only  
- **Time Range:** 05-Dec-2022 to 06-Mar-2024  
- **Total Billing:** ₹190.43 Million+

### 📄 Key Fields

| Column Name            | Description                          |
|------------------------|--------------------------------------|
| Patient_ID             | Unique patient identifier            |
| Admit Date             | Date of admission                    |
| Discharge Date         | Date of discharge                    |
| Follow-Up Date         | Scheduled follow-up consultation     |
| Bed_Occupancy          | Type of bed used (Private, General, ICU) |
| Diagnosis_Type         | Type of diagnosis (Viral, Flu, etc.) |
| Billing_Amount         | Total charge billed                  |
| Insurance_Amount       | Insurance claim amount               |
| Doctor_Name            | Doctor assigned to the patient       |
| Feedback Volume        | Number of feedback entries per doctor|

---

## 📊 Dashboard Preview

![Apollo Dashboard](Images/Dashboard%20-%20Apollo.png)

---

## 💡 Insights

- 🦠 **Diagnosis Trends**:  
  - **Viral Infections (2K)**, **Flu (1.72K)**, and **Malaria (1.43K)** are most frequent.  
  - **Fractures** and **Pneumonia** appear in lower volumes.

- 🛏️ **Bed Occupancy**:  
  - **Private Beds** are most preferred (~3.4K patients), followed by **General** and **ICU**, indicating skewed demand for premium services.

- 🧑‍⚕️ **Doctor Feedback**:  
  - All seven doctors have ~1.02K feedback each—showing balanced patient load or automated distribution.

- 💰 **Billing vs Insurance**:  
  - Viral infections generated the **highest billing and insurance coverage**.  
  - For less severe conditions like **fractures**, billing persists but **insurance coverage drops significantly**, revealing potential patient burden.

- 📆 **Timeline Visibility**:  
  - Clear mapping of **Admit → Discharge → Follow-up dates** supports monitoring patient lifecycle for operational efficiency.

---

## ✅ Recommendations

- 💳 **Policy Alignment**: Increase insurance support for low-volume treatments like fractures to reduce out-of-pocket expenses.  
- 🛌 **Bed Allocation Strategy**: Consider expanding **Private bed capacity** or redistributing based on real-time usage demand.  
- 🧑‍⚕️ **Doctor Engagement**: Dive deeper into feedback content to assess quality, not just quantity, of patient-doctor interaction.  
- 📅 **Proactive Scheduling**: Use admit-to-follow-up trends to predict future demand surges and improve hospital readiness.

---

## 🛠️ Tools & Technologies Used

| Tool        | Purpose                           |
|-------------|-----------------------------------|
| **Power BI**| Dashboard creation, visual analytics |
| **Excel**   | Data cleaning & preprocessing     |

---



## 🧾 Conclusion

This project delivers end-to-end visibility into hospital workflow, from diagnosis to billing and follow-up. It highlights opportunities in insurance alignment, capacity planning, and feedback analysis. By leveraging interactive dashboards, Apollo Hospitals can drive better patient experience, financial efficiency, and operational foresight.

---

## 👤 Author

**Vansh Chugh**  
[GitHub](https://github.com/VANSH-Chugh) | [LinkedIn](https://www.linkedin.com/in/vansh-chugh-64111a1ab)



