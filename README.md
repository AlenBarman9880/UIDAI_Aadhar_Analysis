# UIDAI Data Hackathon 2026 – Aadhaar Analytics

## 📌 Project Overview
This repository contains the work submitted by **Team Idea Assassins** for the **UIDAI Data Hackathon 2026**.  
Our project focuses on analysis of Aadhaar enrolment, demographic updates, and biometric activity to uncover regional trends, age-wise patterns, and actionable insights for policy and service optimization.

---

## 👥 Team Members
- Mrinal Shobhit  
- Alen Barman  
- Diya Sarkar  
- Amaldeep Patra  

Team ID: **UIDAI_4274**

---

## 🎯 Problem Statement
Aadhaar is India’s largest digital identity infrastructure, underpinning billions of transactions annually.  
Despite its scale, **operational usage patterns remain under-analysed**, leading to:
- Uneven adoption across states and districts  
- High biometric update load among children/adolescents  
- Frequent demographic updates due to migration  
- Limited analytical visibility for planning & policy  

Our goal: **Transform raw Aadhaar activity into actionable signals for policy, planning, and service optimization.**

---

## 📊 Datasets Used
- **Aadhaar Enrolment Dataset** – Age-wise enrolment records  
- **Aadhaar Biometric Update Dataset** – Biometric update activity  
- **Aadhaar Demographic Update Dataset** – Demographic correction updates  
- **Census 2011 District Boundary Data** – For spatial visualization  

---

## 🛠️ Methodology
1. **Data Cleaning & Standardization** – Normalize state, district, and pincode fields  
2. **Aggregation & Alignment** – Derive metrics and align datasets by geography/time  
3. **Interactive Mapping** – District-level biometric update maps using GeoPandas & Plotly  
4. **Visualization & Dashboards** – Power BI dashboards for exploration  
5. **Pattern Interpretation** – Identify gaps, disparities, and trends for decision intelligence  

---

## 📐 Metrics Defined
- **Biometric Update Count** – Total update transactions  
- **Eligible Enrolment Count** – Population base for fair comparison  
- **Biometric Update Activity Rate** – Updates relative to enrolments  
- **State-Relative Z-Score** – District deviation from state average  
- **Data Sufficiency & Reporting Flags** – Ensure reliability of insights  

---

## 🚩 Key Insights & Recommendations
### Under-Activity Districts
- **Cause:** Poor connectivity, few centres, low awareness  
- **Action:** Mobile Aadhaar camps, integrate child updates with school enrolment  

### Below State Average Districts
- **Cause:** Behavioural inertia, inconvenient timings  
- **Action:** SMS/IVR reminders, evening/weekend centre hours  

### High-Volume Districts
- **Cause:** Policy-triggered surges, insufficient counters  
- **Action:** Temporary counters, appointment/token systems, demand forecasting  

### No Reporting Districts
- **Cause:** Data gaps or extreme remoteness  
- **Action:** Verify with registrars, mobile camps aligned with ration/health days  

---

## 📈 Dashboard & Tools
- **Power BI Dashboards** – Interactive exploration of Aadhaar enrolment & update patterns  
- **GeoPandas + Plotly** – Geographic visualizations  
- **Analytical Code Notebooks** – Data cleaning, aggregation, and analysis workflows  

---

## 🏆 Impact
- Provides **region-specific, data-driven recommendations** for Aadhaar operations  
- Helps reduce **infrastructure stress** at enrolment/update centres  
- Enables **policy-ready insights** for targeted interventions  
- Supports **governance optimization** by improving citizen experience  

---

## 🔗 Resources
- [Interactive Power BI Dashboard](#)  
- [Analysis Code Notebooks](#)  

---

## 🙏 Acknowledgements
This project was developed as part of the **UIDAI Data Hackathon 2026**, leveraging datasets from the **Open Government Data (OGD) Platform India**.  
Special thanks to **UIDAI** and **NIC** for enabling open data-driven innovation.
