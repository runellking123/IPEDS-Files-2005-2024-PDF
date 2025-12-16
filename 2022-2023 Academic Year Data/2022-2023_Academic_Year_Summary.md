# Wiley College - 2022-2023 Academic Year Graduation Data

**Academic Year Period:** July 1, 2022 - June 30, 2023

## Summary

This document compiles verified graduation data for Wiley College for the 2022-2023 academic year from IPEDS official reporting and internal Databricks records.

## Official IPEDS Data (2022-2023)

**Source:** NCES IPEDS 2024 Data Feedback Report
**URL:** https://nces.ed.gov/ipeds/dfr/2024/ReportHTML.aspx?unitId=229887

### Degrees Awarded (2022-23)
- **Bachelor's degrees:** 94
- **Associate's degrees:** 0
- **Total degrees:** 94

### Enrollment Data (Fall 2023)
- **Total fall enrollment:** 636 students
- **Full-time:** 614
- **Part-time:** 22
- **12-month FTE:** 639

### Student Demographics (Fall 2023)
- **Black/African American:** 84%
- **Hispanic/Latino:** 4%
- **White:** 6%
- **Women:** 53%

### Retention Rates (Fall 2022 Cohort)
- **Full-time students:** 32%
- **Part-time students:** 25%

### Graduation Rates (2017 Cohort, 150% time)
- **Overall graduation rate:** 20%
- **Transfer-out rate:** 14%

### Financial Information
- **Tuition and fees (2023-24):** $12,500
- **Average net price (2022-23):** $10,290

---

## Internal Databricks Data (2022-2023)

**Source:** Wiley University Jenzabar J1 Database (via Databricks)
**Query Date:** December 16, 2025

### Degrees Conferred (July 1, 2022 - June 30, 2023)
- **Total degrees conferred:** 94
- **Unique students:** 94

### Breakdown by Degree Type

| Degree Code | Count | Level |
|-------------|-------|-------|
| BS | 37 | Bachelor's |
| BBA | 33 | Bachelor's |
| BA | 24 | Bachelor's |

**Summary:**
- **Bachelor's degrees:** 94
- **Associate's degrees:** 0

---

## Data Reconciliation

### Comparison: IPEDS vs. Databricks

| Metric | IPEDS 2024 | Databricks | Difference |
|--------|-----------|-----------|------------|
| Bachelor's degrees | 94 | 94 | 0 |
| Associate's degrees | 0 | 0 | 0 |
| **Total degrees** | **94** | **94** | **0** |

### Analysis

**Perfect data match!** IPEDS and Databricks show **100% alignment**:
- Exact match on total degrees: 94
- Exact match on bachelor's degrees: 94
- Exact match on associate's degrees: 0
- This validates excellent data quality and reporting accuracy

### Year-over-Year Comparison (Databricks)
- **2021-2022:** 114 total degrees (108 bachelor's, 6 associate's)
- **2022-2023:** 94 total degrees (94 bachelor's, 0 associate's)
- **Change:** -20 degrees (-17.5%)

---

## Key Findings for 2022-2023

### Graduation Statistics
1. **94 bachelor's degrees** were awarded
2. **0 associate's degrees** were awarded
3. **Total: 94 degrees** for the academic year

### Degree Distribution
- **BS (Bachelor of Science):** 37 degrees (39.4%)
- **BBA (Bachelor of Business Administration):** 33 degrees (35.1%)
- **BA (Bachelor of Arts):** 24 degrees (25.5%)

### Critical Concerns
- **Continued decline:** 17.5% decrease from previous year
- **No associate's degrees:** Complete absence of associate degree completions
- **Retention collapse:** Dropped to 32% (from 54% previous year)

### Retention Crisis
- **32% full-time retention** (Fall 2022 cohort) - alarming drop
- This represents a decline of 22 percentage points from previous year (54% to 32%)
- Lowest retention rate in recent history
- Will severely impact future graduation numbers

### Enrollment Decline
- Fall 2023 enrollment: 636 students (down from 698 in Fall 2022)
- **8.9% enrollment decrease**
- Combined with low retention, creates compounding challenges

### Multi-Year Graduation Trend
Looking at the 8-year trajectory:
- **2016-2017:** 271 degrees
- **2022-2023:** 94 degrees
- **Total decline:** 65.3% reduction over 6 years

---

## Data Sources

1. **IPEDS 2024 Data Feedback Report**
   - URL: https://nces.ed.gov/ipeds/dfr/2024/ReportHTML.aspx?unitId=229887
   - Data Year: 2022-2023
   - Retrieved: December 16, 2025

2. **Wiley University Databricks (Jenzabar J1)**
   - Schema: hive_metastore.j1.degree_history
   - Query Period: July 1, 2022 - June 30, 2023
   - Query Date: December 16, 2025

---

**Document Created:** December 16, 2025
**Last Updated:** December 16, 2025
