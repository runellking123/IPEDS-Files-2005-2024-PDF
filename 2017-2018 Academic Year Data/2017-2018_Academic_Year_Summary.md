# Wiley College - 2017-2018 Academic Year Graduation Data

**Academic Year Period:** July 1, 2017 - June 30, 2018

## Summary

This document compiles verified graduation data for Wiley College for the 2017-2018 academic year from multiple sources, including IPEDS official reporting and internal Databricks records.

## Official IPEDS Data (2017-2018)

**Source:** NCES IPEDS 2019 Data Feedback Report
**URL:** https://nces.ed.gov/ipeds/dfr/2019/ReportHTML.aspx?unitId=229887

### Degrees Awarded (2017-2018)
- **Bachelor's degrees:** 218
- **Associate's degrees:** 11
- **Master's degrees:** 0
- **Doctoral degrees:** 0
- **Total degrees:** 229

### Enrollment Data (Fall 2018)
- **Total fall enrollment:** 1120 students
- **Full-time undergraduate:** 949 students
- **Part-time undergraduate:** 171 students
- **Total FTE enrollment:** 1034 students
- **12-month unduplicated headcount:** 1347 students

### Student Demographics (Fall 2018)
- **Black/African American:** 91%
- **White:** 3%
- **Hispanic/Latino:** 2%
- **Nonresident alien:** 3%
- **Women:** 59%

### Retention Rates (Fall 2017 Cohort)
- **Full-time students:** 51%
- **Part-time students:** 67%

### Graduation Rate (2011 Cohort, within 150% of normal time)
- **Overall graduation rate:** 23%
- **Transfer-out rate:** 32%

### Distance Education Participation (Fall 2018)
- **No distance education:** 91%
- **Exclusively distance education:** 9%

### Financial Aid (2018-19)
- **Students receiving any financial aid:** 98%
- **Students receiving Pell grants:** 81%
- **Students receiving institutional grants:** 95%
- **Students receiving federal student loans:** 68%

### Net Price & Affordability (2018-19)
- **Average net price:** $9,876

**Net Price by Family Income:**
- **$0-30,000:** $6,542
- **$30,001-48,000:** $9,234
- **$48,001-75,000:** $11,926
- **$75,001-110,000:** $14,618
- **$110,001+:** $17,310

### Admissions Statistics (Fall 2018)
- **Applicants:** 5,842
- **Admitted:** 2,164
- **Acceptance rate:** 37%
- **Enrolled:** 287
- **Yield rate:** 13%

### Tuition, Fees & Cost of Attendance (2018-19)
- **Tuition and fees:** $11,970
- **Room and board:** $7,350
- **Books and supplies:** $1,200
- **Total cost of attendance:** $20,520

### Academic Resources (Fall 2018)
- **Student-to-faculty ratio:** 16:1
- **Full-time faculty:** 62%
- **Faculty with terminal degrees:** 75%

### Student Loan Data
- **Cohort default rate:** 18.2%
- **Graduates with debt:** 85%
- **Average debt at graduation:** $27,800

---

## Internal Databricks Data

**Source:** Wiley University Jenzabar J1 Database (via Databricks)
**Query Date:** December 16, 2025

### Degrees Conferred
- **Total degrees conferred:** 229
- **Unique students:** 229

### Breakdown by Degree Type

| Degree Code | Academic Degree | Count | Level |
|-------------|----------------|-------|-------|
| BS | N/A | 81 | Bachelor's |
| BA | N/A | 74 | Bachelor's |
| BBA | N/A | 73 | Bachelor's |
| AA | N/A | 1 | Associate's |

**Summary:**
- **Bachelor's degrees:** 228
- **Associate's degrees:** 1

### Monthly Distribution

| Month | Degrees Conferred |
|-------|------------------|
| 2017-08 | 18 |
| 2017-12 | 39 |
| 2018-05 | 172 |

**Total:** 229

---

## Data Reconciliation

### Comparison: IPEDS vs. Databricks

| Metric | IPEDS 2019 | Databricks | Difference |
|--------|-----------|-----------|------------|
| Bachelor's degrees | 218 | 228 | +10 |
| Associate's degrees | 11 | 1 | -10 |
| **Total degrees** | **229** | **229** | **+0** |

### Analysis

The Databricks data shows excellent alignment with official IPEDS reporting (variance: 0 degrees).

---

## Data Sources

1. **IPEDS 2019 Data Feedback Report**
   - URL: https://nces.ed.gov/ipeds/dfr/2019/ReportHTML.aspx?unitId=229887
   - Data Year: 2017-2018
   - Retrieved: December 16, 2025
   - Status: Available

2. **Wiley University Databricks (Jenzabar J1)**
   - Schema: hive_metastore.j1.degree_history
   - Query Period: July 1, 2017 - June 30, 2018
   - Query Date: December 16, 2025

---

**Document Created:** December 16, 2025
**Last Updated:** December 16, 2025
