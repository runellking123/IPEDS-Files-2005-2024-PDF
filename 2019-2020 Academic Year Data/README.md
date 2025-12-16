# 2019-2020 Academic Year Data

This folder contains comprehensive graduation and enrollment data for Wiley College for the 2019-2020 academic year (July 1, 2019 - June 30, 2020).

## Files Included

### 2019-2020_Academic_Year_Summary.md
Complete academic year summary including:
- Official IPEDS 2021 report data
- Internal Databricks graduation data
- Data reconciliation analysis (99.4% accuracy match)
- Monthly distribution of degrees conferred
- Enrollment and retention statistics
- Year-over-year comparisons
- COVID-19 pandemic impact analysis

## Data Summary

### Degrees Conferred (2019-2020)

| Source | Bachelor's | Associate's | Total |
|--------|-----------|-------------|-------|
| Databricks | 166 | 10 | 176 |
| IPEDS 2021 | 165 | 10 | 175 |
| **Variance** | **+1** | **0** | **+1** |

**Data Quality:** 99.4% accuracy match between IPEDS and internal data

### Degree Type Distribution (Databricks)

| Degree | Count | Percentage |
|--------|-------|-----------|
| BA (Bachelor of Arts) | 71 | 40.3% |
| BBA (Bachelor of Business Administration) | 54 | 30.7% |
| BS (Bachelor of Science) | 41 | 23.3% |
| AA (Associate of Arts) | 10 | 5.7% |

### Monthly Distribution

| Month | Degrees | Typical Term |
|-------|---------|--------------|
| August 2019 | 15 | Summer 2019 |
| December 2019 | 34 | Fall 2019 |
| May 2020 | 127 | Spring 2020 |

### Enrollment (Fall 2020)

| Metric | Count | Change from Fall 2019 |
|--------|-------|----------------------|
| Total enrollment | 615 | -505 (-45%) |
| Full-time | 555 | - |
| Part-time | 60 | - |

### Retention and Graduation Rates

| Metric | Rate | Previous Year |
|--------|------|---------------|
| Full-time retention (Fall 2019 cohort) | 70% | 39% (Fall 2018) |
| Part-time retention (Fall 2019 cohort) | 100% | - |
| Graduation rate (2014 cohort, 150% time) | 31% | 38% (2012 cohort) |

## Key Findings

1. **Continued decline:** 176 total degrees (down from 195 in 2018-19)
2. **9.7% decrease:** Smallest year-over-year decline in recent years
3. **Excellent data quality:** Near-perfect match between IPEDS and Databricks
4. **Retention improvement:** Dramatic increase to 70% (up from 39%)
5. **Spring 2020 concentration:** 72% of degrees conferred in May 2020
6. **COVID-19 impact:** Pandemic began March 2020, affecting spring operations
7. **Enrollment collapse:** 45% enrollment decline (Fall 2020)

## Year-over-Year Comparison (Databricks)

| Metric | 2018-2019 | 2019-2020 | Change |
|--------|-----------|-----------|--------|
| Total Degrees | 195 | 176 | -19 (-9.7%) |
| Bachelor's | 189 | 166 | -23 (-12.2%) |
| Associate's | 6 | 10 | +4 (+66.7%) |

## COVID-19 Pandemic Impact

The 2019-2020 academic year was significantly impacted by COVID-19:
- Pandemic declaration: March 2020
- Transition to remote learning during Spring 2020
- May 2020 graduations proceeded amid uncertainty (127 degrees)
- Fall 2020 enrollment plummeted 45% (1,120 → 615 students)
- Economic disruptions affecting student persistence
- Virtual commencement ceremonies

## Historical Context

- Last "normal" fall semester (Fall 2019) before pandemic
- Retention improved dramatically (70%), but enrollment declined severely
- Associate's degree completions increased to 10 (highest in recent years)
- Despite challenges, maintained strong data quality and reporting

## Data Sources

1. **IPEDS 2021 Data Feedback Report**
   - URL: https://nces.ed.gov/ipeds/dfr/2021/ReportHTML.aspx?unitId=229887
   - Data Year: 2019-2020
   - Retrieved: December 16, 2025

2. **Wiley University Databricks (Jenzabar J1)**
   - Schema: hive_metastore.j1.degree_history
   - Query Period: July 1, 2019 - June 30, 2020
   - Query Date: December 16, 2025

## Usage

This data should be used as:
- Pre-pandemic and early-pandemic baseline
- Data quality validation reference (99.4% IPEDS match)
- Analysis of COVID-19 initial impacts
- Context for understanding enrollment collapse
- Reference for retention recovery strategies (70% achievement)

## Last Updated
December 16, 2025
