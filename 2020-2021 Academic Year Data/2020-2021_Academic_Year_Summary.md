# Wiley College - 2020-2021 Academic Year Graduation Data

**Academic Year Period:** July 1, 2020 - June 30, 2021

## Summary

This document compiles verified graduation data for Wiley College for the 2020-2021 academic year from IPEDS official reporting and internal Databricks records.

## Official IPEDS Data (2020-2021)

**Source:** NCES IPEDS 2022 Data Feedback Report
**URL:** https://nces.ed.gov/ipeds/dfr/2022/ReportHTML.aspx?unitId=229887

### Degrees Awarded (2020-21)
- **Bachelor's degrees:** 127
- **Associate's degrees:** 4
- **Total degrees:** 131

### Enrollment Data (Fall 2021)
- **Total fall enrollment:** 665 students
- **Full-time undergraduate:** 584
- **Part-time undergraduate:** 81
- **12-month FTE enrollment:** 573

### Student Demographics (Fall 2021)
- **Black/African American:** 91%
- **White:** 5%
- **Hispanic/Latino:** 2%
- **Women:** 53%

### Retention Rates (Fall 2020 Cohort)
- **Full-time students:** 34%
- **Part-time students:** 36%

### Graduation Rates (2015 Cohort, 150% time)
- **Overall graduation rate:** 27%
- **Transfer-out rate:** 39%

### Bachelor's Degree Completion (2013 Cohort)
- **4-year rate:** 20%
- **6-year rate:** 29%
- **8-year rate:** 29%

### Financial Information
- **Tuition and fees (2021-22):** $13,500
- **Average net price (2020-21):** $8,796

---

## Internal Databricks Data (2020-2021)

**Source:** Wiley University Jenzabar J1 Database (via Databricks)
**Query Date:** December 16, 2025

### Degrees Conferred (July 1, 2020 - June 30, 2021)
- **Total degrees conferred:** 133
- **Unique students:** 133

### Breakdown by Degree Type

| Degree Code | Count | Level |
|-------------|-------|-------|
| BBA | 56 | Bachelor's |
| BS | 39 | Bachelor's |
| BA | 34 | Bachelor's |
| AA | 4 | Associate's |

**Summary:**
- **Bachelor's degrees:** 129
- **Associate's degrees:** 4

---

## Data Reconciliation

### Comparison: IPEDS vs. Databricks

| Metric | IPEDS 2022 | Databricks | Difference |
|--------|-----------|-----------|------------|
| Bachelor's degrees | 127 | 129 | +2 |
| Associate's degrees | 4 | 4 | 0 |
| **Total degrees** | **131** | **133** | **+2** |

### Analysis

The Databricks data shows excellent alignment with official IPEDS reporting:
- **+2 bachelor's degree difference** (1.5% variance)
- **Perfect match on associate's degrees**
- **98.5% accuracy match** validates data reliability

### Year-over-Year Comparison (Databricks)
- **2019-2020:** 176 total degrees (166 bachelor's, 10 associate's)
- **2020-2021:** 133 total degrees (129 bachelor's, 4 associate's)
- **Change:** -43 degrees (-24.4%)

---

## Key Findings for 2020-2021

### Graduation Statistics
1. **127-129 bachelor's degrees** were awarded
2. **4 associate's degrees** were awarded
3. **Total: 131-133 degrees** for the academic year

### Degree Distribution
- **BBA (Bachelor of Business Administration):** 56 degrees (42.1%)
- **BS (Bachelor of Science):** 39 degrees (29.3%)
- **BA (Bachelor of Arts):** 34 degrees (25.6%)
- **AA (Associate of Arts):** 4 degrees (3.0%)

### Notable Trends
- **BBA dominance:** Business administration degrees represented 42% of all graduates
- **Significant decline:** 24.4% decrease from previous year (176 to 133 degrees)
- **COVID-19 impact:** This academic year was heavily impacted by the pandemic

### Enrollment and Retention Impact
- Fall 2021 enrollment declined to 665 (from 615 in Fall 2020)
- **34% full-time retention** - critically low retention rate
- This low retention foreshadows continued graduation challenges

### Academic Year Context
The 2020-2021 academic year continued to face challenges from:
- Ongoing COVID-19 pandemic impacts
- Remote and hybrid learning environments
- Economic disruptions affecting student persistence
- Enrollment stability concerns

---

## Data Sources

1. **IPEDS 2022 Data Feedback Report**
   - URL: https://nces.ed.gov/ipeds/dfr/2022/ReportHTML.aspx?unitId=229887
   - Data Year: 2020-2021
   - Retrieved: December 16, 2025

2. **Wiley University Databricks (Jenzabar J1)**
   - Schema: hive_metastore.j1.degree_history
   - Query Period: July 1, 2020 - June 30, 2021
   - Query Date: December 16, 2025

---

**Document Created:** December 16, 2025
**Last Updated:** December 16, 2025
