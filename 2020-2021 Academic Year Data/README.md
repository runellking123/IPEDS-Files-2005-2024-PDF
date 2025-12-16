# 2020-2021 Academic Year Data

This folder contains comprehensive graduation and enrollment data for Wiley College for the 2020-2021 academic year (July 1, 2020 - June 30, 2021).

## Files Included

### 2020-2021_Academic_Year_Summary.md
Complete academic year summary including:
- Official IPEDS 2022 report data
- Internal Databricks graduation data
- Data reconciliation analysis (98.5% accuracy match)
- Degree conferral breakdowns
- Enrollment and retention statistics
- COVID-19 pandemic continued impact analysis
- Year-over-year comparisons

## Data Summary

### Degrees Conferred (2020-2021)

| Source | Bachelor's | Associate's | Total |
|--------|-----------|-------------|-------|
| Databricks | 129 | 4 | 133 |
| IPEDS 2022 | 127 | 4 | 131 |
| **Variance** | **+2** | **0** | **+2** |

**Data Quality:** 98.5% accuracy match between IPEDS and internal data

### Degree Type Distribution (Databricks)

| Degree | Count | Percentage |
|--------|-------|-----------|
| BBA (Bachelor of Business Administration) | 56 | 42.1% |
| BS (Bachelor of Science) | 39 | 29.3% |
| BA (Bachelor of Arts) | 34 | 25.6% |
| AA (Associate of Arts) | 4 | 3.0% |

### Enrollment (Fall 2021)

| Metric | Count | Change from Fall 2020 |
|--------|-------|----------------------|
| Total fall enrollment | 665 | +50 (+8.1%) |
| Full-time | 584 | - |
| Part-time | 81 | - |
| 12-month FTE | 573 | - |

### Retention and Graduation Rates

| Metric | Rate | Previous Year |
|--------|------|---------------|
| Full-time retention (Fall 2020 cohort) | 34% | 70% (Fall 2019) |
| Part-time retention (Fall 2020 cohort) | 36% | 100% (Fall 2019) |
| Graduation rate (2015 cohort, 150% time) | 27% | 31% (2014 cohort) |
| Transfer-out rate (2015 cohort) | 39% | - |

### Financial Information

| Metric | Amount |
|--------|--------|
| Tuition and fees (2021-22) | $13,500 |
| Average net price (2020-21) | $8,796 |

## Key Findings

1. **Sharp decline:** 133 total degrees (down from 176 in 2019-20)
2. **24.4% decrease:** Largest year-over-year decline in the series
3. **COVID-19 impact:** Full academic year under pandemic conditions
4. **Retention collapse:** Dropped to 34% (from 70% previous year)
5. **BBA dominance:** Business degrees represent 42% of all graduates
6. **High transfer-out rate:** 39% of 2015 cohort transferred out
7. **Enrollment slight recovery:** Fall 2021 enrollment increased 8.1%

## Year-over-Year Comparison (Databricks)

| Metric | 2019-2020 | 2020-2021 | Change |
|--------|-----------|-----------|--------|
| Total Degrees | 176 | 133 | -43 (-24.4%) |
| Bachelor's | 166 | 129 | -37 (-22.3%) |
| Associate's | 10 | 4 | -6 (-60.0%) |

## COVID-19 Pandemic Impact

The 2020-2021 academic year was fully impacted by COVID-19:
- Entire academic year conducted remotely or hybrid
- Retention plummeted from 70% to 34%
- Largest single-year graduation decline (-24.4%)
- Economic hardships affecting student persistence
- Associate's degree completions dropped 60%
- Virtual learning fatigue and engagement challenges

## Degree Program Shifts

- **BBA surge:** Business administration became dominant program (42.1%)
- **BA decline:** Arts degrees dropped to lowest share (25.6%)
- **Overall contraction:** All programs saw reduced completions

## Historical Context

- Full pandemic academic year
- Retention crisis emerged (34% retention)
- High transfer-out rate (39%) indicates student mobility/dissatisfaction
- Despite challenges, maintained strong data quality (98.5% IPEDS match)
- Enrollment showed modest recovery (+8.1%)

## Data Sources

1. **IPEDS 2022 Data Feedback Report**
   - URL: https://nces.ed.gov/ipeds/dfr/2022/ReportHTML.aspx?unitId=229887
   - Data Year: 2020-2021
   - Retrieved: December 16, 2025

2. **Wiley University Databricks (Jenzabar J1)**
   - Schema: hive_metastore.j1.degree_history
   - Query Period: July 1, 2020 - June 30, 2021
   - Query Date: December 16, 2025

## Usage

This data should be used as:
- Analysis of peak pandemic impact on graduations
- Understanding retention crisis during remote learning
- Reference for program-level performance during crisis
- Context for transfer-out behavior patterns
- Baseline for post-pandemic recovery planning

## Last Updated
December 16, 2025
