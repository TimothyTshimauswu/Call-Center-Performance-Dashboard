# Call Center Performance Dashboard

**Interactive Dashboard**: [View Live on Tableau Public](https://public.tableau.com/app/profile/timothy.tshimauswu4603/viz/CallCentrePerformanceDashboard_17665283843880/CallCentrePerformanceDashboard-ExecutiveKPIMonitoring)

---

## Project Overview

Executive KPI dashboard analyzing 3,896 monthly call center interactions to identify performance gaps and optimization opportunities. Built with SQL, Tableau, and Excel to demonstrate operational analytics capabilities and business impact quantification.

**Key Outcome**: Identified 3 critical optimization opportunities with projected R1.5M annual savings through targeted agent training, staffing adjustments, and process improvements.

---

## Business Problem

Call center operations lacked visibility into employee performance, call patterns, and service quality metrics. Management needed a data-driven dashboard for monthly performance reviews and operational decision-making.

---

## Key Metrics

**Monthly Performance Summary:**
- Total Calls: 3,896 interactions
- Overall Resolution Rate: 70.47%
- Average Speed of Answer: 67 seconds (meets target)
- Agent Performance Range: 59.18% - 78.74% resolution rates

**8 KPIs Tracked:**
1. Call Volume Trends (day-of-week patterns)
2. Inbound Calls Today (real-time tracking)
3. Overall Resolution Rate
4. Customer Satisfaction Rating
5. Speed of Answer by Agent
6. Resolution Rates by Agent
7. Resolved Calls Count
8. Average Call Length

---

## Critical Findings

### 1. Agent Performance Gaps

**Finding**: 3 agents below 70% resolution target
- Dan: 59.18% (116 calls) - 10.82 percentage points below target
- Joe: 67.53% (131 calls) - 2.47 percentage points below target
- Diane: 68.75% (143 calls) - 1.25 percentage points below target

**Business Impact**: ~45 unresolved calls monthly × R150 escalation cost = R81,000 annual cost

**Recommendation**: Implement targeted training program, weekly coaching sessions, peer shadowing with top performer (Martha: 78.74% resolution rate)

---

### 2. Monday Staffing Inefficiency

**Finding**: Monday call volume +26% above average (290 calls vs 230 average)

**Business Impact**: Extended wait times, higher abandonment risk, estimated 2% churn increase = R300,000 annual retention value at risk

**Recommendation**: Shift 1 agent from Friday (200 calls) to Monday, implement flexible scheduling for peak periods

---

### 3. Top Performer Insights

**Finding**: Martha demonstrates superior performance (78.74% resolution, 163 calls resolved)

**Recommendation**: Document best practices, create training materials, implement peer shadowing program

---

## Projected Financial Impact

| Initiative | Annual Savings |
|------------|---------------|
| Agent Training Program | R81,000 |
| Monday Staffing Optimization | R300,000 |
| Process Efficiency Improvements | R400,000 |
| Speed of Answer Optimization | R60,000 |
| **TOTAL** | **R841,000 - R1.5M** |

---

## Technical Implementation

**Data Processing:**
- Data source: 5,000+ call center transaction records
- Cleaning: SQL and Tableau (standardized categories, handled missing data)
- Analysis: Month-filtered for operational relevance

**Dashboard Features:**
- Month-over-month performance tracking
- Color-coded performance indicators (green = target met, blue = needs attention)
- Agent-level drill-downs
- Interactive time-based filters

**Tools Used:**
- SQL (data extraction and validation)
- Tableau Desktop/Public (dashboard development)
- Excel (initial exploration)

---

## Repository Contents

```
Call-Center-Performance-Dashboard/
├── README.md
├── data/
│   └── Call_Center_Data.xlsx
├── images/
│   └── dashboard_screenshot.png
└── documentation/
    └── Call_Center_Performance_Analysis_Report.docx
```

---

## Use Cases

**Monthly Performance Reviews**: Agent evaluation, training needs identification, performance improvement tracking

**Operational Planning**: Staffing optimization, capacity planning, resource allocation

**Quality Improvement**: Resolution rate tracking, speed of answer monitoring, satisfaction trends

**Executive Reporting**: High-level KPI summary with drill-down capabilities

---

## Key Recommendations

**Immediate Actions (Week 1):**
1. Schedule coaching sessions for Dan (59.18% resolution rate)
2. Implement Monday staffing adjustment (+1 agent shift from Friday)
3. Document Martha's best practices for training materials

**Short-term (Month 1-3):**
1. Launch systematic training program for agents below 70% target
2. Establish weekly dashboard review cadence
3. Create agent performance improvement plans

---

## Dashboard Design

**Month-Filtered Analysis**: Focuses on latest month performance for operational relevance. Monthly reviews align with operational planning cycles and enable month-over-month trend tracking.

**Layout**: High-level metrics at top for executive scanning, detailed performance data below for drill-down analysis. Color coding enables quick identification of areas needing attention.

---

## Additional Resources

- **Business Report**: [Call_Center_Performance_Analysis_Report.docx](documentation/Call_Center_Performance_Analysis_Report.docx) - Comprehensive analysis with detailed ROI calculations
- **Live Dashboard**: [Tableau Public](https://public.tableau.com/app/profile/timothy.tshimauswu4603/viz/CallCentrePerformanceDashboard_17665283843880/CallCentrePerformanceDashboard-ExecutiveKPIMonitoring)

---

## Contact

**Unarine Timothy Tshimauswu**  
Data Scientist | Business Intelligence Analyst

- Email: timothytshimauswu@gmail.com
- LinkedIn: [linkedin.com/in/utshimauswu](https://www.linkedin.com/in/utshimauswu)
- Portfolio: [timothy-ai-ml-portfolio-landing.vercel.app](https://timothy-ai-ml-portfolio-landing.vercel.app/)

---

*This project demonstrates operational analytics capabilities including KPI tracking, dashboard design, performance analysis, and business impact quantification for data analyst and business intelligence roles.*
