# Wiley College - 2019-2020 Academic Year Graduation Data

**Academic Year Period:** July 1, 2019 - June 30, 2020

## Summary

This document compiles verified graduation data for Wiley College for the 2019-2020 academic year from multiple sources, including IPEDS official reporting and internal Databricks records.

## Official IPEDS Data (2019-2020)

**Source:** NCES IPEDS 2021 Data Feedback Report
**URL:** https://nces.ed.gov/ipeds/dfr/2021/ReportHTML.aspx?unitId=229887

### Degrees Awarded (2019-2020)
- **Bachelor's degrees:** 165
- **Associate's degrees:** 10
- **Master's degrees:** 0
- **Doctoral degrees:** 0
- **Total degrees:** 175

### Enrollment Data (Fall 2020)
- **Total fall enrollment:** 615 students
- **Full-time undergraduate:** 555 students
- **Part-time undergraduate:** 60 students
- **Total FTE enrollment:** 771 students
- **12-month unduplicated headcount:** 881 students

### Student Demographics (Fall 2020)
- **Black/African American:** 90%
- **White:** 4%
- **Hispanic/Latino:** 2%
- **Nonresident alien:** 3%
- **Women:** 57%

### Retention Rates (Fall 2019 Cohort)
- **Full-time students:** 70%
- **Part-time students:** 100%

### Graduation Rate (2013 Cohort, within 150% of normal time)
- **Overall graduation rate:** 31%
- **Transfer-out rate:** 28%

### Distance Education Participation (Fall 2020)
- **No distance education:** 88%
- **Exclusively distance education:** 12%

---

## Internal Databricks Data

**Source:** Wiley University Jenzabar J1 Database (via Databricks)
**Query Date:** December 16, 2025

### Degrees Conferred
- **Total degrees conferred:** 176
- **Unique students:** 176

### Breakdown by Degree Type

| Degree Code | Academic Degree | Count | Level |
|-------------|----------------|-------|-------|
| BA | N/A | 71 | Bachelor's |
| BBA | N/A | 54 | Bachelor's |
| BS | N/A | 41 | Bachelor's |
| AA | N/A | 10 | Associate's |

**Summary:**
- **Bachelor's degrees:** 166
- **Associate's degrees:** 10

### Monthly Distribution

| Month | Degrees Conferred |
|-------|------------------|
| 2019-08 | 15 |
| 2019-12 | 34 |
| 2020-05 | 127 |

**Total:** 176

---

## Data Reconciliation

### Comparison: IPEDS vs. Databricks

| Metric | IPEDS 2021 | Databricks | Difference |
|--------|-----------|-----------|------------|
| Bachelor's degrees | 165 | 166 | +1 |
| Associate's degrees | 10 | 10 | +0 |
| **Total degrees** | **175** | **176** | **+1** |

### Analysis

The Databricks data shows excellent alignment with official IPEDS reporting (variance: 1 degree).

---

## Data Sources

1. **IPEDS 2021 Data Feedback Report**
   - URL: https://nces.ed.gov/ipeds/dfr/2021/ReportHTML.aspx?unitId=229887
   - Data Year: 2019-2020
   - Retrieved: December 16, 2025
   - Status: Available

2. **Wiley University Databricks (Jenzabar J1)**
   - Schema: hive_metastore.j1.degree_history
   - Query Period: July 1, 2019 - June 30, 2020
   - Query Date: December 16, 2025

---

**Document Created:** December 16, 2025
**Last Updated:** December 16, 2025
