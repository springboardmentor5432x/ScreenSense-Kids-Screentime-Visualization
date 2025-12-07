# ScreenSense: Kids' Screentime Visualization Project 📊

> **Data-Driven Insights for Public Health Intervention**  
> Analyzing screentime patterns of 9,712 Indian children to identify intervention opportunities

![Status](https://img.shields.io/badge/Status-Complete-brightgreen)
![Batch](https://img.shields.io/badge/Batch-Infosys%20Springboard%206.0-blue)
![Duration](https://img.shields.io/badge/Duration-8%20Weeks-orange)
![Dataset](https://img.shields.io/badge/Dataset-9712%20Records-yellowgreen)

---

## 📋 Project Overview

**ScreenSense** is a comprehensive data analytics project analyzing screentime patterns among Indian children (ages 8-18) to understand health impacts and develop evidence-based intervention strategies. The project combines advanced data engineering, exploratory analysis, and interactive visualization design to enable data-driven decision-making for public health stakeholders.

### Key Findings at a Glance

| Metric | Finding |
|--------|---------|
| **Population Affected** | 66.9% (6,490 children) showing health impacts |
| **At-Risk Screen Time** | 61.3% in excessive/high categories |
| **Average Daily Usage** | Young Adults: 4.54 hrs/day (2.3x recommended) |
| **Activity Impact** | 50-point difference: Entertainment (68% unhealthy) vs Learning (18% unhealthy) |
| **Device Impact** | 64-point difference: Smartphone (68% unhealthy) vs Laptop (4% unhealthy) |
| **Risk Concentration** | 54% of population in just 5 demographic cohorts |
| **Intervention ROI** | At 52% effectiveness: 5,601 children move to healthy status (33% → 91%) |

---

## 🎯 Project Objectives

✅ **Analyze** screentime patterns across multiple dimensions (age, gender, location, device, activity)  
✅ **Identify** highest-risk demographic segments and cohorts  
✅ **Develop** evidence-based intervention strategies with quantified ROI  
✅ **Create** interactive decision-support dashboards for stakeholders  
✅ **Demonstrate** advanced Power BI and data analytics capabilities  

---

## 📂 Repository Structure

```
ScreenSense/
│
├── README.md (this file)
├── PRESENTATION.md
│
├── 📊 Dashboard/
│   ├── ScreenSense_Dashboard.pbix (Power BI file - 7 pages)
│   └── Dashboard_Guide.md
│
├── 📑 Documentation/
│   ├── Week3_Analysis.docx (Univariate & Bivariate)
│   ├── Week4_Analysis.docx (Device & Activity Mix)
│   ├── Week5_Analysis.docx (Segment & Cohort Analysis)
│   ├── Week6_Analysis.docx (Decision Support)
│   └── Comprehensive_Final_Report.docx (50+ pages)
│
├── 📈 Data/
│   ├── Indian_Kids_Screentime_2025.csv (Source data - 9,712 records)
│   ├── Data_Dictionary.md (Column definitions)
│   └── Data_Quality_Report.md
│
├── 📓 Notebooks/
│   ├── Week1_Data_Preparation.ipynb
│   ├── Week2_Feature_Engineering.ipynb
│   ├── Week3_Descriptive_Analysis.ipynb
│   ├── Week4_Dimensional_Analysis.ipynb
│   ├── Week5_Cohort_Analysis.ipynb
│   └── Week6_What_If_Modeling.ipynb
│
└── 🎤 Presentation/
    ├── ScreenSense_Concise_PPT.pptx (8-slide presentation)
    └── Presentation_Guide.docx (Speaker notes)
```

---

## 🔍 What's Inside

### Dashboard (7 Pages, 27+ Visualizations)

**Page 1: Home**
- Executive overview with 5 KPI cards
- Key findings summary
- Navigation to all analysis sections

**Page 2-3: Week 3 Analysis**
- **Univariate:** Individual variable distributions
- **Bivariate:** Relationships between variables
- Slicers: Gender, Age Group, Urban/Rural

**Page 4-5: Week 4 Analysis**
- **Device & Activity Mix:** Combinations and their health impact
- **Urban vs Rural:** Location-based patterns
- Device health risk percentages
- Location-specific interventions

**Page 6: Week 5 Analysis**
- **Top 5 Risk Cohorts:** Ranked by health impact
- **Health Impact Breakdown:** Sleep, eye strain, anxiety, obesity
- **Device × Activity Heatmap:** Risk levels
- Best and worst-case scenarios

**Page 7: Week 6 Analysis**
- **Intervention Simulator:** What-if parameter (0-100% effectiveness)
- **Impact Projections:** Current → Projected health outcomes
- **Prescriptive Action Plan:** By cohort and intervention type
- **ROI Calculator:** Expected outcomes by intervention

### Data (9,712 Records, 23 Columns)

**Original 8 Columns:**
- Age, Gender, Urban_or_Rural, Primary_Device
- Avg_Daily_Screen_Time_hr, Activity_Category
- Health_Status, Health_Issues

**15 Engineered Features:**
- Age_Group (Child, Teenager, Young Adult)
- Screen_Time_Category (Low, Moderate, High, Excessive)
- Screen_Comparison (Small vs Large screens)
- Cohort_Label (Multi-dimensional segments)
- Health_Impact_Columns (Poor_Sleep, Eye_Strain, Anxiety, Obesity_Risk)
- Risk_Score, Intervention_Priority, and more

**Data Quality:**
- ✅ 0% null values
- ✅ 0% duplicate records
- ✅ Validated ranges and distributions
- ✅ Complete population (no sampling)

### Key Insights by Week

**Week 3: The Baseline**
- 61.8% of children in concerning/excessive screen time
- Smartphone dominates (47% of usage)
- Age progression: 4.16 hrs → 4.54 hrs (Child to Young Adult)
- 66.9% showing health impacts (sleep, eye, anxiety, obesity)

**Week 4: What Combinations Matter**
- Activity Type: 50-point difference (Entertainment 68% unhealthy vs Learning 18%)
- Device Type: 64-point difference (Smartphone 68% unhealthy vs Laptop 4%)
- Device Ergonomics: 23-point difference (Small screens 72% vs Large screens 49%)
- Urban dominates smartphone usage (56% vs 46% rural)

**Week 5: Risk Concentration**
- Top 5 cohorts: 5,269 children (54.3% of population)
- All top 5 are entertainment-focused
- 4 out of 5 are urban locations
- Young Adults: 90%+ unhealthy rate
- Teenagers: 84-87% unhealthy rate
- Best-case scenario: 82% healthy (learning + laptop + urban + child)

**Week 6: Intervention Strategy**
- Current: 33.1% healthy (3,222 children)
- At 60% intervention effectiveness: 70.3% healthy (+37.2 points)
- At 52% blended effectiveness: 90.9% healthy (+57.8 points)
- 3,601 to 5,601 children move from unhealthy to healthy status

---

## 💡 Strategic Recommendations

### Immediate Priority (Months 1-3)

**1. Parental Control App Deployment** (Urban Young Adults)
- Target: 2,890 children (highest-risk cohort)
- Expected effectiveness: 65%
- Expected outcome: 1,879 children to healthy
- Budget: High | ROI: Highest
- Timeline: 3 months

**2. Device Recommendation Campaign** (All Population)
- Target: 9,712 children
- Expected effectiveness: 35%
- Expected outcome: 3,399 children improved
- Budget: Low (policy-level)
- ROI: Highest per dollar
- Timeline: Immediate

**3. School-Based Digital Wellness** (Teenagers)
- Target: 3,135 children
- Expected effectiveness: 58%
- Expected outcome: 1,818 children to healthy
- Budget: Medium | ROI: Medium-High
- Timeline: 6 months

### Secondary Priority (Months 4-6)

- Rural SMS awareness campaigns (48% effectiveness)
- Quarterly health screening programs
- Media literacy curriculum integration

### Population-Level Impact

**Blended Approach at 52% Effectiveness:**
- Expected children improved: 5,601
- Projected healthy rate: 90.9% (from 33.1%)
- Annual health improvement: +57.8 percentage points
- Cost-effectiveness: High across all intervention types

---

## 🛠️ Technical Stack

**Data Preparation & Engineering:**
- Python 3.x
- Pandas, NumPy
- Jupyter Notebook
- ETL: 8 → 23 columns (15 engineered features)

**Visualization & Dashboarding:**
- Microsoft Power BI Desktop
- 27+ advanced visualizations
- 15+ DAX measures (custom calculations)
- Interactive parameters and slicers
- What-If parameter implementation

**Data Analysis:**
- Univariate analysis (single variables)
- Bivariate analysis (relationships)
- Cohort analysis (multi-dimensional segments)
- What-If modeling (scenario projection)
- ROI calculation

**Analytical Progression:**
- Week 3: Descriptive ("What is happening?")
- Week 4: Dimensional ("What combinations matter?")
- Week 5: Prescriptive ("What should we do?")
- Week 6: Strategic ("What will happen if...?")

---

## 📊 Dashboard Features

### Interactive Elements
- **10+ Slicers:** Gender, Age_Group, Urban_or_Rural, Primary_Device, Activity_Category, Screen_Comparison, and more
- **What-If Parameter:** Intervention Effectiveness Slider (0-100%)
- **Cross-Filtering:** All pages interconnected
- **Navigation Buttons:** Seamless page traversal
- **Drill-Down Capability:** Explore specific cohorts and segments

### Visualization Types
- Donut charts (health status distribution)
- Stacked bar charts (screen time categories)
- Ribbon charts (device preferences)
- Waterfall charts (intervention impact)
- Matrix/Heatmaps (risk levels)
- Small multiples (comparative analysis)
- KPI cards with dynamic measures
- Line charts (trends)
- Combo charts (dual-axis analysis)

### Design Features
- Professional color scheme (blue/purple gradient)
- Color-coded risk indicators (Green → Yellow → Orange → Red)
- Mobile-friendly layout
- Consistent formatting across pages
- Clear labeling and legends
- Accessibility considerations

---

## 🎓 Learning Outcomes

### Skills Demonstrated

**Data Analytics:**
- ETL and data engineering (8 → 23 columns)
- Univariate, bivariate, and multivariate analysis
- Cohort analysis and segmentation
- Prescriptive and what-if modeling
- ROI calculation and financial analysis

**Power BI Proficiency:**
- Advanced visualization design
- DAX formula creation (15+ measures)
- Interactive parameter implementation
- Custom theme and color psychology
- Cross-filtering and drill-through
- Report optimization and performance

**Strategic Thinking:**
- Problem identification and scoping
- Evidence-based recommendation development
- Stakeholder-focused insight generation
- Business case development
- Resource allocation optimization

**Communication:**
- Data visualization for business intelligence
- Executive summary development
- Presentation skills (5-10 minute pitch)
- Technical documentation
- Insight articulation

---

## 📈 How to Use This Project

### For Stakeholders/Decision-Makers

1. **Review Dashboard:** Start with Home page for executive overview
2. **Explore Key Findings:** Slides 3-6 show top 5 cohorts and intervention potential
3. **Model Scenarios:** Use What-If slider on Week 6 page to test effectiveness levels
4. **Access Recommendations:** See prescriptive action plan with timelines and budgets
5. **Track Progress:** Dashboard auto-updates when new data is added

### For Data Analysts/Developers

1. **Review Methodology:** See Week 1-6 Jupyter notebooks for analysis progression
2. **Understand Features:** Consult Data_Dictionary.md for all 23 columns
3. **Replicate Analysis:** Notebooks are fully commented for reproducibility
4. **Extend Analysis:** Add new cohorts, interventions, or outcome measures
5. **Customize Dashboard:** PBIX file is fully editable in Power BI Desktop

### For Educators/Students

1. **Study the Progression:** Week-by-week demonstrates analytical thinking
2. **Learn Techniques:** Each week introduces new analysis types
3. **Understand Power BI:** Dashboard shows professional design practices
4. **Practice Documentation:** See how findings are communicated clearly
5. **Apply Framework:** Use this structure for your own projects

---

## 🚀 Getting Started

### Prerequisites
- Microsoft Power BI Desktop (for viewing/editing dashboard)
- Python 3.x (for data preparation notebooks)
- Jupyter Notebook
- Libraries: pandas, numpy, matplotlib, seaborn

### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/ScreenSense.git
cd ScreenSense

# Install dependencies
pip install -r requirements.txt

# Open dashboard
# Download ScreenSense_Dashboard.pbix and open in Power BI Desktop

# View notebooks
jupyter notebook
```

### File Sizes
- Dashboard (PBIX): ~50MB
- Data CSV: ~2MB
- Documentation: ~5MB
- Total: ~60MB

---

## 📊 Key Metrics at a Glance

### Population Metrics
- Total Children: **9,712**
- Age Range: **8-18 years**
- Urban Distribution: **71%**
- Rural Distribution: **29%**

### Health Status
- Healthy: 3,222 (33.1%)
- Unhealthy: 6,490 (66.9%)
- Average Health Issues per Child: 2.4

### Screen Time
- Average Daily Usage: 4.35 hours
- Recommended: <2 hours/day
- Exceeding Recommendation: 92.4%
- Young Adults: 4.54 hours/day
- Children: 4.16 hours/day

### Risk Distribution
- Low (Healthy): 8.2%
- Moderate: 29.8%
- High: 47.4%
- Excessive: 14.6%

### Device Usage
- Smartphone: 47%
- TV: 25.6%
- Laptop: 14.8%
- Tablet: 12.6%

### Activity Distribution
- Entertainment-focused: 81.7%
- Balanced: 16.4%
- Learning-focused: 1.9%

---

## 🎯 Expected Outcomes

### Short-term (3 months)
- ✅ Parental control apps deployed for Urban Young Adults
- ✅ Device recommendation campaign launched nationally
- ✅ 1,879+ children move to healthy status
- ✅ Early ROI metrics visible

### Medium-term (6 months)
- ✅ School-based programs implemented in 50+ schools
- ✅ 1,818+ teenagers in digital wellness curriculum
- ✅ 3,399+ children benefit from device recommendations
- ✅ Total: 3,600-4,000 children improved

### Long-term (12 months)
- ✅ 5,601 children moved from unhealthy to healthy status
- ✅ Population health rate: 33% → 91%
- ✅ Annual health improvement: +57.8 percentage points
- ✅ Sustainable intervention framework established
- ✅ Model ready for national rollout

---

## 📞 Contact & Support

**Project Lead:** Afzal Hussain S  
**Email:** afzalmysss321@gmail.com 
**LinkedIn:** https://www.linkedin.com/in/afzalhussains


**Mentor:** Sirisha  
**Organization:** Infosys Springboard 6.0 - Batch 4  
**Project Period:** Oct-Nov 2025  
**Completion Date:** 06-12-2025

---

## 📄 License

This project is created for educational purposes as part of Infosys Springboard 6.0 program.

---

## 🙏 Acknowledgments

- **Dataset Source:** Kaggle - Indian Kids Screentime 2025
- **Mentor Guidance:** Sirisha, Infosys Springboard
- **Infosys Springboard 6.0** for project structure and support
- **Community:** Data analysts and visualization practitioners who inspired this work

---

## 📚 Additional Resources

### Documentation Files
- `Comprehensive_Final_Report.docx` - Complete 50+ page analysis report
- `Data_Dictionary.md` - All 23 columns defined
- `Data_Quality_Report.md` - Data validation and quality metrics
- `Dashboard_Guide.md` - How to use each dashboard page
- `PRESENTATION.md` - 8-slide presentation (storytelling format)

### Weekly Analyses
- `Week3_Analysis.docx` - Univariate & Bivariate findings
- `Week4_Analysis.docx` - Device & Activity analysis
- `Week5_Analysis.docx` - Cohort & Segment analysis
- `Week6_Analysis.docx` - Decision support & ROI modeling

### Notebooks
- `Week1_Data_Preparation.ipynb` - ETL and data cleaning
- `Week2_Feature_Engineering.ipynb` - Feature creation
- `Week3_Descriptive_Analysis.ipynb` - Univariate & Bivariate
- `Week4_Dimensional_Analysis.ipynb` - Combinations & Interactions
- `Week5_Cohort_Analysis.ipynb` - Segmentation & Profiling
- `Week6_What_If_Modeling.ipynb` - Scenario analysis

---

## 🔄 How to Contribute

Found an issue or want to improve?

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add YourFeature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a Pull Request

---

## 📋 Changelog

**Version 1.0 (06-12-2025)**
- ✅ Initial project completion
- ✅ All 6 weeks of analysis complete
- ✅ Dashboard with 27+ visualizations
- ✅ Comprehensive documentation
- ✅ Presentation materials
- ✅ GitHub repository setup

---

## ⭐ Fun Facts

- 📊 **27+ Visualizations** across 7 dashboard pages
- 🔧 **15+ DAX Measures** for dynamic calculations
- 📈 **6 Weeks** of progressive analytical sophistication
- 🎯 **54%** of problem concentrated in 5 cohorts
- 🚀 **+57.8%** population health improvement possible
- 👶 **9,712** children analyzed
- 🌍 **2 Regions** analyzed (Urban/Rural)
- 📱 **4 Device Types** compared

---

**Made with ❤️ by Afzal Hussain S**  
**Infosys Springboard 6.0 - Batch 4 (2025)**

---

## 🌟 Star This Repository

If you find this project helpful for learning data analytics or Power BI, please give it a star! ⭐

---

**Last Updated:** 07-12-2025  
**Status:** Complete & Ready for Deployment
