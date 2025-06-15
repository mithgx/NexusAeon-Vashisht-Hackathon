# 🚦 NexusAeon – Driving Safety Insights  
*🏆 1st Place Winner – Vashisht 2024 Data Analytics Hackathon*

---

## 📌 Overview

NexusAeon Data Analytics Hackathon is a data-driven road safety analysis hackathon that leverages over **1.8 million real-world driving events** from ADAS (Advanced Driver Assistance Systems) and DMS (Driver Monitoring Systems) sensors to identify **accident blackspots** and **risky driver behaviors**. Our solution combines **geospatial analytics, clustering, time-based visualizations**, and **domain-specific road safety references** to suggest actionable safety interventions.

Presented with an interactive **Power BI dashboard** and a concise data story, this project secured the **1st position** at the Vashisht 2024 Hackathon, hosted by IIITDM Kancheepuram.

---

## 👨‍💻 Team Sub-X

- **Mithilesh Gopalakrishnan S**
- **Shobhan Karthish M**

---

## 🎯 Problem Statement

Given telemetry and alert data from 130 vehicles collected over 30 days (spanning multiple Indian states), identify:

- High-frequency accident zones
- Risky timeframes for alerts
- Driving behavior patterns (e.g., drowsiness, unsafe distances, mobile usage)
- Actionable interventions for improving road safety

---

## 📊 Dataset Details

- **Vehicles**: 130 fleet vehicles
- **Duration**: 30 days
- **Events**: 1.8+ million alerts and sensor readings
- **Regions**: Karnataka, Telangana, Andhra Pradesh, Maharashtra, Odisha, Tamil Nadu, Kerala
- **Alert Types**:
  - FCW: Forward Collision Warning
  - PCW: Pedestrian Collision Warning
  - LDW: Lane Departure Warning
  - HMW: Headway Monitoring Warning
  - DMS Alerts: Drowsiness, Seatbelt, Mobile Usage, Yawning

---

## 🧠 Methodology

### 🔍 1. Data Cleaning & Filtering
- Removed noisy/missing points
- Focused on events with high confidence values

### 🌍 2. Geospatial Clustering
- Used heatmaps and DBSCAN to identify **blackspot clusters**
- Mapped alerts over road networks and accident-prone areas

### ⏰ 3. Temporal Pattern Analysis
- Created hourly and daily time-series graphs
- Donut charts and line plots to visualize alert spikes

### ⚠️ 4. Alert Categorization
- Grouped alerts by type: CAS (collision) vs. DMS (driver behavior)
- Separated analytics for each group

---

## 🗺️ Key Findings

| 📍 Location                        | 🚨 Incidents | 🔎 Observation |
|----------------------------------|--------------|----------------|
| **Wardha Road, Nagpur**          | 30,000+      | Poor visibility, high-speed segment |
| **HYD–VIZAG Highway (NH-65)**    | 12,000+      | Multiple DMS alerts – fatigue & mobile use |
| **Airport Rd, Karnataka (NH-43)**| 10,000+      | Unsafe lane changes, low signage |

> Additional DMS alert hotspots were seen along urban congested regions like **Dilsukhnagar** and **Mahatma Gandhi Bus Station Area** **(HYD)**.

---

## 📈 Visualizations

The project included a complete **Power BI dashboard** with:

- Dynamic filters (alert type, time range, location)
- Alert frequency graphs
- Geospatial heatmaps
- Blackspot ranking dashboard
- Alert trend by hour/day/week

📂 See `visualizations/` for exported views or the `.pbix` file.

---

## ✅ Recommendations

| Problem                        | Recommendation |
|-------------------------------|----------------|
| Frequent CAS alerts at highways | Speed calming zones, better signboards |
| High DMS alerts (drowsiness, mobile) | Awareness campaigns, stricter traffic enforcement |
| Poor lane management           | Road marking improvement and lane sensors |
| Bad road surfaces              | Infrastructure maintenance and pothole patching |

---

## 🧾 References

1. *Road Safety Audit: Wardha Road – Nagpur City*  
2. *Road Accidents in Maharashtra 2020 – NH65 Case Study*  
3. [Times of India: NH-65 – Bloodiest Stretch in Telangana](https://timesofindia.indiatimes.com/city/hyderabad/nh-65-bloodiest-stretch-in-telangana-clocks-4200-accidents-in-9-years/articleshow/99073858.cms)

---

## 🗂️ Repo Structure
```
NexusAeon-Vashisht-Hackathon/
├── report/
│ └── Vashisht_2024_NexusAeon.pdf
├── visualizations/
│ └── dashboard_screenshots.png
│ └── powerbi_dashboard.pbix
├── README.md
```

