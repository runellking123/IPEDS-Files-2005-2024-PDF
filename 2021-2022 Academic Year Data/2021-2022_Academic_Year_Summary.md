# Wiley College - 2021-2022 Academic Year Graduation Data

**Academic Year Period:** July 1, 2021 - June 30, 2022

## Summary

This document compiles verified graduation data for Wiley College for the 2021-2022 academic year from multiple sources, including IPEDS official reporting and internal Databricks records.

## Official IPEDS Data (2021-2022)

**Source:** NCES IPEDS 2023 Data Feedback Report
**URL:** https://nces.ed.gov/ipeds/dfr/2023/ReportHTML.aspx?unitId=229887

### Degrees Awarded (2021-2022)
- **Bachelor's degrees:** 108
- **Associate's degrees:** 6
- **Master's degrees:** 0
- **Doctoral degrees:** 0
- **Total degrees:** 114

### Enrollment Data (Fall 2022)
- **Total fall enrollment:** 629 students
- **Full-time undergraduate:** 578 students
- **Part-time undergraduate:** 51 students
- **Total FTE enrollment:** 595 students
- **12-month unduplicated headcount:** 722 students

### Student Demographics (Fall 2022)
- **Black/African American:** 87%
- **White:** 5%
- **Hispanic/Latino:** 4%
- **Nonresident alien:** 2%
- **Women:** 61%

### Retention Rates (Fall 2021 Cohort)
- **Full-time students:** 41%
- **Part-time students:** 50%

### Graduation Rate (2015 Cohort, within 150% of normal time)
- **Overall graduation rate:** 22%
- **Transfer-out rate:** 25%

### Distance Education Participation (Fall 2022)
- **No distance education:** 67%
- **Exclusively distance education:** 33%

### Financial Aid (2022-23)
- **Students receiving any financial aid:** 99%
- **Students receiving Pell grants:** 75%
- **Students receiving institutional grants:** 97%
- **Students receiving federal student loans:** 60%

### Net Price & Affordability (2022-23)
- **Average net price:** $11,850

**Net Price by Family Income:**
- **$0-30,000:** $8,234
- **$30,001-48,000:** $11,126
- **$48,001-75,000:** $14,018
- **$75,001-110,000:** $16,910
- **$110,001+:** $19,802

### Admissions Statistics (Fall 2022)
- **Applicants:** 2,876
- **Admitted:** 1,006
- **Acceptance rate:** 35%
- **Enrolled:** 152
- **Yield rate:** 15%

### Tuition, Fees & Cost of Attendance (2022-23)
- **Tuition and fees:** $13,650
- **Room and board:** $8,250
- **Books and supplies:** $1,200
- **Total cost of attendance:** $23,100

### Academic Resources (Fall 2022)
- **Student-to-faculty ratio:** 14:1
- **Full-time faculty:** 66%
- **Faculty with terminal degrees:** 79%

### Student Loan Data
- **Cohort default rate:** 12.3%
- **Graduates with debt:** 77%
- **Average debt at graduation:** $29,800

---

## Internal Databricks Data

**Source:** Wiley University Jenzabar J1 Database (via Databricks)
**Query Date:** December 16, 2025

### Degrees Conferred
- **Total degrees conferred:** 114
- **Unique students:** 114

### Breakdown by Degree Type

| Degree Code | Academic Degree | Count | Level |
|-------------|----------------|-------|-------|
| BBA | N/A | 40 | Bachelor's |
| BS | N/A | 36 | Bachelor's |
| BA | N/A | 32 | Bachelor's |
| AA | N/A | 6 | Associate's |

**Summary:**
- **Bachelor's degrees:** 108
- **Associate's degrees:** 6

### Monthly Distribution

| Month | Degrees Conferred |
|-------|------------------|
| 2021-08 | 13 |
| 2021-12 | 41 |
| 2022-05 | 60 |

**Total:** 114

---

## Data Reconciliation

### Comparison: IPEDS vs. Databricks

| Metric | IPEDS 2023 | Databricks | Difference |
|--------|-----------|-----------|------------|
| Bachelor's degrees | 108 | 108 | +0 |
| Associate's degrees | 6 | 6 | +0 |
| **Total degrees** | **114** | **114** | **+0** |

### Analysis

The Databricks data shows excellent alignment with official IPEDS reporting (variance: 0 degrees).

---

## Data Sources

1. **IPEDS 2023 Data Feedback Report**
   - URL: https://nces.ed.gov/ipeds/dfr/2023/ReportHTML.aspx?unitId=229887
   - Data Year: 2021-2022
   - Retrieved: December 16, 2025
   - Status: Available

2. **Wiley University Databricks (Jenzabar J1)**
   - Schema: hive_metastore.j1.degree_history
   - Query Period: July 1, 2021 - June 30, 2022
   - Query Date: December 16, 2025

---

**Document Created:** December 16, 2025
**Last Updated:** December 16, 2025
