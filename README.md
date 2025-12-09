# 📊 ScreenSense: Kids’ Screentime Visualization

ScreenSense is a data analysis and visualization project that studies screentime habits among Indian children. It reveals insights on device dependency, activity patterns, and health impacts based on demographics such as age, gender, and location.

---

## 📁 Dataset
- **Source:** Indian Kids Screentime 2025 (Kaggle)
- **Total Records:** 9,665+
- **Columns Include:**
  - Age, Gender
  - Avg_Daily_Screen_Time_hr
  - Primary_Device
  - Educational_to_Recreational_Ratio
  - Health_Impacts
  - Urban_or_Rural
  - Derived: Age_Band, ScreenTime_Level, Activity_Type

---

## 🛠️ Tech Stack
| Component | Tools |
|-----------|-------|
| Data Cleaning | Python (Pandas, NumPy) |
| Development | Jupyter Notebook |
| Visualization | Power BI |
| Modeling | DAX Calculated Columns & Measures |
| Database | CSV Local |
| Dashboard Features | KPIs, Slicers, Treemap, Bar, Donut, Pie Charts |

---

## ✨ Key Features
- Interactive, filter-based analytics dashboard
- Screentime segmentation by age, gender & location
- Device usage & content preference comparison
- DAX-driven screentime level slicers
- Health impact visualization (eye strain, poor sleep, anxiety)
- Activity dominance (Recreational vs Educational)

---

## 🧠 Screentime Level Categorization (DAX)
```DAX
ScreenTime_Level =
SWITCH(
    TRUE(),
    screensense[Avg_Daily_Screen_Time_hr] < 1, "Minimal (<1 hr)",
    screensense[Avg_Daily_Screen_Time_hr] >= 1 && screensense[Avg_Daily_Screen_Time_hr] <= 3, "Low (1–3 hrs)",
    screensense[Avg_Daily_Screen_Time_hr] > 3 && screensense[Avg_Daily_Screen_Time_hr] <= 5, "Moderate (3–5 hrs)",
    screensense[Avg_Daily_Screen_Time_hr] > 5, "High (>5 hrs)"
)
```

## 📊 Key Insights
- **Avg Daily Screentime:** 4.37 hours
- **Highest Screentime Group:** 13–17 years
- **Dominant Device:** Smartphone
- **Activity Preference:** Recreational > Educational
- **Location Impact:** Urban > Rural screentime
- **Common Health Effects:** Poor sleep, eye strain, anxiety

---
<img width="1331" height="738" alt="Screenshot 2025-12-04 122040" src="https://github.com/user-attachments/assets/ef073bdb-05e0-467b-9ef6-4b4361f19da8" />
