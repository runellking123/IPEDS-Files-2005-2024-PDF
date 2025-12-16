# 2018-2019 Academic Year Data

This folder contains comprehensive graduation and enrollment data for Wiley College for the 2018-2019 academic year (July 1, 2018 - June 30, 2019).

## Files Included

### 2018-2019_Academic_Year_Summary.md
Complete academic year summary including:
- Official IPEDS 2019 report data (2017-18 actual year)
- Internal Databricks graduation data (2018-19 actual year)
- Degree conferral breakdowns
- Enrollment and retention statistics
- Year-over-year comparisons

## Data Summary

### Degrees Conferred (2018-2019)

| Source | Bachelor's | Associate's | Total |
|--------|-----------|-------------|-------|
| Databricks | 189 | 6 | 195 |
| IPEDS 2019 (2017-18 data) | 224 | 1 | 225 |

**Note:** IPEDS 2019 report contains data from the 2017-18 academic year, not 2018-19.

### Degree Type Distribution (Databricks 2018-19)

| Degree | Count | Percentage |
|--------|-------|-----------|
| BA (Bachelor of Arts) | 68 | 34.9% |
| BBA (Bachelor of Business Administration) | 62 | 31.8% |
| BS (Bachelor of Science) | 59 | 30.3% |
| AA (Associate of Arts) | 6 | 3.1% |

### Enrollment (Fall 2018)

| Metric | Count |
|--------|-------|
| Total enrollment | 1,600 |
| Full-time | 877 |
| Part-time | 126 |
| Total FTE | 1,206 |

### Retention and Graduation Rates

| Metric | Rate |
|--------|------|
| Full-time retention (Fall 2017 cohort) | 39% |
| Graduation rate (2012 cohort, 150% time) | 38% |
| 6-year bachelor's rate (2012 cohort) | 18% |

## Key Findings

1. **Continued decline:** 195 total degrees (down from 229 in 2017-18)
2. **14.8% decrease:** Second consecutive year of significant decline
3. **Enrollment peak:** Fall 2018 enrollment reached 1,600 students (highest in period)
4. **Retention crisis:** Only 39% full-time retention signals future challenges
5. **Increase in associate's degrees:** 6 AA degrees conferred (up from 1)

## Year-over-Year Comparison (Databricks)

| Metric | 2017-2018 | 2018-2019 | Change |
|--------|-----------|-----------|--------|
| Total Degrees | 229 | 195 | -34 (-14.8%) |
| Bachelor's | 228 | 189 | -39 (-17.1%) |
| Associate's | 1 | 6 | +5 (+500%) |

## Historical Context

- Peak enrollment year (1,600 students) coincides with declining graduations
- Critical retention rate of 39% foreshadows continued graduation challenges
- Graduation-enrollment mismatch indicates systemic retention/completion issues
- Last year before COVID-19 pandemic impact

## Data Sources

1. **IPEDS 2019 Data Feedback Report**
   - URL: https://nces.ed.gov/ipeds/dfr/2019/ReportHTML.aspx?unitId=229887
   - Data Year: 2017-2018 (note: one year lag)
   - Retrieved: December 16, 2025

2. **Wiley University Databricks (Jenzabar J1)**
   - Schema: hive_metastore.j1.degree_history
   - Query Period: July 1, 2018 - June 30, 2019
   - Query Date: December 16, 2025

## Usage

This data should be used as:
- Pre-pandemic baseline reference
- Analysis of enrollment-graduation disconnect
- Warning indicator of retention challenges
- Context for understanding subsequent pandemic impacts

## Last Updated
December 16, 2025
