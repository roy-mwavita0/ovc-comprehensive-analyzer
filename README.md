# 📊 OVC Data Quality Analyzer

**OVC Data Quality Analyzer** is a digital dashboard built in **R Shiny** for assessing, visualizing, and improving the data quality of **Orphans and Vulnerable Children (OVC)** program records. It enables real-time detection of data anomalies and supports evidence-based service delivery through intuitive visualizations and automated validation checks.

## 🔗 Live Dashboard

👉 [Access the live tool on R Shiny](https://roymwavita.shinyapps.io/ovc_analyzer/)

---

## 🌟 Key Features

- 📥 **Data Upload Interface**: Accepts OVC registration data in `.csv` format

  ![Screenshot 2025-07-08 095124](https://github.com/user-attachments/assets/d005ab98-b781-4f95-af08-0ce0a4228efc)
  
- 🧹 **Built-in Data Validation**:
  
  ![Screenshot 2025-07-08 095218](https://github.com/user-attachments/assets/6fba1533-8f9e-4975-bd81-386d097a355e)

  - Detects duplicate Birth Certificate and CCC numbers
  - Flags records with enrollment before birth or linkage to care before birth
  - Identifies blank or inconsistent exit reasons
  - Highlights incorrect OVC and caregiver status combinations
    
  ![Screenshot 2025-07-08 095200](https://github.com/user-attachments/assets/81050e5b-4580-4c16-9961-bd4dfc4f71b1)

- 📊 **Dashboards for Monitoring**:
  
![Screenshot 2025-07-08 095246](https://github.com/user-attachments/assets/0db304dc-18a2-435f-8091-cc695a4665e2)
  - Caseloads by sex, HIV status, birth certificate ownership, schooling, and disability
  - OVC summary breakdown by CBO, constituency, and ward
- 🔍 **Dynamic Filtering**:
  - Filter dashboards by CBO, Constituency, and Ward
- 📁 **Export Options**:
  - Downloadable lists of all flagged anomalies for data correction and follow-up

---

## 🧰 Technology Stack

- [R Shiny](https://shiny.rstudio.com/)
- [tidyverse](https://www.tidyverse.org/) (`dplyr`, `ggplot2`, `readxl`, etc.)
- `highcharter` for interactive plots
- Hosted on [shinyapps.io](https://www.shinyapps.io)

---

## 🚀 Getting Started

1. Go to the **Upload Registration List** tab.
2. Upload your `.csv` file (must include key columns like `cpims_ovc_id`, `exit_status`, etc.)
3. Click **Analyze Data** to generate insights.
4. Navigate to the **Overview** and **Data Gaps** sections:
   - **Overview**: Visual summaries of OVC case indicators
   - **Data Gaps**: Visualizations and downloadable tables for flagged data quality issues

---

## ✅ Sample Data Quality Checks

| Check                            | Description                                  |
|----------------------------------|----------------------------------------------|
| Duplicate Birth Certificates     | OVCs sharing the same birth certificate ID   |
| Duplicate CCC Numbers            | Same CCC number linked to multiple OVCs      |
| Enrolled Before Birth            | Logical inconsistency in enrollment date     |
| Linked to CCC Before Birth       | Invalid HIV linkage timeline                 |
| Blank or Missing Exit Reason     | Incomplete data for exited cases             |
| Inconsistent Exit Age            | Mismatched age at exit based on DOB          |
| OVC/Caregiver Status Errors      | Status doesn't align with case conditions    |

---
Created by **Roy Lennic Mwavita** – Monitoring & Evaluation professional, Kenya  
📧 lennicroy@gmail.com | 📞 +254 794 395 145
