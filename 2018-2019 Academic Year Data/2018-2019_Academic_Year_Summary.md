# Wiley College - 2018-2019 Academic Year Graduation Data

**Academic Year Period:** July 1, 2018 - June 30, 2019

## Summary

This document compiles verified graduation data for Wiley College for the 2018-2019 academic year from IPEDS official reporting and internal Databricks records.

## Official IPEDS Data (2018-2019)

**Source:** NCES IPEDS 2019 Data Feedback Report
**URL:** https://nces.ed.gov/ipeds/dfr/2019/ReportHTML.aspx?unitId=229887

### Degrees Awarded (2017-18)
- **Bachelor's degrees:** 224
- **Associate's degrees:** 1
- **Total degrees:** 225

**Note:** IPEDS reports typically show data from the previous year, so this 2019 report contains 2017-18 data.

### Enrollment Data (Fall 2018)
- **Total unduplicated headcount:** 1,600
- **Full-time students:** 877
- **Part-time students:** 126
- **Total FTE enrollment:** 1,206

### Student Demographics (Fall 2018)
- **Black/African American:** 76%
- **Hispanic/Latino:** 5%
- **White:** 5%
- **Nonresident alien:** 7%
- **Women:** 57%

### Retention Rates (Fall 2017 Cohort)
- **Full-time students:** 39%

### Graduation Rates (2012 Cohort, 150% time)
- **Overall graduation rate:** 38%
- **Bachelor's degree (6 years):** 18%
- **Bachelor's degree (8 years):** 20%

---

## Internal Databricks Data (2018-2019)

**Source:** Wiley University Jenzabar J1 Database (via Databricks)
**Query Date:** December 16, 2025

### Degrees Conferred (July 1, 2018 - June 30, 2019)
- **Total degrees conferred:** 195
- **Unique students:** 195

### Breakdown by Degree Type

| Degree Code | Count | Level |
|-------------|-------|-------|
| BA | 68 | Bachelor's |
| BBA | 62 | Bachelor's |
| BS | 59 | Bachelor's |
| AA | 6 | Associate's |

**Summary:**
- **Bachelor's degrees:** 189
- **Associate's degrees:** 6

---

## Data Reconciliation

### Comparison: IPEDS vs. Databricks

**Note:** IPEDS 2019 report shows 2017-18 data (224 bachelor's, 1 associate's), while Databricks shows 2018-19 conferrals (189 bachelor's, 6 associate's).

The difference reflects different reporting periods:
- IPEDS 2019 reports data from **2017-18** academic year
- Databricks data covers **2018-19** academic year (July 1, 2018 - June 30, 2019)

### Year-over-Year Comparison (Databricks)
- **2017-2018:** 229 total degrees (228 bachelor's, 1 associate's)
- **2018-2019:** 195 total degrees (189 bachelor's, 6 associate's)
- **Change:** -34 degrees (-14.8%)

---

## Key Findings for 2018-2019

### Graduation Statistics
1. **189 bachelor's degrees** were conferred
2. **6 associate's degrees** were conferred
3. **Total: 195 degrees** for the academic year

### Degree Distribution
- **BA (Bachelor of Arts):** 68 degrees (34.9%)
- **BBA (Bachelor of Business Administration):** 62 degrees (31.8%)
- **BS (Bachelor of Science):** 59 degrees (30.3%)
- **AA (Associate of Arts):** 6 degrees (3.1%)

### Enrollment Context
- Fall 2018 enrollment peaked at 1,600 students
- This was a high enrollment period for Wiley College
- Despite high enrollment, graduation numbers continued to decline

### Retention Performance
- **39% full-time retention** (Fall 2017 cohort) - concerning decline from historical levels
- This low retention rate would impact future graduation numbers

---

## Data Sources

1. **IPEDS 2019 Data Feedback Report**
   - URL: https://nces.ed.gov/ipeds/dfr/2019/ReportHTML.aspx?unitId=229887
   - Data Year: 2017-2018
   - Retrieved: December 16, 2025

2. **Wiley University Databricks (Jenzabar J1)**
   - Schema: hive_metastore.j1.degree_history
   - Query Period: July 1, 2018 - June 30, 2019
   - Query Date: December 16, 2025

---

**Document Created:** December 16, 2025
**Last Updated:** December 16, 2025
