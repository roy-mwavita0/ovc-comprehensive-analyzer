# OVC Comprehensive Data Quality Dashboard

**Live App:** [https://sufuri.shinyapps.io/ovc_gaps/](https://sufuri.shinyapps.io/ovc_gaps/)

## Overview

The **OVC Gaps Dashboard** is an interactive R Shiny application designed to support monitoring and evaluation efforts in Orphans and Vulnerable Children (OVC) programs. The dashboard provides real-time insights into regsitry gaps, reporting eligibility, HIV status monitoring, data quality, and prevention program performance.

Built with R Shiny, the application enables stakeholders—such as implementing partners, M&E officers, program managers, and case managers interactively explore data, assess program performance, and identify areas for action or improvement.

---

## ✨ Key Features

### 1. **Eligible for Reporting**
This section summarizes the population that is eligible for reporting, providing a clear snapshot of:

- **Enrolled OVCs**
- **Birth Certificate Ownership**
- **OVCs with Disabilities**
- **Exited Beneficiaries**
- **Transferred Beneficiaries**

These metrics help validate the reporting base and provide insight into the dynamics of the OVC program beneficiaries.
<img width="1920" height="883" alt="Screenshot (2)" src="https://github.com/user-attachments/assets/4571c65b-40e5-49a7-8729-ba5c44047f46" />

<img width="1920" height="856" alt="Screenshot (3)" src="https://github.com/user-attachments/assets/0b9beb53-427c-4492-becc-d6e7fa2e48d2" />


---

### 2. **HIV Information**
Focused on HIV-positive OVCs, this section tracks and analyzes clinical outcomes and care cascade, including:

- **Viral Load Cascade**
- **Contribution to the Triple 95 Targets**
- **HIV-Positive OVC Enrollment Trends**
- **Unsuppressed Viral Load Trends**

This supports targeted interventions and helps programs meet PEPFAR clinical targets.

<img width="1920" height="889" alt="Screenshot (4)" src="https://github.com/user-attachments/assets/d3790019-981a-4b82-9099-bfac358360aa" />

<img width="1920" height="900" alt="Screenshot (5)" src="https://github.com/user-attachments/assets/ffd3acb3-f5ba-4a23-bc8e-7346ef275ed2" />


---

### 3. **Comprehensive Gaps**
This section highlights **data quality issues** within the OVC registry and reporting systems. It helps identify and address:

- **Missing or incomplete records**
- **Inconsistencies in registration data**
- **Coverage gaps by service area or demographics**

This ensures that decisions are made on the basis of complete and reliable data.

<img width="1920" height="889" alt="Screenshot (6)" src="https://github.com/user-attachments/assets/9d0d1638-5085-4615-92de-01c58043c913" />


---

### 4. **OVC Preventive (Sinovuyo EBI)**
Tracks the implementation and performance of the **Sinovuyo Parenting Program** (an evidence-based intervention):

- **Enrollment Trends**
- **Session Completion Rates**
- **Session Gaps** (e.g. skipped sessions, duplicates, inconsistent sessions)

By analyzing these metrics, stakeholders can strengthen EBI delivery, improve retention, and reduce fidelity issues.

<img width="1920" height="892" alt="Screenshot (7)" src="https://github.com/user-attachments/assets/ef0fbd37-699a-42b0-be3c-36eb610dd5c2" />

---

## 📊 Technology Stack

- **Language:** R
- **Framework:** [Shiny](https://shiny.posit.co/)
- **Key Packages:**  
  `shiny`, `highcharter`, `tidyverse`, `DT`, `shinydashboard`, `tidyr`, `lubridate`, `bs4dash`, etc.


---

## 🧭 How to Use

1. Open the app: [https://sufuri.shinyapps.io/ovc_gaps/](https://sufuri.shinyapps.io/ovc_gaps/)
2. Navigate through the top-level tabs:
   - **Eligible for Reporting**
   - **HIV Information**
   - **Comprehensive Gaps**
   - **OVC Preventive**
3. Use filters (ward, constituency, group_name, facilitator) to refine the view.
4. Hover, zoom, and click through visualizations to explore trends.
---

## 🚀 Deployment

- Hosted on **ShinyApps.io**  
- Deployment includes cache management and reactive expressions for performance.
- Scalable for use across multiple counties or implementing partners.

---


- RStudio (recommended)

