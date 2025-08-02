# Hospital Room Emergency Dashboard

This repository showcases an end-to-end hospital emergency room analytics solution. It was developed using Power BI to monitor patient volume, wait times, satisfaction scores, referral trends, admission statuses, and key demographic patterns.

> **Author:** Oforah Ivan  
> **Tool Used:** Power BI Desktop  
> **Report Period:** Jan 2023 – Dec 2024  

---

## 🎯 Project Objective

The goal is to give healthcare administrators a clear, interactive view of emergency room performance. The dashboard enables quick evaluation of:

- Patient inflow patterns by time and demographics
- Wait time efficiency and performance against targets
- Department referrals and admission outcomes
- Patient satisfaction trends across months

---

## 🔧 Tools and Technologies

| Tool       | Purpose                                  |
|------------|-------------------------------------------|
| Power BI   | Report development and data visualization |
| Excel      | Initial data formatting         |
| Github     | Documentation   |
| LinkedIn   | Documenteation & Exhibition |

---

## 📊 Key Metrics Tracked

### ✅ **Performance Indicators**
- Average Wait Time (Monthly)
- % of Patients Seen Within 30 Minutes
- Patient Satisfaction Score

### 📈 **Patient Flow**
- Hourly and Daily Patient Volume
- Admission vs Non-Admission Rates
- Referrals by Department

### 👥 **Demographics**
- Age Group, Gender, and Race Distribution
- Weekly and Hourly Patient Volume Heatmap

---

## 📌 Insights & Highlights

- **Avg. Wait Time:** ~35 mins over the year; May 2023 saw a drop to 34.4 mins
- **Admission Rate:** 50.04% overall admitted, balanced with non-admitted
- **Departments with Most Referrals:** General Practice (1.8K), Orthopedics (1.0K)
- **Race Distribution:** Majority White (2.6K), followed by African American (2.0K)
- **Time Blocks of Peak Volume:** 07:00–10:00 and 13:00–16:00 on weekdays
- **Target Compliance:** Only 59.32% of patients were seen within the 30-minute standard

---








## 🧪 How to Use

1. **Download the PBIX file** from `/dashboards/Hospital_Emergency_Room_Report.pbix`
2. Open in Power BI Desktop
3. Use filters to explore:
    - Date range  
    - Department referral  
    - Gender or age group  
    - Admission status

---

## 📁 Repository Structure

```bash
├── dashboards/
│   └── Hospital_Emergency_Room_Report.pbix
├── data/
│   └── patient_records_sample.csv
├── insights/
│   └── insight_summary.md
├── scripts/
│   └── time_slot_analysis.py  # Optional, for preprocessing or simulation
├── README.md

