# axon-healthcare-analytics-excel-dashboard

# 🏥 Axon Healthcare Analytics Dashboard

> **An interactive Excel-based Healthcare Analytics Dashboard delivering deep insights into patient care, doctor performance, treatment outcomes, and diagnosis trends across multiple states and cities in the USA.**

---

## 📸 Dashboard Preview

[Axon Healthcare Analytics Dashboard] <img width="1757" height="777" alt="Screenshot 2026-06-17 110726" src="https://github.com/user-attachments/assets/f086c3ba-b2bc-4cf2-9033-acdf52f8bdb4" />


---

## 📌 Table of Contents

1. [Project Overview](#-project-overview)
2. [Objectives](#-objectives)
3. [Dataset Description](#-dataset-description)
4. [Key Metrics](#-key-metrics-at-a-glance)
5. [Visualizations](#-visualizations-included)
6. [Filters & Slicers](#-interactive-filters-slicers)
7. [Excel Features Used](#-excel-features-used)
8. [Project Structure](#-project-structure)
9. [Getting Started](#-getting-started)
10. [Key Insights & Findings](#-key-insights--findings)
11. [Business Impact](#-business-impact)
12. [Challenges & Solutions](#-challenges--solutions)
13. [Future Improvements](#-future-improvements)
14. [Conclusion](#-conclusion)
15. [Contributing](#-contributing)
16. [License](#-license)
17. [Author](#-author)

---

## 🔍 Project Overview

The **Axon Healthcare Analytics Dashboard** is a fully interactive business intelligence solution built entirely in **Microsoft Excel**. It consolidates data from 10,000 patients, 1,000 doctors, and 10,000 lab results into a single, easy-to-navigate dashboard.

This project was created to help healthcare administrators, analysts, and decision-makers quickly understand:
- How patients are distributed across blood types, age groups, and genders
- How doctors are allocated across medical specialties
- What treatment types are being used and how much they cost
- Which diagnoses are most common and who is most affected
- What percentage of operations succeed, fail, or are ongoing

The dashboard replaces the need for manual reporting by providing **real-time, slicer-driven visual analytics** that update instantly with every filter selection.

---

## 🎯 Objectives

- ✅ Consolidate large-scale healthcare data into a single interactive dashboard
- ✅ Track and monitor key healthcare KPIs in real time
- ✅ Identify patterns in patient demographics, diagnoses, and treatments
- ✅ Enable filtering by State, City, Gender, and Treatment Type
- ✅ Help hospital management make faster, data-driven decisions
- ✅ Provide a clean, professional visual layout for presentations and reporting

---

## 🗃️ Dataset Description

The dashboard is powered by a healthcare dataset containing the following key fields:

| Category | Fields |
|---|---|
| 👥 Patient Info | Patient ID, Age, Gender, Blood Type, City, State |
| 🩺 Doctor Info | Doctor ID, Specialty, Patients Per Doctor |
| 🏥 Visit Info | Visit ID, Follow-Up Status, Treatment Type |
| 💊 Treatment Info | Treatment Cost, Treatment Type |
| 🔬 Lab Results | Lab Result ID, Result Status (Normal / Abnormal) |
| 🩻 Operations | Operation Status (Successful / Ongoing / Failed) |
| 📋 Diagnosis | Diagnosis Type (Asthma, Diabetes, Healthy, Hypertension, Migraine) |

- **Total Records:** 10,000 patients
- **Doctors:** 1,000
- **Lab Results:** 10,000
- **States Covered:** California, Florida, Illinois, New York, Texas
- **Cities Covered:** Chicago, Houston, Los Angeles, Miami, New York City

---

## 📊 Key Metrics at a Glance

| # | Metric | Value |
|---|---|---|
| 1 | 👥 Total Patients | 10,000 |
| 2 | 🩺 Total Doctors | 1,000 |
| 3 | 🗓️ Total Visits | 10,000 |
| 4 | 📅 Average Patient Age | 48.93 years |
| 5 | 🔁 Follow-Up Rate | 49.84% |
| 6 | 💊 Average Treatment Cost | $524.75 |
| 7 | 👨‍⚕️ Avg. Patients Per Doctor | 10 |
| 8 | 🔬 Abnormal Lab Results | 33.54% |
| 9 | 🧪 Total Lab Result IDs | 10,000 |

---

## 📈 Visualizations Included

### 1. 🔵 Operation Count By Status — *Pie Chart*
Tracks the outcome of all medical operations performed.

| Status | Percentage |
|---|---|
| ✅ Successful | 34% |
| 🔄 Ongoing | 33% |
| ❌ Failed | 33% |

> Nearly one-third of operations are still ongoing or have failed — signaling a need for operational review.

---

### 2. 🩸 Patient Count By Blood Type — *Bar Chart*
Displays patient distribution across all 8 blood types.

| Blood Type | Count |
|---|---|
| A− | 1,257 |
| A+ | 1,225 |
| AB− | 1,199 |
| AB+ | 1,304 |
| B− | 1,266 |
| B+ | 1,202 |
| O− | 1,236 |
| O+ | 1,311 *(Highest)* |

> **O+** is the most common blood type, important for blood bank planning.

---

### 3. 🚻 Gender Distribution of Patients — *Donut Chart*
Shows how patients are distributed by gender.

| Gender | Percentage |
|---|---|
| Female | 34.03% |
| Male | 33.14% |
| Other | 32.83% |

> Gender distribution is nearly equal — indicating a well-balanced patient population.

---

### 4. 📋 Diagnosis Count By Age Group — *Stacked Bar Chart*
Breaks down diagnosis frequency across age groups.

- Age Groups: **Middle-aged, Adult, Senior, Teenager, Young Adult, Elderly**
- Helps identify which age segments are most affected by healthcare issues

---

### 5. 👨‍⚕️ Doctor Count By Specialty — *Bar Chart*
Shows how doctors are distributed across medical specialties.

| Specialty | Doctor Count |
|---|---|
| Cardiology | 207 |
| General Medicine | 212 *(Highest)* |
| Neurology | 185 *(Lowest)* |
| Orthopedics | 190 |
| Pediatrics | 204 |

> General Medicine has the most doctors; Neurology may need more staffing.

---

### 6. 🏥 Percentage of People By Diagnosis — *Donut Chart*
Shows the proportion of patients by their diagnosis.

| Diagnosis | Percentage |
|---|---|
| Asthma | 20.09% |
| Diabetes | 19.81% |
| Healthy | 20.11% |
| Hypertension | 19.60% |
| Migraine | 20.39% *(Highest)* |

> Diagnoses are evenly distributed — chronic conditions like Migraine and Asthma lead slightly.

---

## 🔍 Interactive Filters (Slicers)

All charts and KPIs update dynamically when filters are applied.

| 🔘 Filter | Options Available |
|---|---|
| 🗺️ **State** | California, Florida, Illinois, New York, Texas |
| 💉 **Treatment Type** | Medication, Physical Therapy, Surgery, Vaccination |
| 🏙️ **City** | Chicago, Houston, Los Angeles, Miami, New York City |
| 🚻 **Gender** | Female, Male, Other |

---

## 💡 Excel Features Used

| Feature | Purpose |
|---|---|
| 📊 Pivot Tables | Data summarization and aggregation |
| 📉 Pivot Charts | Bar, Pie, Donut, and Stacked Bar visualizations |
| 🎛️ Slicers | Interactive filtering across all visuals |
| 🔢 Excel Formulas | KPI calculations (AVERAGE, COUNT, COUNTIF, AVERAGEIF) |
| 🎨 Conditional Formatting | Highlight key values and trends |
| 📦 Linked Text Boxes | KPI card display tied to formula results |
| 🖼️ Icons & Shapes | Professional dashboard design elements |
| 🎨 Custom Color Theme | Dark teal and green healthcare branding |

---

## 📁 Project Structure

```
axon-healthcare-analytics/
│
├── 📄 README.md                          # Project documentation (this file)
├── 🖼️ Screenshot_2026-06-17_110726.png   # Dashboard preview image
├── 📊 Axon_Healthcare_Dashboard.xlsx     # Main Excel dashboard file
└── 📁 data/
    └── healthcare_data.csv               # Raw source dataset
```

---

## 🚀 Getting Started

### ✅ Prerequisites

- **Microsoft Excel 2016 or later**
- OR **Microsoft 365** *(recommended for full slicer & chart compatibility)*

### 📥 Installation & Setup

**Step 1 — Clone or Download the Repository**
```bash
git clone https://github.com/your-username/axon-healthcare-analytics.git
cd axon-healthcare-analytics
```
Or click **Code → Download ZIP** on GitHub and extract the folder.

**Step 2 — Open the Excel File**
```
Double-click: Axon_Healthcare_Dashboard.xlsx
```

**Step 3 — Enable Editing**
- Click **"Enable Editing"** in the yellow bar at the top (if prompted)
- Click **"Enable Content"** if macros are present

**Step 4 — Explore the Dashboard**
- Navigate to the **Dashboard** sheet/tab
- Use the **Slicers** (right panel) to filter by State, City, Gender, or Treatment Type
- All charts and KPIs will update **automatically**

**Step 5 — Refresh Data** *(if using external or updated data)*
- Go to **Data tab → Refresh All**
- Or right-click any Pivot Table → **Refresh**

---

## 🔑 Key Insights & Findings

After analyzing the dashboard, the following insights were discovered:

1. **🔴 High Operation Failure Rate**
   - 33% of operations failed and 33% are still ongoing — only 34% were successful. This indicates potential issues with operation planning or patient preparation.

2. **🟡 Nearly Half of Patients Don't Follow Up**
   - With a follow-up rate of only **49.84%**, half the patients are not returning for post-treatment checkups, which may lead to undetected complications.

3. **🟠 High Abnormal Lab Results**
   - **33.54%** of lab results are abnormal — one in three patients has an irregular lab finding that may require attention.

4. **🟢 Blood Type O+ is Most Common**
   - O+ patients (**1,311**) are the largest group — hospitals should maintain higher O+ blood bank reserves.

5. **🔵 Neurology is the Most Understaffed Specialty**
   - With only **185 doctors**, Neurology has the fewest specialists relative to other departments like General Medicine (212).

6. **🟣 Migraine is the Most Common Diagnosis**
   - At **20.39%**, Migraine leads all diagnoses — suggesting a potential focus area for preventive care campaigns.

7. **⚖️ Balanced Gender & Age Distribution**
   - Patient gender is nearly equal (34% / 33% / 33%), and diagnosis spread is even across age groups — showing diverse patient representation.

8. **💰 Average Treatment Cost is $524.75**
   - This can vary significantly by treatment type (Surgery vs. Medication) — filtering by Treatment Type reveals cost distribution patterns.

---

## 💼 Business Impact

This dashboard delivers measurable value to healthcare organizations:

| Stakeholder | Benefit |
|---|---|
| 🏥 Hospital Administrators | Monitor operation outcomes and reduce failure rates |
| 📊 Healthcare Analysts | Quickly identify abnormal trends in lab results and diagnoses |
| 👨‍⚕️ Department Heads | Evaluate doctor-to-patient ratios and staffing needs |
| 💰 Finance Teams | Track and control average treatment costs by type and region |
| 🏙️ City/State Health Departments | Compare healthcare performance across locations |
| 🧑‍⚕️ Patient Care Teams | Improve follow-up rates by identifying low-engagement regions |

**Estimated Time Saved:** Manual reporting that previously took hours can now be reviewed in minutes using dashboard filters.

---

## 🧩 Challenges & Solutions

| Challenge | Solution |
|---|---|
| Large dataset with 10,000+ rows | Used Pivot Tables for fast aggregation |
| Making charts update with filters | Connected all charts to shared Slicers |
| Designing a clean layout | Used custom shapes, colors, and icon sets |
| Calculating KPIs dynamically | Linked KPI cards to Pivot Table formula outputs |
| Maintaining consistent color theme | Applied a custom teal/green Excel theme throughout |

---

## 🔮 Future Improvements

- [ ] 📅 Add a **Date/Time filter** to track trends over months and years
- [ ] 🌍 Add a **Map visual** to show patient distribution by state geographically
- [ ] 📤 Export dashboard to **Power BI** for web-based sharing
- [ ] 📧 Add **automated email reports** using Excel + Outlook macros (VBA)
- [ ] 🤖 Integrate **predictive analytics** to forecast patient admission rates
- [ ] 📱 Build a **mobile-friendly version** using Power BI Mobile
- [ ] 🔗 Connect to a **live database** (SQL Server / Google Sheets) for real-time data

---

## ✅ Conclusion

The **Axon Healthcare Analytics Dashboard** successfully transforms raw healthcare data into clear, actionable visual insights using Microsoft Excel. By combining Pivot Tables, Pivot Charts, Slicers, and dynamic KPI cards, this dashboard empowers healthcare professionals to:

- Monitor **10,000 patients** and **1,000 doctors** at a glance
- Track **treatment costs**, **lab results**, and **operation outcomes**
- Filter data instantly by **State, City, Gender, and Treatment Type**
- Identify **critical issues** like high operation failure rates and low follow-up rates

This project demonstrates the power of **Excel as a Business Intelligence tool** — no specialized software required. It serves as a strong foundation for future upgrades to Power BI or cloud-based analytics platforms.

> 💡 *"Data is the heartbeat of healthcare — this dashboard makes it visible."*



---

*Made with ❤️ and Microsoft Excel*
